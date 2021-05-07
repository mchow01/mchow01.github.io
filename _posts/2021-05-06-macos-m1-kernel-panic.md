---
layout: post
title:  "A Baffling Kernel Panic in macOS"
date:   2021-05-06 21:04:00
categories: macos system internals wtf
---

The problem: it was taking a very long time for my Mac Mini M1 to shutdown.  In fact, it wouldn't shutdown, but rebooted after a long while.  The stackshot is below.

I searched for "watchdog timeout: no checkins from watchdogd" and came across this: [https://apple.stackexchange.com/questions/412584/m1-mac-kernel-panic-on-reboot-no-checkins-from-watchdogd](https://apple.stackexchange.com/questions/412584/m1-mac-kernel-panic-on-reboot-no-checkins-from-watchdogd)

Indeed, my Terminal app was listed in the "Developer Tools" section of Security & Privacy settings in macOS.  I removed it, and problem solved.  Also, the existence of a "Developer Tools" section in the Security & Privacy settings was news to me.

<pre>
panic(cpu 0 caller 0xfffffe0016745e30): watchdog timeout: no checkins from watchdogd in 305 seconds (511 totalcheckins since monitoring last enabled), shutdown in progress
Debugger message: panic
Memory ID: 0xff
OS release type: User
OS version: 20E241
Kernel version: Darwin Kernel Version 20.4.0: Thu Apr 22 21:46:41 PDT 2021; root:xnu-7195.101.2~1/RELEASE_ARM64_T8101
Fileset Kernelcache UUID: 0B829878C98BF0B6E3AF7BF571B60BF2
Kernel UUID: 1DC99FEF-0771-3229-974C-9B18710700AE
iBoot version: iBoot-6723.101.4
secure boot?: YES
Paniclog version: 13
KernelCache slide: 0x000000000bca4000
KernelCache base:  0xfffffe0012ca8000
Kernel slide:      0x000000000c7e4000
Kernel text base:  0xfffffe00137e8000
Kernel text exec base:  0xfffffe00138b0000
mach_absolute_time: 0x1e61d41f56
Epoch Time:        sec       usec
  Boot    : 0x60946d08 0x00015b56
  Sleep   : 0x00000000 0x00000000
  Wake    : 0x00000000 0x00000000
  Calendar: 0x60948237 0x0002e29d

CORE 0 recently retired instr at 0xfffffe0013a20b18
CORE 1 recently retired instr at 0xfffffe0013a21fcc
CORE 2 recently retired instr at 0xfffffe0013a21fcc
CORE 3 recently retired instr at 0xfffffe0013a21fcc
CORE 4 recently retired instr at 0xfffffe0013a21fd0
CORE 5 recently retired instr at 0xfffffe0013a21fd0
CORE 6 recently retired instr at 0xfffffe0013a21fd0
CORE 7 recently retired instr at 0xfffffe0013a21fd0
Total cpu_usage: 13790411
Thread task pri cpu_usage
0xfffffe1666900660 kernel_task 0 6683008
0xfffffe1666d5e640 kernel_task 0 4159352
0xfffffe1666d5ccc0 kernel_task 0 0
0xfffffe1666c74660 kernel_task 0 19556
0xfffffe1666d5dfe0 kernel_task 0 0

Panicked task 0xfffffe1666834688: 35305 pages, 458 threads: pid 0: kernel_task
Panicked thread: 0xfffffe1666900660, backtrace: 0xfffffe30194578b0, tid: 102
		  lr: 0xfffffe00138fe920  fp: 0xfffffe3019457920
		  lr: 0xfffffe00138fe704  fp: 0xfffffe3019457990
		  lr: 0xfffffe0013a27330  fp: 0xfffffe30194579b0
		  lr: 0xfffffe0013a18b90  fp: 0xfffffe3019457a60
		  lr: 0xfffffe00138b77e8  fp: 0xfffffe3019457a70
		  lr: 0xfffffe00138fe394  fp: 0xfffffe3019457e00
		  lr: 0xfffffe00138fe394  fp: 0xfffffe3019457e70
		  lr: 0xfffffe00140ae96c  fp: 0xfffffe3019457e90
		  lr: 0xfffffe0016745e30  fp: 0xfffffe3019457ec0
		  lr: 0xfffffe00167455c8  fp: 0xfffffe3019457f00
		  lr: 0xfffffe0014ca1668  fp: 0xfffffe3019457f20
		  lr: 0xfffffe0014a1a8c8  fp: 0xfffffe3019457fb0
		  lr: 0xfffffe0014003548  fp: 0xfffffe3019457fc0
		  lr: 0xfffffe0013a1b5b8  fp: 0xfffffe3019457fe0
		  lr: 0xfffffe00138b785c  fp: 0xfffffe3019457ff0
		  lr: 0xfffffe00139297a4  fp: 0xfffffe3f630b3ee0
		  lr: 0xfffffe00139299b0  fp: 0xfffffe3f630b3f00
		  lr: 0xfffffe00138c0c38  fp: 0x0000000000000000
      Kernel Extensions in backtrace:
         com.apple.driver.AppleInterruptController(1.0d1)[1903B10D-E35E-3864-9842-4EE73CE97CD2]@0xfffffe0014a18000->0xfffffe0014a1bfff
            dependency: com.apple.driver.AppleARMPlatform(1.0.2)[58B65D99-A7B7-316F-8E28-CEDEE98BBC3E]@0xfffffe001420c000->0xfffffe001425bfff
         com.apple.driver.watchdog(1.0)[BEE7A0FC-B21D-32F4-8632-C669EA683887]@0xfffffe0016744000->0xfffffe0016747fff
         com.apple.driver.AppleS5L8960XWatchDogTimer(1.0)[2B2069CC-0C2D-3A5A-B4FA-D10F4C2D8371]@0xfffffe0014ca0000->0xfffffe0014ca3fff
            dependency: com.apple.driver.AppleARMPlatform(1.0.2)[58B65D99-A7B7-316F-8E28-CEDEE98BBC3E]@0xfffffe001420c000->0xfffffe001425bfff
            dependency: com.apple.driver.watchdog(1)[BEE7A0FC-B21D-32F4-8632-C669EA683887]@0xfffffe0016744000->0xfffffe0016747fff
            dependency: com.apple.iokit.IOReportFamily(47)[789544EB-168A-39BF-9FAB-1D8E60EDF2EE]@0xfffffe0015d18000->0xfffffe0015d1bfff

last started kext at 1049340046: com.apple.filesystems.autofs	3.0 (addr 0xfffffe0013760000, size 16384)
loaded kexts:
com.apple.filesystems.autofs	3.0
com.apple.fileutil	20.036.15
com.apple.driver.AppleTopCaseHIDEventDriver	4040.11
com.apple.iokit.IOBluetoothSerialManager	8.0.4d18
com.apple.driver.AppleBiometricServices	1
com.apple.driver.BCMWLANFirmware4378.Hashstore	1
com.apple.driver.AppleAOPVoiceTrigger	11.5
com.apple.iokit.AppleBCM5701Ethernet	11.0.0
com.apple.driver.AppleThunderboltIP	4.0.3
com.apple.driver.CoreKDL	1
com.apple.driver.SEPHibernation	1
com.apple.driver.AppleUSBDeviceNCM	5.0.0
com.apple.driver.DiskImages.ReadWriteDiskImage	493.0.0
com.apple.driver.DiskImages.UDIFDiskImage	493.0.0
com.apple.driver.DiskImages.RAMBackingStore	493.0.0
com.apple.driver.DiskImages.FileBackingStore	493.0.0
com.apple.driver.AppleSmartBatteryManager	161.0.0
com.apple.filesystems.apfs	1677.100.114
com.apple.driver.AppleFileSystemDriver	3.0.1
com.apple.nke.l2tp	1.9
com.apple.filesystems.tmpfs	1
com.apple.driver.AppleSmartIO2	1
com.apple.driver.ApplePMP	1
com.apple.IOTextEncryptionFamily	1.0.0
com.apple.filesystems.hfs.kext	556.100.11
com.apple.security.BootPolicy	1
com.apple.BootCache	40
com.apple.AppleFSCompression.AppleFSCompressionTypeZlib	1.0.0
com.apple.AppleFSCompression.AppleFSCompressionTypeDataless	1.0.0d1
com.apple.driver.ApplePMPFirmware	1
com.apple.AppleEmbeddedSimpleSPINORFlasher	1
com.apple.driver.AppleSPMIPMU	1.0.1
com.apple.driver.AppleCS42L83Audio	442.26
com.apple.driver.AppleTAS5770LAmp	442.26
com.apple.driver.AppleJPEGDriver	4.6.0
com.apple.driver.AppleMobileDispH13G-DCP	140.0
com.apple.driver.AppleAVD	380
com.apple.driver.AppleAVE2	401.73.2
com.apple.AGXG13G	173.22.1
com.apple.driver.usb.AppleUSBHostT8103	1
com.apple.driver.AudioDMAController-T8103	1.60.5
com.apple.driver.AppleT8020SOCTuner	1
com.apple.driver.AppleT8103CLPCv3	1
com.apple.driver.AppleSPIMC	1
com.apple.driver.AppleS5L8960XNCO	1
com.apple.driver.AppleT8103PMGR	1
com.apple.driver.AppleS8000AES	1
com.apple.driver.AppleS5L8920XPWM	1.0.0d1
com.apple.driver.AppleS8000DWI	1.0.0d1
com.apple.driver.AppleS5L8960XWatchDogTimer	1
com.apple.driver.AppleInterruptController	1.0.0d1
com.apple.driver.AppleBluetoothModule	1
com.apple.driver.AppleSamsungSerial	1.0.0d1
com.apple.driver.AppleBCMWLANBusInterfacePCIe	1
com.apple.driver.AppleMCDP29XXUpdateSupport	1
com.apple.driver.AppleT8020DART	1
com.apple.driver.AppleS5L8940XI2C	1.0.0d2
com.apple.driver.AppleT8101	1
com.apple.driver.AppleM68Buttons	1.0.0d1
com.apple.iokit.IOUserEthernet	1.0.1
com.apple.driver.usb.AppleUSBUserHCI	1
com.apple.iokit.IOKitRegistryCompatibility	1
com.apple.iokit.EndpointSecurity	1
com.apple.driver.AppleDiskImages2	1
com.apple.AppleSystemPolicy	2.0.0
com.apple.nke.applicationfirewall	311
com.apple.kec.InvalidateHmac	1
com.apple.kext.triggers	1.0
com.apple.driver.AppleActuatorDriver	4440.3
com.apple.driver.AppleMultitouchDriver	4440.3
com.apple.driver.AppleInputDeviceSupport	4400.35
com.apple.driver.AppleHSBluetoothDriver	4040.11
com.apple.driver.IOBluetoothHIDDriver	8.0.4d18
com.apple.iokit.IOAVBFamily	940.4
com.apple.plugin.IOgPTPPlugin	980.4
com.apple.iokit.IOEthernetAVBController	1.1.0
com.apple.driver.AppleMesaSEPDriver	100.99
com.apple.iokit.IOBiometricFamily	1
com.apple.driver.usb.IOUSBHostHIDDevice	1.2
com.apple.driver.usb.cdc	5.0.0
com.apple.driver.AppleUSBAudio	405.39
com.apple.iokit.IOAudioFamily	300.6.1
com.apple.vecLib.kext	1.2.0
com.apple.driver.AppleAOPAudio	16.2
com.apple.driver.IOBluetoothHostControllerPCIeTransport	8.0.4d18
com.apple.iokit.IOBluetoothHostControllerTransport	8.0.4d18
com.apple.driver.AppleConvergedIPCOLYBTControl	1
com.apple.driver.AppleConvergedPCI	1
com.apple.driver.AppleBluetoothDebug	1
com.apple.driver.usb.AppleEmbeddedUSBXHCIPCI	1
com.apple.driver.usb.AppleUSBXHCIPCI	1.2
com.apple.driver.AppleEmbeddedUSB	1
com.apple.driver.AppleTrustedAccessory	1
com.apple.driver.AppleSEPHDCPManager	1.0.1
com.apple.iokit.AppleSEPGenericTransfer	1
com.apple.driver.usb.networking	5.0.0
com.apple.driver.DiskImages.KernelBacked	493.0.0
com.apple.driver.AppleThunderboltDPInAdapter	8.1.4
com.apple.driver.AppleThunderboltDPAdapterFamily	8.1.4
com.apple.driver.AppleThunderboltUSBDownAdapter	1.0.4
com.apple.driver.AppleThunderboltPCIDownAdapter	4.1.1
com.apple.driver.AppleBTM	1.0.1
com.apple.driver.AppleXsanScheme	3
com.apple.driver.AppleDCPDPTXProxy	1.0.0
com.apple.driver.DCPDPFamilyProxy	1
com.apple.nke.ppp	1.9
com.apple.driver.AppleSPU	1
com.apple.driver.AppleBSDKextStarter	3
com.apple.filesystems.hfs.encodings.kext	1
com.apple.AGXFirmwareKextG13GRTBuddy	173.22.1
com.apple.AGXFirmwareKextRTBuddy64	173.22.1
com.apple.driver.AppleDiagnosticDataAccessReadOnly	1.0.0
com.apple.driver.AppleHPM	3.4.4
com.apple.iokit.IONVMeFamily	2.1.0
com.apple.driver.AppleNANDConfigAccess	1.0.0
com.apple.driver.AppleStockholmControl	1.0.0
com.apple.driver.AppleDialogPMU	1.0.1
com.apple.driver.AppleCSEmbeddedAudio	442.26
com.apple.driver.AppleEmbeddedAudio	442.26
com.apple.iokit.AppleARMIISAudio	80.34.1
com.apple.driver.DCPAVFamilyProxy	1
com.apple.driver.AppleH11ANEInterface	4.75.0
com.apple.driver.AppleMCA2-T8103	540.10
com.apple.iokit.IOMobileGraphicsFamily-DCP	343.0.0
com.apple.driver.AppleDCP	1
com.apple.driver.AppleFirmwareKit	1
com.apple.iokit.IOMobileGraphicsFamily	343.0.0
com.apple.iokit.IOGPUFamily	21.5
com.apple.driver.AppleSPMI	1.0.1
com.apple.driver.AppleT8103TypeCPhy	1
com.apple.driver.AppleUSBXDCIARM	1.0
com.apple.driver.AppleUSBXDCI	1.0
com.apple.iokit.IOUSBDeviceFamily	2.0.0
com.apple.driver.usb.AppleUSBXHCIARM	1
com.apple.driver.usb.AppleUSBXHCI	1.2
com.apple.driver.AppleEmbeddedUSBHost	1
com.apple.driver.usb.AppleUSBHub	1.2
com.apple.driver.usb.AppleUSBHostCompositeDevice	1.2
com.apple.driver.ApplePassthroughPPM	3.0
com.apple.driver.AppleSART	1
com.apple.driver.ApplePMGR	1
com.apple.driver.watchdog	1
com.apple.driver.usb.AppleUSBHostPacketFilter	1.0
com.apple.driver.AppleDisplayCrossbar	1.0.0
com.apple.driver.AppleTypeCPhy	1
com.apple.driver.AppleThunderboltNHI	7.2.8
com.apple.driver.AppleT8103PCIeC	1
com.apple.iokit.IOThunderboltFamily	9.3.2
com.apple.driver.ApplePIODMA	1
com.apple.driver.AppleT8103PCIe	1
com.apple.driver.AppleMultiFunctionManager	1
com.apple.driver.AppleEmbeddedPCIE	1
com.apple.driver.AppleBluetoothDebugService	1
com.apple.driver.AppleBCMWLANCore	1.0.0
com.apple.iokit.IO80211FamilyV2	1200.12.2b1
com.apple.driver.IOImageLoader	1.0.0
com.apple.driver.corecapture	1.0.4
com.apple.iokit.IODisplayPortFamily	1.0.0
com.apple.driver.AppleGPIOICController	1.0.2
com.apple.driver.AppleFireStormErrorHandler	1
com.apple.driver.AppleMobileApNonce	1
com.apple.iokit.IOTimeSyncFamily	980.4
com.apple.driver.DiskImages	493.0.0
com.apple.iokit.IOGraphicsFamily	585.1
com.apple.iokit.IOBluetoothFamily	8.0.4d18
com.apple.iokit.IOBluetoothPacketLogger	8.0.4d18
com.apple.driver.FairPlayIOKit	68.7.0
com.apple.iokit.CoreAnalyticsFamily	1
com.apple.driver.AppleSSE	1.0
com.apple.driver.AppleSEPKeyStore	2
com.apple.driver.AppleUSBTDM	511.101.1
com.apple.iokit.IOUSBMassStorageDriver	184.101.1
com.apple.iokit.IOPCIFamily	2.9
com.apple.iokit.IOSCSIBlockCommandsDevice	436.100.4
com.apple.iokit.IOSCSIArchitectureModelFamily	436.100.4
com.apple.driver.AppleIPAppender	1.0
com.apple.driver.AppleFDEKeyStore	28.30
com.apple.driver.AppleEffaceableStorage	1.0
com.apple.driver.AppleCredentialManager	1.0
com.apple.driver.KernelRelayHost	1
com.apple.iokit.IOUSBHostFamily	1.2
com.apple.driver.AppleUSBHostMergeProperties	1.2
com.apple.driver.usb.AppleUSBCommon	1.0
com.apple.driver.AppleSMC	3.1.9
com.apple.driver.RTBuddy	1.0.0
com.apple.driver.AppleEmbeddedTempSensor	1.0.0
com.apple.driver.AppleARMPMU	1.0
com.apple.iokit.IOAccessoryManager	1.0.0
com.apple.driver.AppleOnboardSerial	1.0
com.apple.iokit.IOSkywalkFamily	1
com.apple.driver.mDNSOffloadUserClient	1.0.1b8
com.apple.iokit.IONetworkingFamily	3.4
com.apple.iokit.IOSerialFamily	11
com.apple.driver.AppleSEPManager	1.0.1
com.apple.driver.AppleA7IOP	1.0.2
com.apple.driver.IOSlaveProcessor	1
com.apple.driver.AppleBiometricSensor	2
com.apple.iokit.IOHIDFamily	2.0.0
com.apple.AUC	1.0
com.apple.iokit.IOAVFamily	1.0.0
com.apple.iokit.IOHDCPFamily	1.0.0
com.apple.iokit.IOCECFamily	1
com.apple.iokit.IOAudio2Family	1.0
com.apple.driver.AppleEmbeddedAudioLibs	1.17
com.apple.driver.AppleFirmwareUpdateKext	1
com.apple.driver.AppleM2ScalerCSCDriver	265.0.0
com.apple.iokit.IOSurface	290.7
com.apple.driver.IODARTFamily	1
com.apple.security.quarantine	4
com.apple.security.sandbox	300.0
com.apple.kext.AppleMatch	1.0.0d1
com.apple.driver.AppleMobileFileIntegrity	1.0.5
com.apple.kext.CoreTrust	1
com.apple.security.AppleImage4	3.0.0
com.apple.iokit.IOCryptoAcceleratorFamily	1.0.1
com.apple.driver.AppleARMPlatform	1.0.2
com.apple.iokit.IOStorageFamily	2.1
com.apple.iokit.IOSlowAdaptiveClockingFamily	1.0.0
com.apple.iokit.IOReportFamily	47
com.apple.kec.pthread	1
com.apple.kec.corecrypto	11.1
com.apple.kec.Libm	1



** Stackshot Succeeded ** Bytes Traced 42744 (Uncompressed 149952) **
</pre>

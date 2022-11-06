---
layout: post
title:  "Results of a Password Cracking Contest in My Security Class (Fall 2022)"
date:   2022-11-05 23:47:00
categories: education security
---

Each time I teach my Security class, I give a month-long lab to crack as many passwords as possible.  For this fall's contest (opened on October 4, 2022), I used two different hash types: MD5 and SHA-512.  The contest closed on November 4th at 11:59 PM PDT.  The password hashes (16 total):

<pre>
jackbear:$1$1PCUCGHC$fQc9fYcA0RHYh6hQdWru.1:1001:1001:,,,:/home/jackbear:/bin/bash
brotherbear:$1$.pDUkCfX$GxHhU/95p8K5kBFxXT.af1:1002:1002:,,,:/home/brotherbear:/bin/bash
fancybear:$1$o16/J6q0$ONpqQ65OCmSVClDVMw9IG.:1003:1003:,,,:/home/fancybear:/bin/bash
barneybear:$1$2Z2Ti73q$HAtV0MFdvtmtG1zoUiPFM0:1004:1004:,,,:/home/barneybear:/bin/bash
pandabear:$1$Pko6Qgvz$t06QJrYj3mXf3rURR6ApG1:1005:1005:,,,:/home/pandabear:/bin/bash
yogibear:$1$owv3ovwW$Wm.i.j6W9Ra6Bduy232Y.1:1006:1006:,,,:/home/yogibear:/bin/bash
papabear:$1$JN9btUA/$Kgpzv46b8qyIXsVlTn5r80:1007:1007:,,,:/home/papabear:/bin/bash
grizzlybear:$1$dg7RXQr2$vnDsFAeTQWpX8IjlRwRwn/:1008:1008:,,,:/home/grizzlybear:/bin/bashsisterbear:$6$Lti1Rz7aG5Gcxu0Y$fk7lAYOj5.20YOP09yYOHj0OLlTmyuzUleQVy4hPBpq5Z6oICK2UGUbP5ivqTIKqJrDLuAygY8qBbcgj.WMfn/:1009:1009:,,,:/home/sisterbear:/bin/bash
teddybear:$6$SbzNgpi0kwc6H5Ef$UiJgTJlbPwwdlXLMQfzk.9bKVQoZn2s2smtk3AaquFSi.NvP.pzYYANMI01MAYlqkhJn5Kz641TcshG.MKInJ1:1010:1010:,,,:/home/teddybear:/bin/bash
polarbear:$6$WSJr4aFmq/9ixL8i$weRpnHG7aJQCuAFamztfuuLC8nP2jwtskHG9lQkKiKV1WRBtefTWTRUiENCdkAQliu9hSD.5omg1XmQ8S9/sI0:1011:1011:,,,:/home/polarbear:/bin/bash
bluebear:$6$BpzsEOCQDs82hNgI$GYsF5y2JBuMgLwLRUP05xfcT6hKEz0KtPbUdWLjLR5P7SSXovsd7WWytwA9wfwIdpa3c5C0ddsHTl/LoULA6T/:1012:1012:,,,:/home/bluebear:/bin/bash
blackbear:$6$RDLDAwDXE63Dl9ZM$/FwOtEyYXFz3x4yUCMLdznUSUS9H4vSCMXM5VmSKW6xQFc/YQTm.t78pZ6Lf38fejGjNGB/ZlbUZqe8c0U9/K0:1013:1013:,,,:/home/blackbear:/bin/bash
mamabear:$6$x698r5uHaGfnqjwh$9qvV9kIUDuLbKWaXTxqXjZcUYZ/SyFQiQcKm/h7P2kVmQplzUIqeKLV8ekfFexfP4/cfOOMcfRX2Kgr1e/rvi.:1014:1014:,,,:/home/mamabear:/bin/bash
carebear:$6$sK1HOgwqf0BAaXkM$80Ui4xUs5MMrmPelNFXyXTtdgopPt1dHPAiv/W3FTmk9BqU1558haEWo5Zc5yjNWmdyNS4zTPsEOyGsyzNo0A/:1015:1015:,,,:/home/carebear:/bin/bash
cozybear:$6$qBsWj2EnnzAcrQDa$04O8mb7L5k2L0mpei0j4E1s/ifqoHX4nHybR/1m4QiG/usO8h18vWBE4fA7gFIZcnTWeLXPUJmLPOibvfdd.I1:1016:1016:,,,:/home/cozybear:/bin/bash
</pre>

113 submissions across two classes.  The answers:
* (MD5) jackbear:j38ifUbn => 93 students cracked this
* (MD5) brotherbear:secret => 110 students cracked this
* (MD5) fancybear:YrbDOrNy => 0 student cracked this
* (MD5) barneybear:i6UmTIUW => 0 student cracked this
* (MD5) pandabear:0248jrd => 67 students cracked this
* (MD5) yogibear:patchett => 108 students cracked this
* (MD5) papabear:gargarismo => 104 students cracked this
* (MD5) grizzlybear:stagionato => 84 students cracked this
* (SHA-512) sisterbear:159753 => 69 students cracked this
* (SHA-512) teddybear:pu => 76 students cracked this
* (SHA-512) polarbear:swZUUAGe => 0 student cracked this
* (SHA-512) bluebear:b**Q~9D8+#qa => 0 student cracked this
* (SHA-512) blackbear:399253 => 17 students cracked this
* (SHA-512) mamabear:Nite => 81 students cracked this
* (SHA-512) carebear:p12070m414 => 40 students cracked this
* (SHA-512) cozybear:endophragmiella => 35 students cracked this

The passwords for fancybear, barneybear, polarbear, bluebear, and blackbear were randomly generated; all other passwords were taken from wordlists.

To earn all 10 / 10 points for the lab, students had to crack 7 or more passwords.  The final distribution:

<pre>
12 (x5)
11 (x11)
10 (x11)
9 (x13)
8 (x21)
7 (x28)
6 (x11)
5 (x8)
4 (x2)
3 (x2)
2 (x2)
</pre>

The winner's methodology and haul:

<pre>
I used john the ripper for my password cracking and used wordlists
from the SecLists github repository.

The files that turned out results were the following for md5:
darkweb2017-top10000 (2), xato-net-10-million-passwords-1000000 (1),
mssql-passwords-nansh0u-guardicore (1), darkc0de.txt (2),
xato-net-10-million-passwords.txt(1)

The files that turned out results were the following for sha512:
mssql-passwords-nansh0u-guardicore (1),
xato-net-10-million-passwords-1000000 (1),
dutch_common_wordlist.txt(1). I tried using the kaonashi(1) wordlist
after having exhausted the SecLists and the subfolders of that
repo. Used the following wordlist Top2Billion-probable-v2(1). I ran
the top2billion one again (had aborted it due to taking too long the
first time). When I ran it with openCl thought not with forking as I
could not get that to work on my laptop (john
--wordlist=C:\Users\[redacted]\Downloads\ProbWL-v2-Real-Passwords-7z\Top2Billion-probable-v2.txt
C:\Users\[redacted]\Downloads\crackme-fall2022sha512.txt
--format=opencl --session=2_bil), I got an additional password.

From md5:
jackbear: j38ifUbn
brotherbear: secret
Yogibear:patchett
papabear: gargarismo
grizzlybear: stagionato
Pandabear: 0248jrd

From sha512:
sistearbear: 159753
teddybear: pu
mamabear: Nite
Blackbear: 399253
Cozybear: endophragmiella
Carebear: p12070m414
</pre>

<pre>
I also finally got OpenCL and forking working, so my hardware is
making the process much faster than normal:

Command: john --wordlist=F:\Desktop2\wordlists\[WORDLIST].txt
C:\Users\[redacted]\Desktop\crackme-fall2022-2.txt
--format=sha512crypt-opencl -fork=8

GPU: EVGA FTW3 ULTRA GAMING GeForce RTX 3070 8 GB Video Card
(Overclocked using MSI Afterburner)

CPU:AMD Ryzen 5 5600X 3.7 GHz 6-Core Processor (running at 4.62 GHz)

RAM: TEAMGROUP T-Force Vulcan Z 32 GB (2 x 16 GB) DDR4-3200 CL16
Memory

Using John The Ripper and the xato-net-10-million-passwords wordlist,
I cracked the password below:

https://github.com/danielmiessler/SecLists/tree/master/Passwords/xato-net-10-million-passwords.txt

MD5:
brotherbear : secret
yogibear : patchett 
pandabear : 0248jrd

SHA-512:
sisterbear : 159753
mamabear : Nite

Using John The Ripper overnight (typing john only, incremental ASCI),
I cracked the passwords below:

SHA-512:
teddybear: pu
blackbear : 399253

Using John The Ripper and the md5decryptor-uk.txt wordlist, I cracked
the password below:

https://github.com/danielmiessler/SecLists/blob/master/Passwords/Leaked-Databases/md5decryptor-uk.txt

MD5:
jackbear : j38ifUbn

Using John The Ripper and the dutch_common_wordlist.txt wordlist, I
cracked the password below:

https://github.com/danielmiessler/SecLists/blob/master/Passwords/dutch_common_wordlist.txt

MD5:
grizzlybear : stagionato

Using John The Ripper and the rockyou.txt wordlist, I cracked the
password below:

https://github.com/danielmiessler/SecLists/blob/master/Passwords/Leaked-Databases/rockyou.txt.tar.gz.

MD5:
papabear : gargarismo

Using John The Ripper and the Top2Billion-probable-v2.txt wordlist, I
cracked the password below:

https://github.com/berzerk0/Probable-Wordlists/tree/master/Real-Passwords

SHA-512:

cozybear: endophragmiella
carebear: p12070m414
</pre>

<pre>
Passwords were found using the following methods:
user           - wordlist/methodology

jackbear       - darkweb2017-top10000.txt
brotherbear    - xato-net-10-million-passwords.txt
fancybear      -
barneybear     - 
pandabear      - xato-net-10-million-passwords.txt
yogibear       - xato-net-10-million-passwords.txt
papabear       - darkc0de.txt
grizzlybear    - darkc0de.txt

bashsisterbear - On all 6-digit numbers
teddybear      - darkc0de.txt
polarbear      -
bluebear       -
blackbear      - On all 6-digit numbers
mamabear       - xato-net-10-million-passwords.txt
carebear       - darkc0de.txt
cozybear       - darkc0de.txt
</pre>

<pre>
brotherbear:secret
yogibear:patchett
pandabear:0248jrd
papabear:gargarismo
jackbear:j38ifUbn
grizzlybear:stagionato
sisterbear:159753
teddybear:pu
blackbear:399253
cozybear:endophragmiella
mamabear:Nite
carebear:p12070m414

Right away I switched from JohnTheRipper to Hashcat just because after
searching around some it seemed Hashcat was very good with multiple
GPUs (though I did not end up using that). I first decided to run a
bruteforce algorithm for some time (about 1 day) just to see if any
lucky shorter passwords would popup that likely would not be on a word
list, and only 'secret' came out of this. Note, I did only use
bruteforce on $1 (MD5) because it seemed the computation speed was
much quicker (I am not too sure why this is). Then I switched my
strategy to word lists. I used 3 different ones, one from something
like 10mil common passwords
(https://github.com/danielmiessler/SecLists/blob/master/Passwords/Common-Credentials/10-million-password-list-top-1000000.txt),
and then larger ones from github: https://github.com/piotrcki/wordlist
, though I could only manage to download half of that one, and then
also one from: https://weakpass.com/wordlist (the Hashes.org one). I
ran the wordlist check for both hash types for each wordlist and
recovered 11 more passwords. If I was more on top of things earlier in
the semester and I wasn't away for 2 weeks, I definitely would have
liked to used Tufts High Performance cloud or AWS to do more brute
force cracking and larger word lists. I also made a custom word list
from all previous years of this contest, but didn't find any repeats
(which was somewhat surprising because I saw passwords like L!verpool
be used a lot in previous years.</pre>

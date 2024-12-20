---
layout: post
title:  "Results of a Password Cracking Contest in My Security Class (Spring 2020)"
date:   2020-04-11 12:00:00
categories: education security
---

Each time I teach my Security class, I give a month-long lab to crack as many passwords as possible.  For this spring's contest [(opened on February 26th 2020)](https://twitter.com/0xmchow/status/1232773806671810561), I used three different hash types: NTLM, MD5, and SHA-512.  The contest was extended to Friday, April 10th at 11:59 PM PDT due to COVID-19.  The password hashes (30 total):

<pre>
shanemcmahon:$1$AFiagxbY$m1G06dn3f67MJ.lCbK2wD1:1003:1003:,,,:/home/shanemcmahon:/bin/bash
undertaker:$1$N474C.43$0RFoyE1h.7PrLN.wtp8vO0:1004:1004:,,,:/home/undertaker:/bin/bash
niajax:$1$7cIw2LC4$1JTETzC30ZZQV69/cPaCB.:1005:1005:,,,:/home/niajax:/bin/bash
beckylynch:$1$H7R1hQX9$to11wDX25cja/iJkOwJdc.:1006:1006:,,,:/home/beckylynch:/bin/bash
mickiejames:$1$Fr.303V4$kyiKpt3U..MO7DEqpBE/p/:1007:1007:,,,:/home/mickiejames:/bin/bash
mandyrose:$1$WFCgYzf4$7YwDknm0/nNpaye5P2r/X1:1008:1008:,,,:/home/mandyrose:/bin/bash
bobbyroode:$1$Y.ZEuYwe$qrQMM5VOYq412F5yBw21y/:1009:1009:,,,:/home/bobbyroode:/bin/bash
carmella:$1$3qVt4oZn$J2GV/na37Z6lrIo9n.h67.:1010:1010:,,,:/home/carmella:/bin/bash
ajstyles:$1$KZkhz.SH$gUWTgvnYEIk73Dw9mPv5c/:1011:1011:,,,:/home/ajstyles:/bin/bash
sethrollins:$1$Hzmk0euJ$l5cFvbqvghsYW4HlX1FQb1:1012:1012:,,,:/home/sethrollins:/bin/bash
rubyriott:$1$LdAMA1T1$GxvSWUmPMEVsBkCmrXhdm1:1013:1013:,,,:/home/rubyriott:/bin/bash
charlotteflair:$1$0z1S59/r$OoPDVmkh30RVG5.DjFHA80:1014:1014:,,,:/home/charlotteflair:/bin/bash
johncena:$6$l0jjDLDz$pPTgmg6WtIr8jD.Jfrcujg.A9m83MCQeBBYPeUamB/rm7TsSoT2U28m5BzQBWiGpUOcvlRZaJVQr59hPvlgu3/:1001:1003:,,,:/home/johncena:/bin/bash
alexabliss:$6$Hb/2T/hJ$lvJV5kB9XkWqQ3z8pzxAHQgdDgzOVXvlco1fFjvjpbPLISx.tvFNuc6LnckRxG6PZn494/LP2ZVejLtMEYMql/:1002:1004:,,,:/home/alexabliss:/bin/bash
dolphziggler:$6$EybUhKYR$ehSUx9uYtGfMtfC3wLKVPVhIQsC6s9w6x.snv3cw/VJw6TT2mbBjrsNjieh8BX358OF2Hoo/PXEYusASZ0.W/1:1003:1005:,,,:/home/dolphziggler:/bin/bash
sonyadeville:$6$3I.Z8/wm$Fvc8PmNPk5N9b55COAGh8xG0Kta47ou49pr6dgFjjgjhzMiaEZjYNcpGFJodJPf8P6C1FbBO5VqG5m1Y7e7Pd1:1004:1006:,,,:/home/sonyadeville:/bin/bash
bayley:$6$0g39uU8d$iOSlaqFmuIKaA9FcaYYjcFfHMgomZ8cZNXgRsFTfEeq4.C9fTpBmeT8wWXlXASAAjiIn/24MOMfWmh6uKJ1UO1:1005:1007:,,,:/home/bayley:/bin/bash
kevinowens:$6$rF3VJTTr$deqgJRka9ecUA2CWdtDfmbLij3v7Lzqk0jhZdyfeFsenX/MWM5AlntNCvxUTmIhyQfErMYH/lWNbcyStytldS/:1006:1008:,,,:/home/kevinowens:/bin/bash
randyorton:$6$lux2EvzK$NfF5XZNgnrfmqyVbCRhWefZ54/NN4eeL5lkFdARkO0jUzUPrgSrNehiaK9z1L6FXRPMDcZYk96U0na.KXDt/3/:1007:1009:,,,:/home/randyorton:/bin/bash
embermoon:$6$2PF7yNQO$jD4/NCYsMIa.hGXkzCON6v6buM7iyKSxCccQOe6i0fumvjV3Qw0mx8iW0lr83Es9eoo8RnCu/zdacgSOyfUm1/:1008:1010:,,,:/home/embermoon:/bin/bash
romanreigns:$6$8qscBeH.$/oSQkqSgSrW.A9.5ZSe5cg.qEknAYnEr1ABkwcO1UPJeO7/vZjb0DcmNhF9qF7byA6W2KRfz13lM6JkF0Orbh.:1009:1011:,,,:/home/romanreigns:/bin/bash
rondarousey:$6$W8LCB1jM$Djd67HW9y7v2D9K91bdFqTMZ5k.MKjKra/4Yx9nQMQARzi1TwBDktqJgUUdKB8MGFpfyyTrEz5fX8XcNQbYnm.:1010:1012:,,,:/home/rondarousey:/bin/bash
nikkicross:$6$NleiBGDx$5aXNOodRpcojj8orCBzexk4yQCX1KL7eJlp15mO6.UswcLvZ1QCe.ffDP24.XphUbTUCAGrE9dQQ/SRpRujod1:1011:1013:,,,:/home/nikkicross:/bin/bash
brocklesnar:$6$3OZEIxVz$yWqyCfo9Ls2Q1at44xmPYrClHVbKcHcQMaBTL6uXS3HGM0TVTN2wZdGbox0L.fh7mm2kb32dZTLEabBHTzSfm.:1012:1014:,,,:/home/brocklesnar:/bin/bash
braywyatt:1003:aad3b435b51404eeaad3b435b51404ee:df7ff4e542cd1589ef847f871d70dfdd:::
danabrooke:1001:aad3b435b51404eeaad3b435b51404ee:fdc72cd893926606ddd5522a6b38d7d8:::
finnbalor:1005:aad3b435b51404eeaad3b435b51404ee:bd464fd6f8d57444e94492a8a87c3d58:::
kofikingston:1004:aad3b435b51404eeaad3b435b51404ee:a3fdfab6f9eceb9d3d49af0826a68150:::
sashabanks:1006:aad3b435b51404eeaad3b435b51404ee:98c1db08e4ac2d477f948850feafb54b:::
themiz:1002:aad3b435b51404eeaad3b435b51404ee:2e26315c1c96c9e225e25cf440619fa6:::
</pre>

64 total submissions.  The answers:

* (MD5) shanemcmahon:voluptuous8887 => 29 students cracked this
* (MD5) undertaker:un1verse => 52 students cracked this
* (MD5) niajax:Abovyan => 37 students cracked this
* (MD5) beckylynch:MAHR => 32 students cracked this
* (MD5) mickiejames:gwyq => 25 students cracked this
* (MD5) mandyrose:v2zcyx => 13 students cracked this
* (MD5) bobbyroode:kY32cWmn => 0 student cracked this
* (MD5) charlotteflair:a1K#le => 2 students cracked this
* (MD5) carmella:abc123 => 63 students cracked this
* (MD5) ajstyles:eviluno => 14 students cracked this
* (MD5) sethrollins:moxley => 53 students cracked this
* (MD5) rubyriott:+_X1R*i,Fz"f => 0 student cracked this
* (SHA-512) johncena:attingeste => 13 students cracked this
* (SHA-512) alexabliss:prohnan => 10 student cracked this
* (SHA-512) dolphziggler:lend => 34 students cracked this
* (SHA-512) sonyadeville:rajeesh => 16 students cracked this
* (SHA-512) bayley:L!verpool => 5 students cracked this
* (SHA-512) kevinowens:827916 => 7 students cracked this
* (SHA-512) randyorton:q6479b => 3 students cracked this
* (SHA-512) embermoon:siIVuTVz => 0 student cracked this
* (SHA-512) romanreigns:3>9(&[ => 0 student cracked this
* (SHA-512) rondarousey:2n76+@4=nN:e => 0 student cracked this
* (SHA-512) nikkicross:tgZRki#{",hz => 0 student cracked this
* (SHA-512) brocklesnar:love14 => 43 students cracked this
* (NTLM) danabrooke:florida1 => 47 students cracked this
* (NTLM) themiz:lamata => 50 student cracked this
* (NTLM) braywyatt:pi1f312in619 => 29 students cracked this
* (NTLM) kofikingston:SPrsoe => 29 students cracked this
* (NTLM) finnbalor:9(Z;5= => 15 students cracked this
* (NTLM) sashabanks:-HP0-g7%85 => 0 student cracked this

To earn all 10 / 10 points for the lab, students had to crack 8 or 9 passwords; 10.5 points were awarded to anyone who cracked 10 or more passwords.  The final distribution:

<pre>
22 (1 total)
21 21 (2 total)
18 (1 total)
17 (1 total)
16 (1 total)
15 (1 total)
14 14 14 (3 total)
13 13 13 (3 total)
12 12 12 (3 total)
11 11 11 11 11 (5 total)
10 10 10 10 10 (5 total)
09 09 09 09 09 09 09 09 (8 total)
08 08 08 08 08 08 08 08 08 08 08 08 08 08 08 (15 total)
07 07 07 07 07 07 (6 total)
06 06 (2 total)
05 05 05 (3 total)
03 03 (2 total)
01 01 (2 total)
</pre>

The winner cracked 22 of the 30 passwords.

Winner 1's haul and methodology:

>carmella:abc123
>undertaker:un1verse
>shanemcmahon:voluptuous8887
>mickiejames:gwyq
>brocklesnar:love14
>dolphziggler:lend
>danabrooke:florida1
>themiz:lamata
>braywyatt:pi1f312in619
>niajax:Abovyan
>beckylynch:MAHR
>sethrollins:moxley
>kofikingston:SPrsoe
>kevinowens:827916
>finnbalor:9(Z;5=
>ajstyles:eviluno
>johncena:attingeste
>bayley:L!verpool
>alexabliss:prohnan
>sonyadeville:rajeesh
>mandyrose:v2zcyx
>randyorton:q6479b
>I learned Hashcat rather than JTR, since it has GPU support out of the box. I'm running a lot of masks and found a few big word lists. A couple of the passwords were found by a Google Search too.

Strategies used by students who cracked 8 or more passwords:

>I used John the Ripper to crack the following passwords, using different flags to extract specific passwords.
>carmella:abc123 (no flags)
>danabrooke:florida1 (--format=NT)
>themiz:lamata (--format=NT)
>kofikingston:SPrsoe (--format=NT)
>niajax:Abovyan (--wordlist=A.txt) - using a wordlist containing many words beginning with A
>beckylynch:MAHR (--wordlist=M.txt) - using a wordlist containing many words beginning with M
>undertaker:un1verse (--wordlist=U.txt) - using a wordlist containing many words beginning with U
>sethrollins:moxley (--wordlist=M.txt) - using a wordlist containing many words beginning with M

>I started out using John the Ripper on a VM. VMs don't support GPU acceleration, so I installed Ubuntu on a USB drive so I could boot from that and run the GPU natively. I build JtR Jumbo version which supports GPUs and ran that. I eventually tried using hashcat, which I then realized had an existing windows binary, so I was able to run that in the background instead of tying up the machine running the USB Ubuntu like I had been.  With both programs, I tried a few different wordlists such as rockyou.txt and realuniq.lst. The latter ended up being too big with too many non-human readable words which was an inefficient use of the search time. I tried different combinations of rules that substituted or added characters into/onto the wordlist words. I tried some brute force searching as well, which found a couple of the shorter passwords, but grew quickly infeasible for longer ones. I also tried looking up the NTLM passwords in a rainbow table (since they have no salt) which found three (two of which had already been found).

>I separated out the first 12 passwords with version $1$ in their own file and ran hashcat with 500 to represent their md5crypt type. The first 2 found were moxley and Abovyan from bt4-passwords.txt in the SecList. I continued through with the entire SecLists folder and then brute-forced for 4 characters. I started a 5 character brute force but stopped since it would take 18 days and my charger was melting:

>hashcat -m 500 -a 0 --username crack1.txt SecLists/Passwords/      //Wordlist
>hashcat -m 500 -a 3 --username crack1.txt ?a?a?a?a (3 hours 19 minutes)    //Bruteforce
>I then did the same thing with sha512 for the next 12 passwords marked as $6$. After finding 5 with the SecLists wordlist, I brute-forced up to 4 characters, then stopped.
>hashcat -m 1800 -a 0 --username crack2.txt SecLists/Passwords/
>After, I ran the NTLM passwords on hashcat (only focusing on the last part of the hash, the other info like 1002:middlehash represents window system information and a weak hash that didn’t matter) with the wordlist and brute force. I found 3 on the wordlist and brute-forced 1
>hashcat -m 1000 -a 0 --username crack3.txt SecLists/Passwords/
>hashcat -m 1000 -a 3 --username crack3.txt ?a?a?a?a?a  (2 min)

>Ran John the Ripper and Hashcat to do dictionary attacks on the white-hole server. Used the crackstation human only passwords found online. Used the default --rules option for John the Ripper for password mutation. For the NT/LM hashes, brute force attack is used with Hashcat after initial dictionary attack, up to 6 or 7 characters long. 

>I used the following wordlists from https://github.com/danielmiessler/SecLists/blob/master:
>- 10-million-password-list-top-1000000.txt
>- alleged-gmail-passwords.txt
>- darkc0de.txt
>- xato-net-10-million-passwords.txt
>- rockyou.txt
>Oh and I for the SHA512 hashes that I cracked (dolphziggler:lend brocklesnar:love14), I specifically had to use JTR Jumbo. All of the hashes I cracked used JTR. I tried to use hashcat but could that spiraled down into dependency hell.

>1. carmella:abc123 - cracked by  running john crackme-spring2020.txt
>2. danabrooke:florida1 - used john with --format=NT
>3. themiz:lamata - used john with --format=NT
>4. kofikingston:SPrsoe - used john with --format=NT
>5. niajax: Abovyan - used ./john with new wordlist from Crackdown2016 from kennyn510 github
>6. dolphziggler: lend - cracked using wordlist cain.txt from cain and able tool
>7. mickiejames:gwyq - cracked using Neo2016.txt wordlist from kennyn510 github
>8. beckylynch:MAHR - cracked using Neo2016.txt wordlist from kennyn510 github
>9. johncena:attingeste - cracked usingInsider2016.txt wordlist from kennyn510 github
>10. undertaker:un1verse - cracked using wordlist
>11. sethrollins:moxley - cracked using wordlist

>carmella: abc123 (JohnTheRipper using rockyou.txt)
>sethrollins: moxley (JohnTheRipper using rockyou.txt)
>undertaker: un1verse (JohnTheRipper using rockyou.txt)
>brocklesnar: love14 (JohnTheRipper using rockyou.txt)
>kofikingston : SPrsoe (isolated the hash from crackme.txt and inputted to onlinehashcrack.com)
>braywyatt : pi1f312in619 (isolated the hash from crackme.txt and inputted to crackstation.net)
>danabrooke : florida1 (isolated the hash from crackme.txt and inputted to crackstation.net)
>themiz: lamata (isolated the hash from crackme.txt and inputted to crackstation.net)
>finnbalor : 9(Z;5= (isolated the hash from crackme.txt and inputted to onlinehashcrack.com)

>I first split the passwords into three different files: crackme-1.txt, for all passwords beginning with $1$ (the MD5 hash); crackme-6.txt, for all passwords beginning with $6$ (SHA-512); and crackme-etc.txt, for all passwords not in the above two files. I ran John the Ripper on crackme-1.txt without specifying a wordlist, and got one password. I then downloaded the xato-net-10-million-passwords file and used that as the wordlist, netting three more passwords. I also used wordlists openwall.net-all and darkc0de to get two more passwords from crackme-1.txt. I then tried running John the Ripper with the xato-net-10-million-passwords file on crackme-6.txt (which took a couple of hours to run). I uncovered two passwords this way. I found three more passwords for crackme-6.txt using the wordlists darkc0de and openwall.net-all.

>undertaker:un1verse JtR with wordlist rockyou.txt (found on the internet) ./john ../hashes/md5crypt.txt --wordlist=../wordlists/rockyou.txt
>carmella:abc123 JtR solo ./john ../hashes/crackme.txt
>sethrollins:moxley JtR with wordlist rockyou.txt (found on the internet) ./john ../hashes/md5crypt.txt --wordlist=../wordlists/rockyou.txt
>niajax:Abovyan Hashcat hashcat -m 500 -a 0 -o cracked.txt -O hashes/md5crypt.txt wordlists/Top109Million-probable-v2.txt
>beckylynch:MAHR hashcat -m 500 -a 0 -o cracked.txt -O hashes/md5crypt.txt wordlists/Top109Million-probable-v2.txt
>mickiejames:gwyq hashcat -m 500 -a 0 -o cracked.txt -O hashes/md5crypt.txt wordlists/Top109Million-probable-v2.txt
>johncena:attingeste hashcat -m 1800 -a 0 -o cracked.txt -O hashes/sha512.txt wordlists/Top109Million-probable-v2.txt
>dolphziggler:lend hashcat -m 1800 -a 0 -o cracked.txt -O hashes/sha512.txt wordlists/Top109Million-probable-v2.txt
>sonyadeville:rajeesh hashcat -m 1800 -a 0 -o cracked.txt -O hashes/sha512.txt wordlists/Top109Million-probable-v2.txt

>carmella:abc123
>sethrollins:moxley
>Mandyrose:v2zcyx
>nijax:Abovyan
>undertaker:un1verse
>beckylynch:MAHR
>themiz:lamata
>danabrooke:florida1
>brocklesnar:love14
>braywyatt:pi1f312in619
>I used hashcat on my personal desktop computer to crack these passwords.
>I didn't want to brute force for a month and increase my power bill so I think I only brute forced one or two of the passwords. I may have lost one of the ones I brute forced, as I originally was playing around with jtr on kali and got one/two. For the rest/vast majority of these passwords I cracked them using two lists with hashcat: the rockyou text file and a 15 GB list I found called realuniq.lst. I believe that it crack station released it. The biggest trouble I had was on figuring out what the heck the NTLM hashes were and formatting them so that hashcat could crack them. The length of time spent cracking the SHA512 hashes was also quite prohibitive. I think I only ran them through rockyou and it still took around 8 hours. Everything other dictionary attack took no longer than an hour on my machine.
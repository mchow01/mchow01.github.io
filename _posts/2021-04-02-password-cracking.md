---
layout: post
title:  "Results of a Password Cracking Contest in My Security Class (Spring 2021)"
date:   2021-04-02 15:00:00
categories: education security
---

Each time I teach my Security class, I give a month-long lab to crack as many passwords as possible.  For this spring's contest (opened on February 28, 2021), I used three different hash types: NTLM, MD5, and SHA-512.  The contest closed on April 1st at 11:59 PM PDT.  The password hashes (21 total):

<pre>
barneybear:$1$lSoAz9hz$BNDSTIYBxW/7kqFkRKvDd.:1003:1003:,,,:/home/barneybear:/bin/bash
cozybear:$1$VK9GSLgF$0zZ44GqFzDEYZQXHImf6p0:1004:1004:,,,:/home/cozybear:/bin/bash
grizzlybear:$1$5vwH0Adb$tKhLKzhfgCnfgWIT0RSuv/:1005:1005:,,,:/home/grizzlybear:/bin/bash
cindybear:$1$2Zl1rGcW$9Yz.hu4ElS0VQu9K0stHJ0:1006:1006:,,,:/home/cindybear:/bin/bash
fancybear:$1$1RMDflNY$nq3PjZvgHJxqy4a6sNpZr0:1007:1007:,,,:/home/fancybear:/bin/bash
chicagobear:$1$aZkD64xd$oPM0PGod1rpv1N7WiGU4t1:1008:1008:,,,:/home/chicagobear:/bin/bash
jackbear:$1$bVXgQZTi$jK0baQnYNleMbGGJkS30d/:1009:1009:,,,:/home/jackbear:/bin/bash
teddybear:$1$AULcNMN/$jkM80ir/Gkn2UjJ84Fr6x.:1010:1010:,,,:/home/teddybear:/bin/bash
polarbear:$6$DmVR.hUbuHEWJgRt$bkEDA3TL8PhLYybWb4umi7uBclM6QZEaspbFds.AzOuVficIOY5oSf/p6womVUrnGyNLpauSLikzFfvRifTa8/:1001:1002:,,,:/home/polarbear:/bin/bash
bluebear:$6$CWJR//qxRYQZGaOT$kVvmad7B9T0UXs968mQaOhrqxhpejjex6FnsY5v0Ncir9bG754K3kFJdn2DHArDWUow6teQVgu/5QMy2fvkZ9.:1002:1003:,,,:/home/bluebear:/bin/bash
papabear:$6$PdFRRpBiB26cR6kr$XzDh2vD1ZIJGKOIIdLn8DZ6l3SsSeUMfqpMFhIbRxNbNmzNiBzosYQPMPAQc6efWEMi4qHAPhLAIp3/5ichCO0:1003:1004:,,,:/home/papabear:/bin/bash
bigbear:$6$1rULfH8xOo04.Ar8$zJqWQKyacOTLEHufSAuDY06quBpnoAoG4jD/SjOGNu6vOWGAtD/C9wrRNUMVI4sEt5a0I5KFblNjMWXYm1noD.:1004:1005:,,,:/home/bigbear:/bin/bash
blackbear:$6$rMoDHrl1IzUy1x.U$fh7XEQBiRBZPdWEnlY5BQ7swugLst1grYrJ65VGrZrS6usqKv9YnHlIcJR0i1EfLGeaHGHHr/iHyuWvVFZPen/:1005:1006:,,,:/home/blackbear:/bin/bash
pandabear:$6$sAG2Xcr.7/2EQeYP$mSwNJGjXZ8qUBhNRMpeKTfaD1jxjSPvJmVt6ITBFJJdQToWerV.WXUaTDkjQ7Lps.rvMWkguXBpT4Jo.syyJB/:1006:1007:,,,:/home/pandabear:/bin/bash
brotherbear:$6$4t060Ebc0QjCQ6kf$Xec623KMWliZqw65Yy7iimDuQKIPtpKItiy7DisXcCrzUTWRqmhGcakwoMxHliJeYVNw92YBV7TvMNvxKHxYI0:1007:1008:,,,:/home/brotherbear:/bin/bash
carebear:$6$JgRnb1cKyE2ofTh1$.YHTGCTKCvnDh6go3hz.f7fcmSYJwYPzHx0oUhRHbmloIJKYX6c3EjIxz8vAh4a1H0ZvqBLF1nwxc0k7Uy6KY0:1008:1009:,,,:/home/carebear:/bin/bash
booboobear:1000:aad3b435b51404eeaad3b435b51404ee:e19ccf75ee54e06b06a5907af13cef42:::
fozziebear:1002:aad3b435b51404eeaad3b435b51404ee:d3415aeccf106b58ec2a32e5ca18e3df:::
mamabear:1001:aad3b435b51404eeaad3b435b51404ee:8ade9f80fe667986b8cc9f7c38993e05:::
sisterbear:1004:aad3b435b51404eeaad3b435b51404ee:81fdc1b401c62f00bb1a26aa323a1c0e:::
yogibear:1003:aad3b435b51404eeaad3b435b51404ee:d32ce92a70a4273c8d9dde0918f4d9b3:::
</pre>

90 submissions across two classes.  The answers:
* (MD5) barneybear:stonks => 67 students cracked this
* (MD5) cozybear:HaydenYourSisterIsMadAtYou => 0 student cracked this
* (MD5) grizzlybear:t05luo => 76 students cracked this
* (MD5) cindybear:craftpw => 83 students cracked this
* (MD5) fancybear:gwerty => 82 students cracked this
* (MD5) chicagobear:cmw880 => 36 students cracked this
* (MD5) jackbear:OHSXOui1 => 0 student cracked this
* (MD5) teddybear:5DYLZCLa46AT => 0 student cracked this
* (SHA512) polarbear:solarwinds123 => 5 students cracked this
* (SHA512) bluebear:L!verpool => 10 students cracked this
* (SHA512) papabear:prodigally => 41 students cracked this
* (SHA512) bigbear:office => 80 students cracked this
* (SHA512) blackbear:mvzbcv => 3 students cracked this
* (SHA512) pandabear:v2YkCHZX => 0 student cracked this
* (SHA512) brotherbear:4KVuJbOLhqkL => 0 student cracked this
* (SHA512) carebear:BQMYLTWMYA => 0 student cracked this
* (NTLM) mamabear:23742374 => 67 students cracked this
* (NTLM) fozziebear:iseesun => 65 students cracked this
* (NTLM) yogibear:00399032 => 47 students cracked this
* (NTLM) sisterbear:vjnxly => 39 students cracked this
* (NTLM) booboo:P@ssw0rd => 61 students cracked this

To earn all 10 / 10 points for the lab, students had to crack 8 or more passwords.  The final distribution:

<pre>
14 (x3)
13 (x4)
12 (x4)
11 (X6)
10 (x19)
9 (x10)
8 (x17)
7 (x4)
6 (x6)
5 (x8)
4 (x8)
2 (x1)
</pre>

There was a three-way tie for first place.  The winners cracked 14 of the 21 passwords. The winners' haul and strategy:

<pre>I ran the file containing the hashes through JtR which told me
what type each group was. I then put each group into its own file and
started running Hashcat on an RTX 2060 and an RX 580 using brute force
on the default charset, no wordlist or rules. This got me the NTLM's
and 4 of the md5's in about a day. I then downloaded the "rockyou.txt"
wordlist of common passwords and used it with the hashcat default
"best64.rule" rules file which got me another md5 and one of the
sha512's. This iteration didn't yield anything further. I found a
couple more huge wordlists. The entire english language got me 2 more
sha512's. A 15Gb compilation of all major hacks and leaks is what is
currently running.</pre>

<pre>Most of these I cracked using hashcat with various wordlists. I
used rockyou, some from Seclists like the xato wordlists and darkc0de,
as well as wordlists from crackstation (realuniq.lst), and a couple
from a site that had wordlists from hashes.org. I have a bunch more
wordlists that I used but most didn't yield results. Most I just let
run for hours, particularly the sha512crypt hashes of course, as well
as some of the longer lists for the MD5crypt hashes. The ntlm ones ran
pretty quickly as expected. The rest (maybe 2 or 3 including the last
ntlm) I cracked using john the ripper using the --incremental flag. I
also enabled the dive rule for some of the cracks although I can't
remember if that yielded any results (yet). I'm trying to get as many
of the simpler ones out as I can before I let the larger ones run for
a couple days.</pre>

<pre>Methodology has been using my gaming rig with hashcat and john
for both brute force masking and wordlists, then leaving it running
for hours / days to do everything. Ryzen 5 2600x and RX580 8GB. Word
lists include SecList, rockyou.txt, and various ones from
https://weakpass.com/lists</pre>

Methodologies from those who cracked 8 or more passwords:

<pre>I used a wordlist that I found here: https://weakpass.com/lists
for the majority of the MD5 and SHA512 passwords. I first started with
the Daniel Miessler xato 10 million list, but then later switched to
the longer list. All of the cracking was done with hashcat. For the
NTLM hashes, I followed a guide from here to set up a brute force
attack:
https://cyberloginit.com/2017/12/26/hashcat-ntlm-brute-force.html</pre>

<pre>I combined and deduplicated all of the password lists in SecLists
and used a dictionary attack in hashcat for the md5 and sha512 hashes,
respectively.  Command: hashcat -a 0 -m 500 lab5/md5.txt
lab5/combined.txt hashcat -a 0 -m 1800 lab5/md5.txt lab5/combined.txt
This cracked 3/8 md5 hashes and 1 sha512 hash. I used hashcat to crack
3 of the ntlm hashes. I used a mask attack to crack those.</pre>

<pre>
grizzlybear:t05luo             - MD5 JTR 10-million-password-list-top-1000000.txt
barneybear:stonks              - MD5 JTR Incremental Brute Force
fancybear:gwerty               - MD5 JTR Incremental Brute Force
chicagobear:cmw880             - MD5 JTR Incremental Brute Force
cindybear:craftpw              - MD5-crypt Hashcat Xato-10-million

bigbear:office                     - SHA512 JTR 10-million-password-list-top-1000000.txt

booboobear:P@ssw0rd    - NT JTR 10-million-password-list-top-1000000.txt
mamabear:23742374       - NT JTR 10-million-password-list-top-1000000.txt
fozziebear:iseesun            - NT JTR Brute Force ASCII Incremental
sisterbear:vjnxly                - NT JTR Brute Force ASCII Incremental
yogibear:00399032          - NT JTR Brute Force ASCII Incremental

Wordlists:
Daniel Miessler Github SecLists : 
    10-million-password-list-top-1000000.txt
    xato-net-10-million-passwords.txt

Experiments:

MD5Crypt, SHA512crypt, NT, LM  on John the Ripper 
John the Ripper 10-million-password-list-top-1000000 

Hashcat - xato-net-10-million-passwords.txt

2 hour incremental ASCII on John the Ripper
</pre>

<pre> I initially threw all the password hashes into a crackme.txt
then ran John the Ripper on many of the wordlists in the Daniel
Meissler SecLists. I was able to crack a couple using
xato-net-10-million-passwords-1000000.txt, darkc0de.txt,
darkweb2017-top10000.txt, bt4-password.txt, cirt-default-passwords.txt
but then soon realize this wasn't efficient as putting all the
passwords hashes in one file confused John the Ripper. Then I started
breaking the password hashes into groups based on their encryption
hash algorithm used and using format to set the algorithm to use such
as --format=NT, SHA512crypt, and MD5crypt. Breaking the password
hashes into groups based on the encryption hash algorithm used helped
especially --format=NT crack some of the last passwords.  </pre>

<pre>
Cracked Passwords ($6$): For these, I used John the Ripper with a dictionary word list 
papabear:prodigally
bigbear:office

Cracked Passwords ($1$): For these, I used John the Ripper with the xato 10 million password list provided from Daniel Miessler's github
barneybear:stonks
grizzlybear:t05luo
cindybear:craftpw
fancybear:gwerty

Cracked Passwords (unsalted): For these, I used crackstation.net
booboobear:P@ssw0rd
fozziebear:iseesun
mamabear:23742374
yogibear:00399032
</pre>

<pre>
I used the lists found in SecLists and hashcat to crack the salted passwords (MD5 AND SHA-512) and used https://crackstation.net/ to crack the unsalted ones (NTLM).

fancybear: gwerty (darkweb2017-top10000.txt)
grizzlybear: t05luo (xato-net-10-million-passwords.txt)
cindybear: craftpw (xato-net-10-million-passwords.txt)
bigbear: office (Leaked-Databases/rockyou.txt)
booboobear: P@ssw0rd (https://crackstation.net/)
fozziebear: iseesun (https://crackstation.net/)
mamabear: 23742374 (https://crackstation.net/)
yogibear: 00399032 (https://crackstation.net/)
</pre>

<pre>
How I Did It: 

I used John the Ripper on my laptop. I split up the crackme-spring2021.txt into 3 different .txt files:
crackme1.txt: contains MD5 format
crackme2.txt: contains SHA-512 format
crackme3.txt: contains the rest of the passwords

 

On crackme1.txt and crackme2.txt I tried a few different wordlists including: 
john --wordlist=xato-net-10-million-passwords.txt {crackme.txt}
john --wordlist=darkweb2017-top10000.txt  {crackme.txt}
john {crackme.txt}

 

On crackme3.txt I tried:
john --format=NT --rules -w=darkc0de.txt crackme3.txt 
john --format=NT --rules -w=rockyou.txt crackme3.txt 

I also tried on --wordlist=german_misc.txt, --wordlist=mssql-passwords-nansh0u-guardicore.txt and a few others but didn’t have any luck 

**Note: I downloaded the rockyou.txt from https://www.kaggle.com/wjburns/common-password-list-rockyoutxt. The rest of the wordlists are from Daniel Miessler’s SecLits: https://github.com/danielmiessler/SecLists.
</pre>

<pre>
For booboobear, fozziebear, mamabear, yogibear, I used the website https://crackstation.net/

For sisterbear, I used the website https://www.onlinehashcrack.com/

For grizzlybear, cindybear, fancybear, papabear, bigbear I used John the Ripper. 

I used the rockyou list for cindybear and bigbear, 

darkweb2017-top1000000 list for fancybear, 

10-million-password-list-top-1000000 list for grizzlybear,

darkc0de list for papabear (this took 4 hours, 36 minutes, and 1 second btw).
</pre>

<pre> Methodology: I created a python script that compiled all of the
wordlists in SecLists into a single txt file. I then used that txt
file on john the ripper for the md5 and SHA-512 hashes. I attempted to
use my Raspberry to crack passwords, but ran into some trouble with
john. I also decided that I didn't want to burn out my pi, so I mostly
used my own computer. For the NTLM hashes, I used online databases of
common NTLM hashses to crack 4 out of the 5 NTLMs.  </pre>

<pre> I created three different files, each one containing all of the
hashes from the different hash types.  At first, I tried to just use
john with the filename. i believe this gave me barneybear and
fancybear but it took forever. Then, I started using the wordlists
from the seclists github. Using 10 million different passwords, john
was able to find matches for a few more passwords.  The last hash type
was a little different. John wouldnt load them correctly, so I found a
hash identifier on google and inputted one of the hashes. it told me
the hash type which I then specified when running john.  </pre>

<pre>
MD5
barneybear:stonks          (JtR incremental ASCII)
grizzlybear:t05luo        (JtR with xato-net-10-million-passwords.txt wordlist)
cindybear:craftpw        (JtR with rockyou.txt wordlist)


SHA512
bigbear:office            (JtR with xato-net-10-million-passwords.txt wordlist)


NTLM
sisterbear:vjnxly        (JtR with --format=NT option)
mamabear:23742374        (JtR with --format=NT format option)
yogibear:00399032        (JtR with --format=NT format option)
fozziebear:iseesun        (JtR with --format=NT format option)
</pre>
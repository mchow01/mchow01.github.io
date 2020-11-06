---
layout: post
title:  "Results of a Password Cracking Contest in My Security Class (Fall 2020)"
date:   2020-11-06 16:00:00
categories: education security
---

Each time I teach my Security class, I give a month-long lab to crack as many passwords as possible.  For this fall's contest [(opened on October 1, 2020)](https://twitter.com/0xmchow/status/1311749343993528322), I used three different hash types: NTLM, MD5, and SHA-512.  The contest closed on November 5th at 11:59 PM PDT.  The password hashes (30 total):

<pre>
morocco:$1$vg8PBEJ7$ivM1BTtIJzZkgLBGElBQ61:1003:1003:,,,:/home/morocco:/bin/bash
tunisia:$1$GpnNHYmW$Z7A9RWC3GlqTlMDuL4cuE/:1004:1004:,,,:/home/tunisia:/bin/bash
columbia:$1$VG.s5MUf$qkgFOcYZViJ5ZDfXtumWd1:1005:1005:,,,:/home/columbia:/bin/bash
germany:$1$tqzG31dC$6h4sc9SYz1gYSuG6pW4390:1006:1006:,,,:/home/germany:/bin/bash
japan:$1$i4D6lAHD$LzC5sjtda1q93Gy9s99nE.:1007:1007:,,,:/home/japan:/bin/bash
denmark:$1$P0KrA4kP$XSU3ZL.HqFZa/wyeokJCD1:1008:1008:,,,:/home/denmark:/bin/bash
serbia:$1$UOQSHvjV$V9Wn/IW8zyMS0l2zg2gdb.:1009:1009:,,,:/home/serbia:/bin/bash
belgium:$1$DajT9Q7N$zkOrFuQnsg7fWOYGpwtJe.:1010:1010:,,,:/home/belgium:/bin/bash
uruguay:$1$aaPR99jr$1V2ijvzLNQCWRhUBbgziM1:1011:1011:,,,:/home/uruguay:/bin/bash
portugal:$1$bBZ262cY$fwKbPMaKbMnoZcg6ra8Wk/:1012:1012:,,,:/home/portugal:/bin/bash
panama:$6$diypI1PcL0TVj6U7$XfrpfXl/k3UHt2JFh.Il.6Jwq8.Fy3FsscubcOP9e8u6IUvx0XFNIBvQzL8vUd6tlpW5.lx7vPfEcJOUcxjs5.:1002:1003:,,,:/home/panama:/bin/bash
saudiarabia:$6$LI/Z7fa2BRRcGfDL$mdBsTeGAE.fr1PAazfFfZPoOSUfQ9vD2l1OvuAfYgraKwD4Rwx2Xi8sxKgL.7Kuz9XEhbNwnI0Yq3EQHO7G6A0:1003:1004:,,,:/home/saudiarabia:/bin/bash
egypt:$6$X4dTOMfZLSPGuYgF$LzM84eu.RdvrOY5rG6lk9BhJBkNBrBQzNDdMI9/AFzxHmjyVRlfCzs6HTtGw6xwijv9sdHpu3qebBrwWG9HsV.:1004:1005:,,,:/home/egypt:/bin/bash
argentina:$6$KOTowzvITs2wRp9c$C38sXIewTdzwlGkXvqqPvpkp6cosbZ2GpQ83vEId0FiT9OJq4G93YHqJ52fLoXpOw5eExidtgPcngpSF5TfrM/:1005:1006:,,,:/home/argentina:/bin/bash
mexico:$6$9MarWt5tQKngxBE0$f4/lAP61h6KHlH8pagDOTyG7qRGvH9dcoxDx7/7j6NSipQyoY4CSN.ds8tjdwEd3saldnNiOD9TdFUMIBdRgn1:1006:1007:,,,:/home/mexico:/bin/bash
france:$6$oFUCFd59p7FK/uLV$qvO6XkZY5tVL2rnmRVSShc2FLV3mf7pIpNo.LICRAilHlBFszDXMiwe/NsxsjL6GXlWoygU9a7sRqtgMTcC2H/:1007:1008:,,,:/home/france:/bin/bash
switzerland:$6$TKPFr/MahRd/qsNm$5e4YKbMj54OSTGV4/h4pGmAgGMz3w/wayADKNt36.eGxEQ0vHf6nOTdo5wehz6vLIzLazt8214jq4vmRXKEBr1:1008:1009:,,,:/home/switzerland:/bin/bash
australia:$6$7FnuGKJ1tOoQTTQx$2MHs0EX29Bz5edJGeVd4EMMmG80SbhBGfhn/6lJNAtKOKDWPuzgBcbUZbhe4Dgy9CCGtwHYsfKEEHDFW9IxZP.:1009:1010:,,,:/home/australia:/bin/bash
sweden:$6$/5DMsJvsctGN0.E1$sDjqfGiqj290vI2YyMi/.cI5p4OMeGMUTjfsXX5TIht0lb9lUBhBo5gg/LV347tzXD5qmOyHYAkbAxdfDN4zo/:1010:1011:,,,:/home/sweden:/bin/bash
peru:$6$n91QW5uCJxjxGGxB$SsHokDU9Oh8YXEYxS2ewvs0b5O0dFPjcHBE90P1YIrHkOTMvAXsDRWWxEC9sniRyEJw..LYEUPrua0nk2FjNv1:1011:1012:,,,:/home/peru:/bin/bash
brazil:1010:aad3b435b51404eeaad3b435b51404ee:8855a8072eefc1b41d77f8ef46db42e1:::
costarica:1003:aad3b435b51404eeaad3b435b51404ee:735636e07397f11a6b658543d12f2bce:::
croatia:1004:aad3b435b51404eeaad3b435b51404ee:a46b4f30962158c6f78ac8b3a88629cd:::
england:1008:aad3b435b51404eeaad3b435b51404ee:959bbfc0eafaa19721282077899b572c:::
iceland:1006:aad3b435b51404eeaad3b435b51404ee:b09679d24e67343b6650049f0eb854f7:::
iran:1001:aad3b435b51404eeaad3b435b51404ee:3637d26785ba5327d3dff5a3b2c8fa50:::
nigeria:1005:aad3b435b51404eeaad3b435b51404ee:2071cd3891d0ad5bc2b38f80274d8c85:::
senegal:1009:aad3b435b51404eeaad3b435b51404ee:c8a188f6c0c4e55d66d3d51cf2fe5103:::
southkorea:1007:aad3b435b51404eeaad3b435b51404ee:28ed64da632d774ad45f17acc851a643:::
spain:1002:aad3b435b51404eeaad3b435b51404ee:3c19c71d5726e1f3008b040c394219ce:::
</pre>

110 submissions across two classes where one is for our inaugural Online Master's Program.  The answers:
* (MD5) morocco:snacks => 109 students cracked this
* (MD5) tunisia:agesque => 71 students cracked this
* (MD5) columbia:3pi5c0p3 => 70 students cracked this
* (MD5) germany:caused => 87 students cracked this
* (MD5) japan:29LMGz3V => 65 students cracked this
* (MD5) denmark:l'acad => 76 students cracked this
* (MD5) serbia:p15mgrqx => 0 student cracked this
* (MD5) belgium:M3Yogm => 1 student cracked this
* (MD5) uruguay:#:j9'v<!dZ#nt-eQ => 0 student cracked this
* (MD5) portugal:TRACE => 99 students cracked this
* (SHA512) panama:HPP196 => 31 students cracked this
* (SHA512) saudiarabia:yossi => 50 students cracked this
* (SHA512) egypt:AgF0vh => 0 student cracked this
* (SHA512) argentina:dallas => 102 students cracked this
* (SHA512) mexico:cheese => 101 students cracked this
* (SHA512) france:NOAHHILLWELOVEYOUBUBBA => 0 student cracked this
* (SHA512) switzerland:fK{B[M*7F@ => 0 student cracked this
* (SHA512) australia:633210 => 25 students cracked this
* (SHA512) sweden:5394 => 63 students cracked this
* (SHA512) peru:JonMoxley => 0 student cracked this
* (NTLM) iran:ThankYouSookHeeForWIT2020 => 0 student cracked this
* (NTLM) spain:LeChampion => 40 students cracked this
* (NTLM) costarica:526047 => 75 students cracked this
* (NTLM) croatia:78121241 => 40 students cracked this
* (NTLM) nigeria:meteor44 => 68 students cracked this
* (NTLM) iceland:Starf8sh => 54 students cracked this
* (NTLM) southkorea:badg3r5 => 64 students cracked this
* (NTLM) england:#@y4tfTMcvC6mg4Z => 0 student cracked this
* (NTLM) senegal:5JcuHvKjYr => 0 student cracked this
* (NTLM) brazil:th!xGy%Z => 5 students cracked this

To earn all 10 / 10 points for the lab, students had to crack 10 or more passwords.  The final distribution:

<pre>
21
19 (3 total)
18 (8 total)
17 (3 total)
16 (5 total)
15 (5 total)
14 (8 total)
13 (5 total)
12 (12 total)
11 (16 total)
10 (17 total)
9 (9 total)
8 (8 total)
7 (5 total)
6
5 (2 total)
3
2
</pre>

The winner cracked 21 of the 30 passwords, submitted on October 9th at 5:00 AM eastern time.  The winner's haul and strategy:

<pre>
germany:caused 
morocco:snacks 
costarica:526047 
southkorea:badg3r5 
croatia:78121241 
portugal:TRACE 
saudiarabia:yossi       
nigeria:meteor44 
sweden:5394 
iceland:Starf8sh   
argentina:dallas 
mexico:cheese 
tunisia:agesque        
columbia:3pi5c0p3 
panama:HPP196 
australia:633210 
spain:LeChampion 
denmark:l'acad 
japan:29LMGz3V 
belgium:M3Yogm 
brazil:th!xGy%Z 

Method – used hashcat mask attacks and hashcat dictionary attacks for
all passwords all while renting a server with many GPU cards Used
Daniel Miessler word lists and weakpass
wordlist. https://vast.ai/console/create/ 10 GTX 1080i server
</pre>

Methodologies from the runners-up who cracked 17 or more passwords:

<pre>I wrote a small python script to read in all of the passwords in
the SecList github, enter them into a set (so no dupes), and then
write them out to one large file. The important part wsa to make sure
the paswords were ordered from smallest lists to largest (to
prioritize the top-x lists over full database dumps). From there I
just ran that list against each set of passwords types on my
rapspberry pi for a few days. I never made it all the way through the
sha passwords, but I didn't want to run for too long.</pre>

<pre>
Methods:
John the Ripper (JtR)
- darkweb2017-top10000.txt (mexico, argentina)
- darkcOde.txt (columbia, tunisia, germany, morocco, portugal)
- xato-net-10-million-passwords.txt (denmark, japan, sweden)
- rockyou.txt (saudiarabia, australia)

Ophcrack (rainbow tables) https://www.objectif-securite.ch/en/ophcrack 
(brazil, costarica, croatia, iceland, nigeria, southkorea)

CrackStation.net
(spain)
</pre>

<pre> Well, I wrote a python script that compiled all the .txt files
in the passwords folder from SecLists into one big .txt file. Then I
just ran hashcat in wordlist mode for all the hashes.</pre>

<pre>I cracked 17 passwords in 5 hours from just the wordlists in
Seclists...

After that, I cracked one password by running a combinator attack and
one more from a breach compilation wordlist that had 1.4 billion
passwords.
</pre>

<pre> I first just ran john the ripper with the rockyou wordlist. I
also explored various other wordlists found from the openwall wordlist
archive. I mixed in no rules and then using all of the default john
rules. I also downloaded all of the KoreLogic word mangling rules, but
have not had much luck with those. I tried different formats with
john, but I've only been able to crack using MD5 & variants, sha512 &
variants, and then using NT format. Tried running incremental mode,
but this did not reveal any new passwords over 3 days of continual
running (expected). Will have to get more creative with word
rules. Trying to set up hashcat to run on GPU, so then I can run some
cracking on my CPU and GPU at the same time for more hashing mwahaha

I also tried to determine all of the hash types, I found that there
are only three types of hashes in this file. MD5crypt, SHA512, and
then either MD5/MD4. Not sure if this is true or not, John says it
detect LM/NT, md5crypt-long, sha512-long, but haven't had any luck
with the long variants.

Using hashcat now, found a few more passwords. Also using larger
wordlists So sad :( I cracked all 19 of these in like the first week
or so, and then didnt have any luck since then. I probably have
50-60gb of wordlists downloaded, was running hashcat full-time on my
friend's PC he wasn't using 24/7 for three weeks, probably used an
amazon P2.xlarge instance with tesla K80 for 72 hours. Nothin. I even
went through and compiled all of the previous passwords you've
released, and pulled out some trends to make custom masks with no
luck. I also just brute forced ?a?a?a?a?a?a?a for md5crypt and NTLM
with no luck beyond what I already had. Can't wait to see all the
passwords released</pre>

<pre>I used rockyou.txt, 29 files from Daniel Miessler's SecLists, and
bruteforce.</pre>

<pre>I used john with various word lists I found on the internet (mostly
github) for groups1 and 2, then used online ophcrack software for
grroup 3</pre>

Methodologies from those who cracked 10 or more passwords:

<pre>
morroco:snacks      John the Ripper (default wordlist)
tunisia:agesque     hashcat with crackstation's wordlist
germany:caused      John the Ripper (default wordlist)
denmark:l'acad      hashcat with crackstation's human passwords wordlist
portugal:TRACE      hashcat with crackstation's human passwords wordlist
columbia:3pi5c0p3   hashcat with crackstation's wordlist
argentina:dallas    hashcat with SecLists' best1050.txt
mexico:cheese       hashcat with SecLists' best1050.txt
sweden:5394         hashcat with crackstation's human passwords wordlist
australia:633210    hashcat with crackstation's human passwords wordlist
saudiarabia:yossi   hashcat with crackstation's human passwords wordlist
costarica:526047    hashcat with crackstation's human passwords wordlist
croatia:78121241    hashcat with crackstation's wordlist
nigeria:meteor44    hashcat with crackstation's wordlist
southkorea:badg3r5  hashcat with crackstation's wordlist
spain:LeChampion    hashcat with crackstation's wordlist
iceland:Starf8sh    hashcat with SecLists' xato-net-10-million-passwords.txt
nigeria:meteor44    John the Ripper (default wordlist)
</pre>

<pre> Below there are username and password pairs in the format
username : password. There are a description of how they were found
after each one.

1) morocco: snacks
found using darkc0de.txt and john the ripper. darkc0de.txt is from Daniel Miessler's github. The crackme-fall2020.txt was split into types. This one was found running only the md5 crypt ones. The following command was used 
/usr/sbin/john --format=md5crypt-long  --wordlist="darkc0de.txt"  crackme-fall2020-md5.txt 

2) columbia: 3pi5c0p3
found using darkc0de.txt and john the ripper. darkc0de.txt is from Daniel Miessler's github. The crackme-fall2020.txt was split into types. This one was found running only the md5 crypt ones. The following command was used 
/usr/sbin/john --format=md5crypt-long  --wordlist="darkc0de.txt"  crackme-fall2020-md5.txt 

3) mexico: cheese
found using xato-net-10-million-passwords-1000000.txt and john the ripper. xato-net-10-million-passwords-1000000.txt is from Daniel Miessler's github. The crackme-fall2020.txt was split into types. This one was found running only the sha512 crypt ones. The following command was used 
/usr/sbin/john --format=sha512crypt --wordlist="xato-net-10-million-passwords-1000000.txt" crackme-fall2020-sha.txt 

4) argentina: dallas
found using xato-net-10-million-passwords-1000000.txt and john the ripper. xato-net-10-million-passwords-1000000.txt is from Daniel Miessler's github. The crackme-fall2020.txt was split into types. This one was found running only the sha512 crypt ones. The following command was used 
/usr/sbin/john --format=sha512crypt --wordlist="xato-net-10-million-passwords-1000000.txt" crackme-fall2020-sha.txt 

5) sweden: 5394
found using xato-net-10-million-passwords-1000000.txt and john the ripper. xato-net-10-million-passwords-1000000.txt is from Daniel Miessler's github. The crackme-fall2020.txt was split into types. This one was found running only the sha512 crypt ones. The following command was used 
/usr/sbin/john --format=sha512crypt --wordlist="xato-net-10-million-passwords-1000000.txt" crackme-fall2020-sha.txt 

6) portugal: TRACE
found using cirt-default-passwords.txt and john the ripper. cirt-default-passwords.txt is from Daniel Miessler's github. The crackme-fall2020.txt was split into types. This one was found running only the md5 crypt ones. The following command was used 
/usr/sbin/john --format=md5crypt-long  --wordlist="cirt-default-passwords.txt"  crackme-fall2020-md5.txt  

7) panama: HPP196
found using cirt-default-passwords.txt and john the ripper. cirt-default-passwords.txt is from Daniel Miessler's github. The crackme-fall2020.txt was split into types. This one was found running only the sha512 crypt ones. The following command was used 
/usr/sbin/john --format=sha512crypt --wordlist="cirt-default-passwords.txt"  crackme-fall2020-sha.txt

8) southkorea: badg3r5
found using cirt-default-passwords.txt and john the ripper. cirt-default-passwords.txt is from Daniel Miessler's github. The crackme-fall2020.txt was split into types. This one was found running only the NT and LM crypt ones. The following command was used 
/usr/sbin/john --format=NT --wordlist="cirt-default-passwords.txt" crackme-fall2020-ntlm.txt 

9) germany: caused
found using dutch_common_wordlist.txt and john the ripper. dutch_common_wordlist.txt is from Daniel Miessler's github. The crackme-fall2020.txt was split into types. This one was found running only the md5 crypt ones. The following command was used 
/usr/sbin/john --format=md5crypt-long  --wordlist="dutch_common_wordlist.txt"  crackme-fall2020-md5.txt

10) saudiarabia: yossi
found using rockyou.txt and john the ripper. rockyou.txt was downloaded from naive-hashcat github. The crackme-fall2020.txt was split into types. This one was found running only the sha crypt ones. The following command was used 
/usr/sbin/john --format=sha512crypt --wordlist="rockyou.txt"  crackme-fall2020-sha.txt

11) denmark: l'acad
found using xato-net-10-million-passwords-1000000.txt and john the ripper. xato-net-10-million-passwords-1000000.txt is from Daniel Miessler's github. The crackme-fall2020.txt was split into types. This one was found running only the md5 crypt ones. The following command was used 
/usr/sbin/john --format=md5crypt-long  --wordlist="xato-net-10-million-passwords-1000000.txt"  crackme-fall2020-md5.txt

12) japan: 29LMGz3V
found using xato-net-10-million-passwords-1000000.txt and john the ripper. xato-net-10-million-passwords-1000000.txt is from Daniel Miessler's github. The crackme-fall2020.txt was split into types. This one was found running only the md5 crypt ones. The following command was used 
/usr/sbin/john --format=md5crypt-long  --wordlist="xato-net-10-million-passwords-1000000.txt"  crackme-fall2020-md5.txt

13) nigeria: meteor44
found using xato-net-10-million-passwords-1000000.txt and john the ripper. xato-net-10-million-passwords-1000000.txt is from Daniel Miessler's github. The crackme-fall2020.txt was split into types. This one was found running only the NT and LM crypt ones. The following command was used 
/usr/sbin/john --format=NT --wordlist="xato-net-10-million-passwords.txt" crackme-fall2020-ntlm.txt 

14) iceland: Starf8sh
found using xato-net-10-million-passwords-1000000.txt and john the ripper. xato-net-10-million-passwords-1000000.txt is from Daniel Miessler's github. The crackme-fall2020.txt was split into types. This one was found running only the NT and LM crypt ones. The following command was used 
/usr/sbin/john --format=NT --wordlist="xato-net-10-million-passwords.txt" crackme-fall2020-ntlm.txt 

15) costarica: 526047
found using xato-net-10-million-passwords-1000000.txt and john the ripper. xato-net-10-million-passwords-1000000.txt is from Daniel Miessler's github. The crackme-fall2020.txt was split into types. This one was found running only the NT and LM crypt ones. The following command was used 
/usr/sbin/john --format=NT --wordlist="xato-net-10-million-passwords.txt" crackme-fall2020-ntlm.txt
</pre>

<pre>I used John the Ripper with the SecLists/Passwords/ wordlists to
crack the passwords. I also used the --rules=Jumbo flag to crack one
extra password that didn't show up otherwise.</pre>

<pre>
morocco:snacks
I used the xato-net-10-million-passwords-1000000.txt wordlist from SecList in JtR
columbia:3pi5c0p3 
I used the bt4-password.txt worldlist from SecList in JtR
portugal:TRACE
I used the bt4-password.txt worldlist from SecList in JtR
germany:caused
I used the bt4-password.txt worldlist from SecList in JtR
denmark:l'acad
I used the xato-net-10-million-passwords.txt from SecList in JtR, but only with the first 5 million words. 
mexico:cheese
I used the 10-million-password-list-top-1000000.txt from SecList in JtR
argentina:dallas
I used the 10-million-password-list-top-1000000.txt from SecList in JtR
panama:HPP196
I used the cirt-default-passwords.txt from SecList in JtR
sweden:5394
I used the xato-net-10-million-passwords.txt from SecList in JtR
southkorea:badg3r5
I ran a separate file of the NTLM hashes through JtR and it was cracked with brute force.
costarica:526047
I ran a separate file of the NTLM hashes through JtR and it was cracked with brute force.
nigeria:meteor44
I used the xato-net-10-million-passwords.txt from SecList in JtR, but only with the first 5 million words.
iceland:Starf8sh
I used the xato-net-10-million-passwords.txt from SecList in JtR, but only with the first 5 million words.
japan:29LMGz3V
I used the xato-net-10-million-passwords.txt from SecList in JtR, but only with the first 5 million words.
</pre>

<pre>
Used a number of wordlists on John --wordlist=FULLPATH
combined(unshadowedfile).  I concatenated a bunch of them together and
just ran them all using john the ripper.  I used the sectlists
wordlists found on githup.  Then also realized they were on my Kali
instance under /usr/share/wordlists. I have a fully loaded/install
Kali Linux running on WSL2 on Windows 10.

John the ripper:
Concatenated all txt files into two and ran against it to find pwd
for the following:  
morocco:snacks:1003:1003:,,,:/home/morocco:/bin/bash
tunisia:agesque:1004:1004:,,,:/home/tunisia:/bin/bash
columbia:3pi5c0p3:1005:1005:,,,:/home/columbia:/bin/bash
germany:caused:1006:1006:,,,:/home/germany:/bin/bash
japan:29LMGz3V:1007:1007:,,,:/home/japan:/bin/bash
denmark:l'acad:1008:1008:,,,:/home/denmark:/bin/bash
portugal:TRACE:1012:1012:,,,:/home/portugal:/bin/bash
used hashcat with rockyou dictionaries (had to unzip).
M can be over 237 types (--help)
m is hashtype 	1000	NTLM
	500	Unix md5 (unix)
	1800	Sha-512(unix)
hashcat -m 1800 sha-512passcodes.txt /usr/share/wordlists/rockyou.txt
hashcat (v6.1.1) starting… 
Gave :
$6$KOTowzvITs2wRp9c$C38sXIewTdzwlGkXvqqPvpkp6cosbZ2GpQ83vEId0FiT9OJq4G93YHqJ52fLoXpOw5eExidtgPcngpSF5TfrM/:dallas
$6$9MarWt5tQKngxBE0$f4/lAP61h6KHlH8pagDOTyG7qRGvH9dcoxDx7/7j6NSipQyoY4CSN.ds8tjdwEd3saldnNiOD9TdFUMIBdRgn1:cheese
</pre>
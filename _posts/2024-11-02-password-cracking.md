---
layout: post
title:  "Results of a Password Cracking Contest in My Security Class (Fall 2024)"
date:   2024-11-02 15:00:00
categories: education security
---

Each time I teach my Security class, I give a month-long lab to crack as many passwords as possible.  For this fall's contest (opened on October 1, 2024), I used two different hash types: MD5 and SHA-512.  The contest closed on November 1st at 11:59 PM PDT.  The password hashes (16 total):

<pre>
sisterbear:$1$meDA7UZm$8Cii/BVR2FCbe51g0VR8I.:1001:1001:,,,:/home/sisterbear:/bin/bash
grizzlybear:$1$8Bg6aLRq$CjQm1v91C96Ldl/yZdo5Z0:1002:1002:,,,:/home/grizzlybear:/bin/bash
jackbear:$1$eORtBHsd$HDdVqrQDmp44iiLxLt8VD/:1003:1003:,,,:/home/jackbear:/bin/bash
pandabear:$1$OCspbg4z$/s.JVe74KyntT3ax7ryOx.:1004:104:,,,:/home/pandabear:/bin/bash
yogibear:$1$C2UPECgG$yuWXqxJrzP7BOuMvhBxX51:1005:1005:,,,:/home/yogibear:/bin/bash
mamabear:$1$w/39f4CN$FRi2kI3SjO1hvAiuBLApw.:1006:1006:,,,:/home/mamabear:/bin/bash
barneybear:$1$ChfEL.qh$x/Pyr9ASnlWSBUiZP2vrC0:1007:1007:,,,:/home/barneybear:/bin/bash
papabear:$1$Hvgj76BS$QJvM2DnkbRMwt4WsjsaWE1:1008:1008:,,,:/home/papabear:/bin/bash

bluebear:$6$csATVChW0EDFvOxe$Go04JRoOaZGOn6DFfjlEegI5VILMTKkMR/y8PKhO4IyOxs6dLb9826ZaJyQ66ZxVyVb/E5ZfaHk0vNRsz7kQo0:1009:1009:,,,:/home/bluebear:/bin/bash
cozybear:$6$JebLS.c2mktxZcgl$64.cqo8W08nNpUmay9PC0BfTe4lgS6lXOhEX52ftcwC8zOVf1Qd8FdTi4DLTAiSEEil2OuF3mnwRnbrjvSN61/:1010:1010:,,,:/home/cozybear:/bin/bash
polarbear:$6$9wMEUyUisuS4bPDe$oWlPDsDsTXG.tEY2dVrbk1S4JnstNEWfBr.molK.nSv68VS5/bEKPh967.IrY4YPzjvFkRqXQdRlXAU0jr.jf.:1011:1011:,,,:/home/polarbear:/bin/bash
teddybear:$6$29qVCVzp.Q17JXVY$zPhYZUlZNkbw8fvQQVjLTuW4MA0PjzySHPEAtKmezba0wzrtYCWM60u2c946ODPnUBygW/YRIRCO.jU01l704/:1012:1012:,,,:/home/teddybear:/bin/bash
carebear:$6$eltS1hJ9D/M5wRve$sn2LY9VTase07I0Xs7TfK50E2qT7hrL/lmKFhoepPHa8IBXIkKdt4QJfJXpSHLKFWWMzC6fCzldaXB03uFQ7n0:1013:1013:,,,:/home/carebear:/bin/bash
blackbear:$6$7hQwol6AVBtGtjzb$0AsXmamaBKoEORKAc0Vh54E0WZJ.TREivbBEizmSzszHqyxmFbG0gfbBPmdJdVgZqiwEQEBdtCEcEgp.k9tPq.:1014:1014:,,,:/home/blackbear:/bin/bash
fancybear:$6$pKg7SbOiBmDEuHpQ$C.hZhPEBKvoaG33aMM5rrmJpj.ceXqwCPDDIkeyEGjvK22f6ohqZeAGqceMPWPCJRkcKqFvmtJ/8GRAuYIxhR1:1015:1015:,,,:/home/fancybear:/bin/bash
brotherbear:$6$si4IzJRiz8p1JAa4$CgCLo2n2yVsA0j3MCLX//QrFdsuUJk6NiTokPFt0LPDRPYV/.Rn8w5riQuFB.R2q9pjO4b51kbLzs/T1t6M2N1:1016:1016:,,,:/home/brotherbear:/bin/bash
</pre>

117 submissions across two classes.  The answers:
* (MD5) sisterbear:reflex => 115 students cracked this
* (MD5) grizzlybear:tenebamur => 104 students cracked this
* (MD5) jackbear:574ch95 => 106 students cracked this
* (MD5) pandabear:scarlett1 => 114 students cracked this
* (MD5) yogibear:2^;CU4i*Z#Eryu8T => 0 student cracked this
* (MD5) mamabear:fmdoei => 22 students cracked this
* (MD5) barneybear:amanduzzpower => 44 students cracked this
* (MD5) papabear:hildy123 => 61 students cracked this
* (SHA-512) bluebear:clay => 114 students cracked this
* (SHA-512) cozybear:BETHANDEMILY => 24 students cracked this
* (SHA-512) polarbear:4085018 => 14 students cracked this
* (SHA-512) teddybear:3ch0p124c7ic => 88 students cracked this
* (SHA-512) carebear:arredavamo => 91 students cracked this
* (SHA-512) blackbear:bhDZ@&M_86YUhTXt => 0 student cracked this
* (SHA-512) fancybear:SHYKUF => 0 student cracked this
* (SHA-512) brotherbear:qq123456 => 108 students cracked this

To earn all 10 / 10 points for the lab, students had to crack 8 or more passwords.  The final distribution:

<pre>
13 (x7)
12 (x2)
11 (x10)
10 (x7)
9 (x19)
8 (x61)
7 (x1)
6 (x3)
5 (x3)
4 (x2)
2 (x1)
1 (x1)
</pre>

Average number of passwords cracked: 8.58974359

Median number of passwords cracked: 8

How I created this fall's password cracking contest:
* sisterbear's password => taken from `xato-net-10-million-passwords-10000.txt` in Daniel Miessler's SecLists
* grizzlybear's password => taken from `darkc0de.txt` in Daniel Miessler's SecLists
* jackbear's password => taken from `darkc0de.txt` in Daniel Miessler's SecLists
* pandabear's password => taken from `darkweb2017-top10000.txt` in Daniel Miessler's SecLists
* yogibear's password => randomly generated using all [a-zA-Z0-9!@#$%^&*()specialcharacters]
* mamabear's password => randomly generated using all [a-z], less than 8 characters
* barneybear's password => taken from `md5decryptor-uk.txt` in Daniel Miessler's SecLists
* papabear's password => taken from `Ashley-Madison.txt` in Daniel Miessler's SecLists
* bluebear's password => taken from `xato-net-10-million-passwords-10000.txt` in Daniel Miessler's SecLists
* cozybear's password => taken from `md5decryptor-uk.txt` in Daniel Miessler's SecLists
* polarbear's password => => randomly generated using all [0-9], less than 8 characters
* teddybear's password => taken from `darkc0de.txt` in Daniel Miessler's SecLists
* carebear's password => taken from `darkc0de.txt` in Daniel Miessler's SecLists
* blackbear's password => randomly generated using all [a-zA-Z0-9!@#$%^&*()specialcharacters]
* fancybear's password => randomly generated using all [A-Z], less than 8 characters
* brotherbear's password => taken from `darkweb2017-top10000.txt` in Daniel Miessler's SecLists

Selected methodologies and hauls from students:

> Pandabear:scarlett1
> Sisterbear:reflex
> Grizzlybear:tenebamur
> Papabear:hildy123
> Barneybear:amanduzzpower
> Jackbear:574ch95
> Bluebear:clay
> Carebear:arredavamo
> Brotherbear:qq123456
>
> I used John the Ripper with its default settings, and it was able to crack pandabear extremely quickly. However, it then had trouble proceeding even when wordlists were supplied. Thus, I turned to Hashcat. I supplied it with the wordlist that I found online: Rockyou and SecList. I wrote a python script to automate the linux commands and these wordlists were able to get be everything but brotherbear relatively quickly (within an hour or two). Then, I left the password cracking running for several hours. It was eventually able to crack brotherbear.

> sisterbear:reflex
> jackbear:574ch95
> papabear:hildy123
> pandabear:scarlett1
> bluebear:clay
> brotherbear:qq123456
> carebear:arredavamo
> cozybear:BETHANDEMILY
> teddybear:3ch0p124c7ic
>
> First 3 I used hashsuite windows, darkc0de.txt and rockyou
> Fourth one I used jtr on my Linux machine, default wordlist
> Bluebear I got on jtr on an aws instance with 10-million-password-list-top-1000000.txt (still running)
> brotherbear I got on hashcat using windows with rockyou
> carebear I got with all.lst on hashcat on windows
> cozybear I got with md5decryptor-uk on hashcat on windows
> teddybear I got with bt4-password.txt on hashcat on windows

> bluebear:clay
> brotherbear:qq123456
> sisterbear:reflex
> teddybear:3ch0p124c7ic
> jackbear:574ch95
> grizzlybear:tenebamur
> pandabear:scarlett1
> teddybear:3ch0p124c7ic
> carebear:arredavamo
>
> Using the following commands... 
> hashcat -m 1800 sha512_hashes.txt SecLists/Passwords/xato-net-10-million-passwords.txt --username
> john --wordlist=xato-net-10-million-passwords-1000000.txt --format=md5crypt crackme-fall2024.txt
> john --wordlist=bt4-password.txt --format=sha512crypt crackme-fall2024.txt
> john --wordlist=bt4-password.txt --format=md5crypt crackme-fall2024.txt
> hashcat -m 500 -a 0 -o cracked_md5.txt md5.txt darkc0de.txt
> hashcat -m 1800 -a 0 -o cracked_sha.txt sha.txt darkc0de.txt

> To crack the passwords above, I began by organizing the hash data based on the hash type. I split the original file into two separate files: one for SHA-512-crypt hashes and one for MD5-crypt hashes. This allowed me to efficiently apply the correct cracking algorithms to each set of hashes.
>
>For the SHA-512-crypt hashes, I ran Hashcat using
>
>`hashcat -m 1800 -a 0 -w 3 -o cracked_passwords.txt --username sha512_hashes.txt SecLists/Passwords/Common-Credentials/10-million-password-list-top-1000000.txt`
>
>thus leveraging the common wordlist “10-million-password-list-top-1000000.txt”.  This successfully revealed the passwords for “bluebear” and “brotherbear”.  Then, I tried the “darkc0de.txt” wordlist on the remaining SHA-512-crypt hashes using 
>
>`hashcat -m 1800 -a 0 -w 3 -o cracked_passwords.txt --username sha512_hashes.txt SecLists/Passwords/Common-Credentials/darkc0de.txt`
>
>which resulted in cracking the passwords for “teddybear” and “carebear”.
>
>Similarly, I used the command 
>
>`hashcat -m 500 -a 0 -w 3 -o cracked_passwords2.txt --username md5_hashes.txt SecLists/Passwords/Common-Credentials/10-million-password-list-top-1000000.txt` 
>
>for the MD5-crypt hashes, which uncovered passwords for “sisterbear” and “pandabear”.  To further crack the MD5 hashes, I used the darkc0de.txt wordlist as
>
>`hashcat -m 500 -a 0 -w 3 -o cracked_passwords2.txt --username md5_hashes.txt SecLists/Passwords/Common-Credentials/darkc0de.txt`
>
>
>and successfully revealed the passwords for “grizzlybear” and “jackbear”.

> The password cracking exercise with John the Ripper demonstrated the importance of a multi-faceted approach. While brute-force methods can be exhaustive and time-consuming, strategic use of rules and targeted wordlists significantly improved efficiency and success rates. Observing patterns and understanding user behaviors (like using numeric sequences) also contributed to cracking more passwords with less effort. The use of specialized wordlists, particularly `darkc0de.txt`, proved invaluable in achieving additional breakthroughs.
>
> Future improvements could involve refining rule sets further and leveraging custom masks tailored to specific password creation habits. This approach highlights that understanding human tendencies can be just as crucial as sheer computational power in the world of password security.

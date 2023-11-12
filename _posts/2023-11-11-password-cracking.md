---
layout: post
title:  "Results of a Password Cracking Contest in My Security Class (Fall 2023)"
date:   2023-11-11 20:20:00
categories: education security
---

Each time I teach my Security class, I give a month-long lab to crack as many passwords as possible.  For this fall's contest (opened on October 2, 2023), I used two different hash types: MD5 and SHA-512.  The contest closed on November 10th at 11:59 PM PDT.  The password hashes (16 total):

<pre>
jackbear:$1$tLqWPL3x$hTIUCQLLEKbMlPjhTOmR3.:1001:1001:,,,:/home/jackbear:/bin/bash
brotherbear:$1$C4qXyAjR$J1oL3RYmHaFldTbYjtASZ/:1002:1002:,,,:/home/brotherbear:/bin/bash
fancybear:$1$Ymmh93Qp$4Laygm7i4UDmNfNGAiRF91:1003:1003:,,,:/home/fancybear:/bin/bash
barneybear:$1$LvAdkCl3$mzHq8zre6oW2/vPSKZVPc/:1004:1004:,,,:/home/barneybear:/bin/bash
pandabear:$1$ldmSUyKK$2WYaaRzLS8bDc7wzJFtu61:1005:1005:,,,:/home/pandabear:/bin/bash
yogibear:$1$y7DJOyR4$ro0Oe1wWuToZF3g8tZ2Pf/:1006:1006:,,,:/home/yogibear:/bin/bash
papabear:$1$P54r4/XD$VnEJFiCLP75m/zxUhCGY80:1007:1007:,,,:/home/papabear:/bin/bash
grizzlybear:$1$veIFirtd$RtmKrUCjJMlF6V4B3y00B1:1008:1008:,,,:/home/grizzlybear:/bin/bash

sisterbear:$6$PSouL3fjntaUDkH3$j5h1OZG/2Hg58x9fBH/uEZxEYVvv5UTgM9YKc98TE6bm93ad2jDDTPFjGF0gIU7Eqh.ARwaWG.mMddbDqE.VK0:1009:1009:,,,:/home/sisterbear:/bin/bash
teddybear:$6$AAQBNuTnQ8z/PFM/$xg2fDO5VpwLtNjszFm2EzzlngUwiVYEWZQCjHssZznG9M5i2SJ/BvI4wJ1O9Oh/IwZ9tb7v/5jiLxNpIqJgOB.:1010:1010:,,,:/home/teddybear:/bin/bash
polarbear:$6$MJlp5Pg66tr34Dk5$SbD48g3ePIaza.0P52e1cwfHO9rndZ6b2ToxlhXnaUxib3kGbByPRzia4kXjNadlf2zSnJwf36oRNFQASXOut1:1011:1011:,,,:/home/polarbear:/bin/bash
bluebear:$6$IP3BEwahNiAUsrR6$GHhXZHP0BmLdEfsz9kOtqZZCNFj/3L2UjG3HeL/yPmcLEOwbYKMxUdpaM1b6rjuoE46HmipB7ls8qm/sMxYOL.:1012:1012:,,,:/home/bluebear:/bin/bash
blackbear:$6$dlFpQsHHaXg8QumO$/UyhZH.GSS8/Z8Z.8hr7U9K.1HuOaUeZjFMAoIE36.vB0/Tk044UxFJpAx84bET6JuOUkuoU.Z.8QVmnU/7Lh0:1013:1013:,,,:/home/blackbear:/bin/bash
mamabear:$6$mo205g6IoHx8xUcS$IK6lhefS88BEb/nSUdDOhDnP.O0T6kGTCOTFPbvo.6yWEAzg.P6L.AnP.zJzBHP/P3oKa/tdoII642QFkclD41:1014:1014:,,,:/home/mamabear:/bin/bash
carebear:$6$05gfSCen6gtcVJ8g$cnl6zUX2SYbJUGxZWbC.i0rxbO1gmFyZhTPpjymCy9h0k7eb7Ew5JJqJQqRt96KxMoq71ueSa.wnJaz07XT3K.:1015:1015:,,,:/home/carebear:/bin/bash
cozybear:$6$delqV7KMicfdLoR1$AxREbM10wv0CQTRci0.eQiDQPAElqMuZ.lrsJ1vMH8P2u522Xp8j/RHZscsLNBhHvxGbgExBAdZaHilyqTiJw/:1016:1016:,,,:/home/cozybear:/bin/bash
</pre>

118 submissions across two classes.  The answers:
* (MD5) jackbear:Everyb0dyKnow$My$ecret => 8 students cracked this
* (MD5) brotherbear:200368 => 115 students cracked this
* (MD5) fancybear:jeronimo => 114 students cracked this
* (MD5) barneybear:gxfzveko => 2 students cracked this
* (MD5) pandabear:chudy => 117 students cracked this
* (MD5) yogibear:IntrepidPursuits => 0 student cracked this
* (MD5) papabear:buggs => 117 students cracked this
* (MD5) grizzlybear:lovehurts => 113 students cracked this
* (SHA-512) sisterbear:jeremiah => 115 students cracked this
* (SHA-512) teddybear:1980-04-24 => 16 students cracked this
* (SHA-512) polarbear:Arthur1 => 112 students cracked this
* (SHA-512) bluebear:182365 => 53 students cracked this
* (SHA-512) blackbear:procaccio => 42 students cracked this
* (SHA-512) mamabear:I%8}JqoT6r{# => 0 student cracked this
* (SHA-512) carebear:4n7id370n47in6 => 35 students cracked this
* (SHA-512) cozybear:eminem123 => 100 students cracked this

The passwords barneybear, yogibear, bluebear, and mamabear were randomly generated; all other passwords were taken from wordlists, namely from [Daniel Miessler's SecLists](https://github.com/danielmiessler/SecLists).

To earn all 10 / 10 points for the lab, students had to crack 8 or more passwords.  The final distribution:

<pre>
13 (x5)
12 (x6)
11 (x10)
10 (x13)
9 (x28)
8 (x48)
7 (x3)
6 (x2)
5 (x2)
3 (x1)
</pre>

Methodologies and hauls from students:

> #### john crackme-fall2023.txt (default wordlist)
> papabear:buggs
> 
> brotherbear:200368
> 
> pandabear:chudy
> 
> #### john --wordlist=SecLists/Passwords/xato-net-10-million-passwords.txt crackme-fall2023.txt
> fancybear:jeronimo
> 
> grizzlybear:lovehurts
> 
> #### hashcat -m 1800 sha512.txt SecLists/Passwords/xato-net-10-million-passwords.txt -o cracked_sha512.txt
> polarbear:Arthur1
> 
> #### hashcat -m 1800 sha512.txt SecLists/Passwords/openwall.net-all.txt -o cracked_sha512.txt
> blackbear:procaccio
> 
> #### ./hashcat -m 1800 Other/sha512.txt Other/Passwords/Leaked-Databases/md5decryptor-uk.txt -o Other/cracked_sha512.txt
> 
> #### tried using the crazy hri lab computer
> cozybear:eminem123
> 
> sisterbear:jeremiah
> #### ./hashcat -m 1800 Other/sha512.txt Other/Passwords/Leaked-Databases/alleged-gmail-passwords.txt -o Other/cracked_sha512.txt
> bluebear:182365
> 
> carebear:4n7id370n47in6
> #### cat dblist.txt | xargs -I {} ./hashcat -m 1800 Other/sha512.txt {} -o Other/cracked_sha512.txt
> #### with dblist.txt containing Other/Passwords/mssql-passwords-nansh0u-guardicore.txt
> teddybear:1980-04-24
> #### cat dblist.txt | xargs -I {} ./hashcat -m 500 Other/md5.txt {} -o Other/cracked_md5.txt
> #### with dblist.txt containing Other/Passwords/scraped-JWT-secrets.txt
> jackbear:Everyb0dyKnow$My$ecret
<hr/>
> Used John the Ripper with these password lists:
> 
> https://github.com/danielmiessler/SecLists/blob/master/Passwords/Common-Credentials/10-million-password-list-top-100000.txt
> 
> https://crackstation.net/crackstation-wordlist-password-cracking-dictionary.htm
> 
> Used hashcat with the first list to get the second group passwords.
> 
> Used hashcat with lists from danielmiessler to get the third group, specifically openwall.net-all.txt, darkc0de.txt, and alleged-gmail-passwords.txt.
<hr/>
> I separated the password list into two files depending on the hash method depicted by $1$ or $6$ and then ran both files with the command john so it would use the default wordlist for all 6 of the username password pairs that it was able to crack.
> 
> bluebear:182365
> 
> papabear:buggs
> 
> brotherbear:200368
> 
> pandabear:chudy
> 
> sisterbear:jeremiah
> 
> polarbear:Arthur1
> 
> After using the default list, I also wanted to use this wordlist I got from SecLists on github under Common-credentials. These wordlists gave me three additional passwords:
> 
> cozybear:eminem123
> 
> fancybear:jeronimo
> 
> grizzlybear:lovehurts

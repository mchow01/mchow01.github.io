---
layout: post
title:  "Results of a Password Cracking Contest in My Security Class (Fall 2018)"
date:   2018-11-10 12:00:00
categories: education security
---

Each time I teach my Security class, I give a month-long lab to crack as many passwords as possible.  For this fall's contest [(opened on October 7, 2018](https://twitter.com/0xmchow/status/1049064581073707008)), I used three different hash types: NTLM, MD5, and SHA-512.  The password hashes (16 total):

<pre>
yogibear:$1$4mcBroGf$v8ApneilDTE18VgvWDBiE.:1003:1003:,,,:/home/yogibear:/bin/bash
bigbear:$1$wxHHsG3L$aHlS./vEc/PEerbNGTWFI1:1004:1004:,,,:/home/bigbear:/bin/bash
grizzlybear:$1$erDsB6Qw$CtTm7jozAV51faPrtbQzL/:1005:1005:,,,:/home/grizzlybear:/bin/bash
pandabear:$1$eFeGh1B.$ysteI0kbYwHAaJYg7gPyo/:1006:1006:,,,:/home/pandabear:/bin/bash
yolandabear:$1$QZGinKKl$mjiuTcAIdf6bfxMKTTkNw.:1007:1007:,,,:/home/yolandabear:/bin/bash
fancybear:$1$RgXw6iaq$PNNEqOsiIMKxLSOHvmkK51:1008:1008:,,,:/home/fancybear:/bin/bash
jojobear:$1$9YPIeyVm$jygTtWr33r.eY..C5JD/31:1009:1009:,,,:/home/jojobear:/bin/bash
smokeybear:$6$FYh4KT1Z$AVDRWEyvasw1xbOO6nrPYJOdVsXYMU58XOrQeXwi8Qts2tGmPwf8HQbJC0qE659iJI0ykiIFX6UUsYm9m/hdj.:1000:1000:,,,:/home/smokeybear:/bin/bash
cocobear:$6$9q3u2Fux$WqZ9V6RQ6w7GNfzedbe1cEnVm3b.XAuZEi8uLDuBoYVsH7Cf3/9M8IkQziuFRnZ/hbcC1JG/1MLyy7NGPxi5A.:1001:1001:,,,:/home/cocobear:/bin/bash
yetibear:$6$/.446T8c$OTqZH8903n6LhUBKpVNtIQQf.so0EprZAym1IUeOLVsZKPMBwb5OgGeLkhJ4xKWLavFrhhuq5N1OEyCFrig.F.:1002:1002:,,,:/home/yetibear:/bin/bash
blackbear:$6$vLklyaUy$HavS8mKYsF0v8Om2XzcqPdwhwywQCzlUp6ZAq3INu9ejYik9BOj9/yzsPTMPy5SniYeWWVrIctg9pVnqdoTxG/:1003:1003:,,,:/home/blackbear:/bin/bash
fozziebear:$6$pT7CDuxB$hpm1p.8c4Q9.dXtljrLhWZ.i4kc2TA5G9xGR.v0RBdJKVz7E9p9esZZjN8Ng6SjlMLPTI7L86o7iXixn2.uYy/:1004:1004:,,,:/home/fozziebear:/bin/bash
pedrobear:$6$uOhp6Hr0$lIZE8oXgf67eZkYNj8VGM1wpbjCiL6xEvuv6rmXweYM/faFKYyRBxW7Dc1X7vgEiNiX3uwfy7HPHBB/wCWNXE0:1005:1005:,,,:/home/pedrobear:/bin/bash
chicagobear:1009:aad3b435b51404eeaad3b435b51404ee:cb8538754ecafad5d2ae67ecc709f459:::
cozybear:1008:aad3b435b51404eeaad3b435b51404ee:8c5f236d8d0e37ef9dc1d827044d0ad5:::
teddybear:1010:aad3b435b51404eeaad3b435b51404ee:c55da69af31a31d7d8e0773c368f0da8:::
</pre>

65 total submissions.  The answers:

* (MD5) yogibear:L1verpool! => 11 students cracked this
* (MD5) bigbear:unbelievable => 60 students cracked this
* (MD5) grizzlybear:zxcasdqwe123 => 56 students cracked this
* (MD5) pandabear:vulmjz => 7 students cracked this
* (MD5) yolandabear:kx7yy4 => 5 students cracked this
* (MD5) fancybear:sx708n => 7 students cracked this
* (MD5) jojobear:wmOhL3u4J => 0 students cracked this
* (SHA512) smokeybear:asdf => 60 students cracked this
* (SHA512) cocobear:meatball => 60 students cracked this
* (SHA512) yetibear:06mulesystems => 8 students cracked this
* (SHA512) blackbear:mzpixl => 3 students cracked this
* (SHA512) fozziebear:320299 => 18 students cracked this
* (SHA512) pedrobear:R6iLFUgG => 0 students cracked this
* (NTLM) cozybear:doofus => 62 students cracked this
* (NTLM) chicagobear:ihateyou => 62 students cracked this
* (NTLM) teddybear:w7zbyt => 45 students cracked this


To earn all 10 points for the lab, students had to crack 6 passwords.  The final distribution:

<pre>
14 14
12 12
11
9 9 9 9
8 8 8 8 8 8 8 8 8 8 8
7 7 7 7 7 7 7 7 7 7 7 7 7 7 7 7 7 7 7 7
6 6 6 6 6 6 6 6 6 6 6 6 6 6 6 6 6 6 6 6
5 5
3
2 2
</pre>

The winners (tied) cracked 14 of the 16 passwords.

Student 1's haul and methodology:
<pre>
pandabear : vulmjz               -> 10milliontop1000000
bigbear : unbelievable          -> 10milliontop1000000
yolandabear : kx7yy4           -> bruteforce 6 char
grizzlybear : zxcasdqwe123 -> 10milliontop1000000
fancybear : sx708n               -> bruteforce 6 char
yogibear : L1verpool!            -> rockyou + best64 aws
jojobear : ???

sha512:
smokeybear : asdf            -> 10milliontop1000000
cocobear : meatball          -> 10millinotop1000000
yetibear : 06mulesystems -> masterlist.txt google cloud
blackbear : mzpixl             -> bruteforce 6 char
fozziebear : 320299          -> lookup service
pedrobear : ???


NTLM:
teddybear : w7zbyt        -> 10milliontop1000000 + ORTRTA
cozybear : doofus          -> same
chicagobear : ihateyou  -> same
</pre>

Student 2's haul:

<pre>
yogibear:L1verpool!
bigbear:unbelievable
grizzlybear:zxcasdqwe123
pandabear:vulmjz
yolandabear:kx7yy4
fancybear:sx708n
smokeybear:asdf
cocobear:meatball
yetibear:06mulesystems
blackbear:mzpixl
fozziebear:320299
chicagobear:ihateyou
cozybear:doofus
teddybear:w7zbyt
</pre>

Student 2's methodology:

>To crack the majority of the passwords I've completed so far, I used John the Ripper and Hashcat. I began by using a series of wordlists on both the MD5 and SHA512 passwords, which I divided into two separate files consisting of only passwords hashed with the respective algorithms. To this point, I've used a scattering of the wordlists from the `Seclists/Leaked-Databases` folder, and have had the most success with `rockyou.txt`. Using `rockyou.txt`, I cracked two of the MD5 hashes and three of the SHA512 hashes.

> I then applied a series of different rules to some of these wordlists, for both MD5 and SHA512 hashed passwords. For the SHA512 passwords, I have been using my computer at home (with a decent graphics card) to speed up the process. Using these rules, and Hashcat which I've found to be a better option for GPU cracking, I cracked another of the MD5 hashed passwords.

> After using a number of wordlists with a collection of different rules, I turned to brute force incremental cracking, as well as Hashcat's mask attack. Using these two brute force methods, I've cracked another three MD5 hashes, and one SHA512 hash.

> For the NTLM passwords, I ran JtR (John the Ripper) with the default settings to crack two of the hashes. I considered using wordlists with rules to crack the remaining NTLM password, but ended up using a site (hashkiller.co.uk/ntlm-decrypter.aspx) with a huge number of computed NTLM hashes (since I noticed that these hashes weren't salted) to crack this one.
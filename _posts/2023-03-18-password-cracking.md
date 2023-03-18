---
layout: post
title:  "Results of a Password Cracking Contest in My Security Class (Spring 2023)"
date:   2023-03-18 14:45:00
categories: education security
---

Each time I teach my Security class, I give a month-long lab to crack as many passwords as possible.  For this spring's contest (opened on February 14, 2023), I used two different hash types: MD5 and SHA-512.  The contest closed on March 17th at 11:59 PM PDT.  The password hashes (16 total):

<pre>
jackbear:$1$IcEtJQLA$XdgWze34ESFTawKK9tGAY0:1001:1001:,,,:/home/jackbear:/bin/bash
brotherbear:$1$Kz02BU4B$Xua6prBBt/JmR0d76yrHH0:1002:1002:,,,:/home/brotherbear:/bin/bash
fancybear:$1$U0fph1lm$Xls6U5H/YOHO/GJupuhrn1:1003:1003:,,,:/home/fancybear:/bin/bash
barneybear:$1$h6pwSfzU$AobJuVh3VYtwWV289Wxk51:1004:1004:,,,:/home/barneybear:/bin/bash
pandabear:$1$/Ais4vWf$/EjRTcWCsPiFJJ0QkGyDS1:1005:1005:,,,:/home/pandabear:/bin/bash
yogibear:$1$1PxK.b6G$wtdQK4JG0QU56fVsKPaGI/:1006:1006:,,,:/home/yogibear:/bin/bash
papabear:$1$YdqJuNhq$6aALThxA8LGvxgbkr8ZdK/:1007:1007:,,,:/home/papabear:/bin/bash
grizzlybear:$1$jqiumZSN$KuuoYt1lVMmAdf7gTLVgv1:1008:1008:,,,:/home/grizzlybear:/bin/bash
sisterbear:$6$q/wSa3rMUvB5tzJp$Pl2o08j6WdAMvhuhNH4A/6r/hT.Acfknwc1PPxmhSOmwGTcXZe/Sys012nmB71RlVh8EKaTruxsn0EcsNn5sW/:1009:1009:,,,:/home/sisterbear:/bin/bash
teddybear:$6$X5Ce3ITEGJDqhMqo$p5ayq6iPb7L8MW7d29EcgzERW4iQuYnjr.pJYFDcmcZgiVsY/4mICp/vODmQDuo9Q5iC.pEqJ7jfNgjkXf0841:1010:1010:,,,:/home/teddybear:/bin/bash
polarbear:$6$jO1g29ts5kmX/E0S$UvACOjug75rHOJo8M1ztYCGcu7IRPlflOc5pn2AqogN2szqYQZDm3EqKKgzHLrOgMmClp6A.6o.FVDGz648Yk1:1011:1011:,,,:/home/polarbear:/bin/bash
bluebear:$6$h4J3yEUEoXFVF/tv$dOlENVF2W7QPCM4MsNjWhKqvQTxHohEeIkM/hKdeIHUHAJ5jQlHg0b.rnNnpTMnpCmJh5Ht5KhnQTXw0DkuYG1:1012:1012:,,,:/home/bluebear:/bin/bash
blackbear:$6$vR.Gz.7c2cvQiH6h$dO9P7JIoA8h24OUAtmWrY22H15hWP.nQekExIoTRyny.WTPAWj3xJQtsIIOioRq21vwgJs783Ia1f3/NNY7Yl.:1013:1013:,,,:/home/blackbear:/bin/bash
mamabear:$6$T8E/8po9NpVWhQXM$mn7dmU58gb3px4ZzyrSZAV.TedUmOZ0E.Jz/j.OBoUYemEPqOQ/0TpekA9g1S81XsHCv6WUhMlaEDj529eAiW/:1014:1014:,,,:/home/mamabear:/bin/bash
carebear:$6$/AMYXRQamucYUdHi$/1TTplaDDqonMnIEvA1Ef2TtiKWzwBEz/djdSPNEMEZ0heeXx8GYLiMh7iy2Vj3U.a60k9YSihavzcv.44wuw.:1015:1015:,,,:/home/carebear:/bin/bash
cozybear:$6$uODP9Vj9DvBEyz5G$GGUSWwlA8EX.eqaKcZEiMiYJboEcC2pj.bPsa9AMbyHV4dnot8WbAYv1aEIBpjeEEPYpel34z0sSACkTJU8Ci1:1016:1016:,,,:/home/cozybear:/bin/bash
</pre>

99 submissions across two classes.  The answers:
* (MD5) jackbear:gatito => 98 students cracked this
* (MD5) brotherbear:vovddo => 17 students cracked this
* (MD5) fancybear:zhangping123 => 96 students cracked this
* (MD5) barneybear:JfeE1wcDCv => 0 student cracked this
* (MD5) pandabear:Sprin9123# => 26 students cracked this
* (MD5) yogibear:ybju455mvrhtkj6 => 95 students cracked this
* (MD5) papabear:67347064 => 12 students cracked this
* (MD5) grizzlybear:n_J_A-S5ObA= => 0 students cracked this
* (SHA-512) sisterbear:lighthouse => 91 students cracked this
* (SHA-512) teddybear:peru12 => 87 students cracked this
* (SHA-512) polarbear:o2nDSzPVr7?y => 0 student cracked this
* (SHA-512) bluebear:88888888 => 91 students cracked this
* (SHA-512) blackbear:cjkywt => 87 students cracked this
* (SHA-512) mamabear:rfpwtz => 2 students cracked this
* (SHA-512) carebear:2004.03.26 => 16 students cracked this
* (SHA-512) cozybear:travis => 91 students cracked this

The passwords for brotherbear, barneybear, papabear, grizzlybear, polarbear, and mamabear were randomly generated; all other passwords were taken from wordlists.

To earn all 10 / 10 points for the lab, students had to crack 8 or more passwords.  The final distribution:

<pre>
13 (x2)
12 (x2)
11 (x4)
10 (x6)
9 (x15)
8 (x60)
7 (x2)
4 (x4)
3 (x2)
2 (x2)
</pre>

The methodology and haul from students:

<pre>
I first randomly picked one word list from github which called
rockyou.txt and test it on jackbear, this is the pair of
username:password I got:

jackbear:gatito

Then, I tried to run John the Ripper with same wordlist on other
usernames, they failed. I realized I need other word list to find the
passwords. I first extracted all .txt file from passwords file in
SecLists GITHUB page
(https://github.com/danielmiessler/SecListshttps://github.com/danielmiessler/SecLists),
below is what I have now:


fancybear:zhangping123
pandabear:Sprin9123#
yogibear:ybju455mvrhtkj6
sisterbear:lighthouse
teddybear:peru12
bluebear:88888888
blackbear:cjkywt
cozybear:travis

For usernames below, I used weakpass_3a(141 GB) from weakpass.com
brotherbear:vovddo
papabear:67347064
carebear:2004.03.26
mamabear:rfpwtz

More usernames are still cracking now, the ETA for sha512 is 07/March which is crazy...
</pre>

<pre>
MD5:

jackbear:gatito:1001:1001:,,,:/home/jackbear:/bin/bash

brotherbear:vovddo:1002:1002:,,,:/home/brotherbear:/bin/bash

fancybear:zhangping123:1003:1003:,,,:/home/fancybear:/bin/bash

pandabear:Sprin9123#:1005:1005:,,,:/home/pandabear:/bin/bash

yogibear:ybju455mvrhtkj6:1006:1006:,,,:/home/yogibear:/bin/bash

papabear:67347064:1007:1007:,,,:/home/papabear:/bin/bash



SHA512:
sisterbear:lighthouse:1009:1009:,,,:/home/sisterbear:/bin/bash

teddybear:peru12:1010:1010:,,,:/home/teddybear:/bin/bash

bluebear:88888888:1012:1012:,,,:/home/bluebear:/bin/bash

blackbear:cjkywt:1013:1013:,,,:/home/blackbear:/bin/bash

carebear:2004.03.26:1015:1015:,,,:/home/carebear:/bin/bash

cozybear:travis:1016:1016:,,,:/home/cozybear:/bin/bash


Compiled unique wordlists from SecLists with bash/zsh commands for
dictionary attacks with JohnTheRipper.  Used hashcat with an RTX3080ti
to brute force lower-case hashes incrementally (length<=6) for
brotherbear.  Used hashcat for dictionary attacks with
cyclone.hashesorg.hashkiller combined and crackstation wordlists,
among others for blackbear.  I also tried using (without success): (1)
mask attacks with smaller keyspaces like strings containing only
upper/lower/numeric characters.  (2) using a simple set of rules with
smaller word-lists to cover more ground.  </pre>

<pre>
I ran the command “john –wordlist=/usr/share/john/password.lst
–format=crypt hash.txt” using john the ripper and it cracked these
four passwords:

 

jackbear:gatito 

brotherbear:vovddo

bluebear:88888888

cozybear:travis

I ran the command “john –wordlist=pass.txt –format=crypt hash.txt”
 where pass.txt is a file I downloaded from SecLists on github
 “xato-net-10-million-passwords-10000000.txt” which cracked 2 more
 passwords.

 

sisterbear:lighthouse

blackbear:cjkywt

 
I ran the command “john –wordlist=new.txt –format=crypt hash.txt”
where new.txt contained several of the smaller text files from
SecLists which cracked 2 passwords:

 

pandabear:Sprin9123#

carebear:2004.03.26

 

I ran the command “john –wordlist=xato-net-10-million-passwords.txt
–format=crypt hash.txt” which cracked 3 passwords:

 

teddybear:peru12

fancybear:zhangping123

yogibear:ybju455mvrhtkj6

</pre>

<pre>
After splitting the crackme file into two files (for the 2 different
hashes), I ran the files using the standard Jack the ripper wordlist
(aborting the session once the program was done with the
wordlist). From this first method, I cracked the first 3 passwords
seen below. I then ran the program with many other wordlists from the
GitHub repository discussed in class and found success with the
english dictionary, darkweb top 10000, seasons, xato, and mssql word
lists.

 

jackbear:gatito

bluebear:88888888

cozybear:travis

sisterbear:lighthouse

blackbear:cjkywt 

pandabear:Sprin9123#

fancybear:zhangping123

yogibear:ybju455mvrhtkj6

teddybear:peru12

carebear:2004.03.26
</pre>

<pre>
## Round 1

Running Hashcat with a dictionary attack to crack MD5 hashed and
salted Linux passwords using the xato.net 10 million password list.
Source:
https://xato.net/today-i-am-releasing-ten-million-passwords-b6278bbe7495
Source: https://github.com/danielmiessler/SecLists/ ``` hashcat -m 500
-a 0 md5.salt.hash
SecLists/Passwords/xato-net-10-million-passwords.txt --force ...
$1$IcEtJQLA$XdgWze34ESFTawKK9tGAY0:gatito
$1$U0fph1lm$Xls6U5H/YOHO/GJupuhrn1:zhangping123
$1$1PxK.b6G$wtdQK4JG0QU56fVsKPaGI/:ybju455mvrhtkj6 ```

## Round 2

Running Hashcat with a dictionary attack to crack SHA512 hashed and
salted Linux passwords using the xato.net 10 million password list.
``` hashcat -m 1800 -a 0 sha512.salt.hash
SecLists/Passwords/xato-net-10-million-passwords.txt --force ...
$6$h4J3yEUEoXFVF/tv$dOlENVF2W7QPCM4MsNjWhKqvQTxHohEeIkM/hKdeIHUHAJ5jQlHg0b.rnNnpTMnpCmJh5Ht5KhnQTXw0DkuYG1:88888888
$6$uODP9Vj9DvBEyz5G$GGUSWwlA8EX.eqaKcZEiMiYJboEcC2pj.bPsa9AMbyHV4dnot8WbAYv1aEIBpjeEEPYpel34z0sSACkTJU8Ci1:travis
$6$vR.Gz.7c2cvQiH6h$dO9P7JIoA8h24OUAtmWrY22H15hWP.nQekExIoTRyny.WTPAWj3xJQtsIIOioRq21vwgJs783Ia1f3/NNY7Yl.:cjkywt
$6$q/wSa3rMUvB5tzJp$Pl2o08j6WdAMvhuhNH4A/6r/hT.Acfknwc1PPxmhSOmwGTcXZe/Sys012nmB71RlVh8EKaTruxsn0EcsNn5sW/:lighthouse
$6$X5Ce3ITEGJDqhMqo$p5ayq6iPb7L8MW7d29EcgzERW4iQuYnjr.pJYFDcmcZgiVsY/4mICp/vODmQDuo9Q5iC.pEqJ7jfNgjkXf0841:peru12
```

## Round 3

What's left of the low hanging fruit: running Hashcat dictionary
attacks (MD5) against the remaining passwords in
SecLists/Passwords/*.txt.

```
$1$/Ais4vWf$/EjRTcWCsPiFJJ0QkGyDS1:Sprin9123#
```

## Round 4

Brute force the remaining 4 MD5 hashes with a default Hashcat mask
attack. Still running, but may as well update.  ``` hashcat -m 500 -a
3 md5.salt.hash.3 ...  $1$Kz02BU4B$Xua6prBBt/JmR0d76yrHH0:vovddo ```

## Round 5
``` hashcat -a 3 ./md5.salt.hash.4 ?d?d?d?d?d?d?d?d?d?d --increment
 --increment-min=6 ...  $1$YdqJuNhq$6aALThxA8LGvxgbkr8ZdK/:67347064
 ```

jackbear:gatito
brotherbear:vovddo
fancybear:zhangping123
barneybear:
pandabear:Sprin9123#
yogibear:ybju455mvrhtkj6
papabear:67347064
grizzlybear:
sisterbear:lighthouse
teddybear:peru12
polarbear:
bluebear:88888888
blackbear:cjkywt
mamabear:
carebear:
cozybear:travis
</pre>

<pre>
(John the Ripper, wordlist=None, local)

1. jackbear:gatito

2. bluebear:88888888

3. cozybear:travis

 

(John the Ripper, wordlist=darkweb-top10000, vm)

4. blackbear:cjkywt

5. sisterbear:lighthouse

 

(John the Ripper, wordlist=seasons, local)

6. pandabear:Sprin9123#

 

(John the Ripper, wordlist=xato-net-10-million-passwords-1000000, local)

7. fancybear:zhangping123     

8. yogibear:ybju455mvrhtkj6 

 

(John the Ripper, wordlist=rockyou, local)

9. teddybear:peru12

 

(Hashcat, brute force, local)

10. brotherbear:vovddo
</pre>
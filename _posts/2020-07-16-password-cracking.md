---
layout: post
title:  "Results of a Password Cracking Contest in My Security Class (Summer 2020)"
date:   2020-07-16 15:00:00
categories: education security
---

Each time I teach my Security class, I give a month-long lab to crack as many passwords as possible.  For this summer's contest [(opened on June 17th 2020)](https://twitter.com/0xmchow/status/1273361873212248064), I used three different hash types: NTLM, MD5, and SHA-512.  The closed on July 15th at 11:59 PM PDT.  The password hashes (17 total):

<pre>
papabear:$1$ru5P9ecg$e09eGufBAel8zvzdQxXLY/:1003:1003:,,,:/home/papabear:/bin/bash
bluebear:$1$hgOfHLcl$8susI6HDLxAYntPmr8J61.:1004:1004:,,,:/home/bluebear:/bin/bash
carebear:$1$ozN.6ZXx$IEoL2RhmIfl0OdF2qT6Hy/:1005:1005:,,,:/home/carebear:/bin/bash
polarbear:$1$AWX5fO6U$p2DmKsbyi7cMOONPcGvyW/:1006:1006:,,,:/home/polarbear:/bin/bash
sisterbear:$1$MxlwZUDN$tN1XRjJFciScHLVPlSZ72.:1007:1007:,,,:/home/sisterbear:/bin/bash
barneybear:$1$El6K43LF$Sj68MKn8mw5xvXSWlsHvP.:1008:1008:,,,:/home/barneybear:/bin/bash
grizzlybear:$1$N8tFNENQ$WdPSIKHswrZp53M/d5ZB1.:1009:1009:,,,:/home/grizzlybear:/bin/bash
mamabear:$6$AuuanIfjpTZdGgaE$MF8vAP3M7QvCEwhWkM3CuFPrdcVZjOj/CLPCv60aEEcu5YklxK26uEIWbXS9N.aNB6zj5hGnQAn6SarOGcAHK.:1001:1002:,,,:/home/mamabear:/bin/bash
brotherbear:$6$HfmniBwBYXXD2pdh$myjjzKGrVFJye8xzn562tKBzJaIQYPS52/BUlKZ6mZjWwnB5R0P7Ra0Qum9y9cGWpvaNS3thPOecmyT4NxX7t/:1002:1003:,,,:/home/brotherbear:/bin/bash
jackbear:$6$dn/BqTXaD8CBAUxP$QU5XeJSQe7F4Q/ID57GfWphTgGQFccUxicW86rRsWaSfIMc8jqvlIlxW2AK0c6sF6OG7ZN0v3VCbvZGr1h3sZ0:1003:1004:,,,:/home/jackbear:/bin/bash
pandabear:$6$03WWmSuqOzO5A3ER$0mnH04hZauUxWRY6lrJl1.2YOS0CYuIX9ClEJ1TFdtW42wPFPITLGVYuRujmtay9cybzeD6ovkdTpnLQmYDvf0:1004:1005:,,,:/home/pandabear:/bin/bash
cozybear:$6$lTQpNeV9Bha/SPu1$OZGJNgiz53Wk16YkWHrZ3hQXiLvX0gIldmAVgWyiTDYs.mRh3djgR49qoJgmJY0Ec.OfO2lVziCV8CY8YkCA9/:1005:1006:,,,:/home/cozybear:/bin/bash
fancybear:$6$DEYIB7FvRWSuBCUv$mAqOB9sKP7fXvjoIBw79zQpkaPpKW052Lm0c3N8vY65hycJz8kw6UuwQIjfkMVXgK3GXwRPWnWtwoy8Tlegdj.:1006:1007:,,,:/home/fancybear:/bin/bash
teddybear:$6$Vd0Vf8mwyG/B8DJh$oKA7274ABgQNdlsjRQ427KhkiGBIO6utsvy6dOljbaQtj2RJd2TWzPkItPKEgWRETxZ.kfqYlqwsRgbgNdSvD.:1007:1008:,,,:/home/teddybear:/bin/bash
blackbear:1002:aad3b435b51404eeaad3b435b51404ee:7894fe6795902d147063fff07a7ac3df:::
cindybear:1001:aad3b435b51404eeaad3b435b51404ee:878d8014606cda29677a44efa1353fc7:::
yogibear:1003:aad3b435b51404eeaad3b435b51404ee:e895fe48cf59700c902f2cb49f86f767:::
</pre>

14 submissions.  The answers:
* (MD5) papabear:Pan-orthodox => 4 students cracked this
* (MD5) bluebear:LUJAN => 13 students cracked this
* (MD5) carebear:bottelborsel => 5 students cracked this
* (MD5) polarbear:59262 => 8 students cracked this
* (MD5) sisterbear:VTPtQu => 0 student cracked this
* (MD5) barneybear:3oswE73dkb => 0 student cracked this
* (MD5) grizzlybear:e<kDWp@x => 0 student cracked this
* (SHA512) mamabear:ster56 => 10 students cracked this
* (SHA512) brotherbear:eater => 10 students cracked this
* (SHA512) jackbear:193838 => 10 students cracked this
* (SHA512) pandabear:become55 => 5 students cracked this
* (SHA512) cozybear:zjhag7 => 0 student cracked this
* (SHA512) fancybear:.PVVhH.=eLJGpP6 => 0 student cracked this
* (SHA512) teddybear:aoJr0.2*Gf => 0 student cracked this
* (NTLM) cindybear:secret => 4 students cracked this
* (NTLM) blackbear:VSndaLOa => 0 student cracked this
* (NTLM) yogibear:;iX;?9LLoAR)8lfQ => 0 student cracked this

To earn all 10 / 10 points for the lab, students had to crack 6 or more passwords.  The final distribution:

<pre>
9 (1 total)
7 (2 total)
6 (4 total)
5 (2 total)
4 (2 total)
2 (2 total)
0 (1 total)
</pre>

The winner cracked 9 of the 17 passwords.

Winner's haul:

>Username: mamabear Password: ster56
>Username: polarbear Password: 59262
>Username: brotherbear Password: eater
>Username: bluebear Password: LUJAN
>Username: carebear Password: bottelborsel
>Username: papabear Password: Pan-orthodox
>Username: jackbear Password: 193838
>Username: pandabear Password: become55
>Username: cindybear Password: secret

Strategies used by students who cracked 6 or more passwords:

>pandabear:become55
>Method: Password wordlist taken from Daniel Miessler’s 10 million password list on github and used John the Ripper wordlist method of cracking the password
>Jackbear:193838
>Method: Password wordlist taken from Daniel Miessler’s 10 million password list on github and used John the Ripper wordlist method of cracking the password
>brotherbear:eater
>Method: Password wordlist taken from Daniel Miessler’s 10 million password list on github and used John the Ripper wordlist method of cracking the password
>Mamabear:ster56
>Method: Password wordlist taken from Daniel Miessler’s 10 million password list on github and used John the Ripper wordlist method of cracking the password
>polarbear:59262
>Method: Password wordlist taken from Daniel Miessler’s 10 million password list on github and used hashcat with straight attack with the combinator rule.
>bluebear:LUJAN
>Method: Password wordlist taken from Daniel Miessler’s 10 million password list on github and used hashcat with straight attack with the combinator rule.

>The cracking methodology that I used was to combine each directory section of the SecLists/Passwords wordlists into a single text file, which resulted in 10 distinct text files. I had separated the hashes into distinct hash files and then ran through JtR. From this, I was able to crack 10 passwords.

>Solutions obtained by running hashcat on the md5 passwords with my laptop using the 15GB crackstation wordlist and then John on the Tufts cluster using the rockyou wordlist with the Jumbo rules for the SHA512 ones.

>I used John the ripper to crack all passwords. I used CPU and some took a few days to get 0 or 1 result. The wordlist I used is rockyou to crack 1 MD5 password and 1 SHA512 password. The rest is cracked by brute force.

>I started running john on a computer at home at the start of the assignment but it turned out to be slower than expected and only made it through the first two passwords (polarbear/bluebear). About a week ago, I set up an Azure instance that cracked more passwords (mamabear/brotherbear/jackbear/pandabear), and I'll check it again tomorrow to see what else it got. I had hoped to get a VM up and running sooner on AWS/Google Cloud, but my credits expired so that unfortunately wasn't an option anymore.
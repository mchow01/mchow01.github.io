---
layout: post
title:  "Results of a Password Cracking Contest in My Security Class (Fall 2025)"
date:   2025-11-01 14:30:00
categories: education security
---

Each semester in my Security class, I give a month-long lab to crack as many passwords as possible.  For this fall's contest (opened on September 30th), I used two different hash types: MD5 and SHA-512.  The contest closed on October 31st at 11:59 PM PDT.  The password hashes (16 total):

<pre>
sisterbear:$1$iEcFTL6M$RTumDIDmychTYRHJ.ygEq1:1001:1001:,,,:/home/sisterbear:/bin/bash
grizzlybear:$1$88X4UZvI$SCbsi8PonbB.gGWu91Y8./:1002:1002:,,,:/home/grizzlybear:/bin/bash
jackbear:$1$HO4DbQAJ$RGrox1qHrg3g7S.qrVTZH.:1003:1003:,,,:/home/jackbear:/bin/bash
pandabear:$1$vuh8yquQ$A4hX.A8etK8UprPyBYx5i0:1004:104:,,,:/home/pandabear:/bin/bash
yogibear:$1$gpmCs1g1$tuCYH.O1sS8fUi0n.9xiq/:1005:1005:,,,:/home/yogibear:/bin/bash
mamabear:$1$XOLx.YW2$3XBm98bNuNC9waeddr0.F0:1006:1006:,,,:/home/mamabear:/bin/bash
barneybear:$1$tp.mBH3K$M41MknsTQWGIPhFGFsqOX.:1007:1007:,,,:/home/barneybear:/bin/bash
papabear:$1$Azr7Lpdk$piLgBgI1P2fYLQaIUrEyQ.:1008:1008:,,,:/home/papabear:/bin/bash
bluebear:$6$d55w24qGVlMBQJG/$rEXS8UcATtRlNY98eAeRh3NIs/R7sIitBQE70RGZ3tHQb3fyTfLBu3YsAff4JxEgPOb5a.LhI5LKSQnRre4o0.:1009:1009:,,,:/home/bluebear:/bin/bash
cozybear:$6$FUMokUdAJ8FLxmlF$LJGYraYr.8S.c/WQvp6/W8nvgAtc016YAYy47uYBX1OB06Cp.oEGXPF4xBcB9RGUCA6o2Wb.WZXaTGMZfZ1ce0:1010:1010:,,,:/home/cozybear:/bin/bash
polarbear:$6$wAu4M5JUgPtBEzjH$ZAAl0Flf7Lh0kSPWoAh5xfH2CJUf/vkjir/mTrK2igFhFcIOe3kvcINwm6N9RNskdrIoNeRSkHbBpU2e5TgCU0:1011:1011:,,,:/home/polarbear:/bin/bash
teddybear:$6$zNXBz3PGsEtgzbUQ$Wln4SqgzSTm68o30WO2vxZjU7.1rk3nJyx4YciX.MjdWigZjL1qUEbIdUAC3laQQ46N.0vdcvsIR4wF6NATes0:1012:1012:,,,:/home/teddybear:/bin/bash
carebear:$6$Jycq90RjBRn4DvCm$lqvaxqhUBuwpTZz.ktF6CweYuqDatK/i2pOBdPv1eSY9g6J6pZ6DmgwIX/XKU8cjkJu/ZjyfoY0UTeFyzI7Yw0:1013:1013:,,,:/home/carebear:/bin/bash
blackbear:$6$nB/ImWwymEvwoP99$ekUYg8X9hs584aC/KgMPKQJPYScN64jw4OgolYpsfUDeJnCGxU/HypILLRq8jjeDf1k6bZ/HNTJfFMvunXaF0.:1014:1014:,,,:/home/blackbear:/bin/bash
fancybear:$6$Q0iz1ANEuRFprN7B$m7Z62ExHMP1SPk2abUMBUcE2y642zS4bH5vZnMA3/quKoh5TM.6JUZYVM98Ezi7BbQRu0hg4D6AAsyyQpKFoL.:1015:1015:,,,:/home/fancybear:/bin/bash
brotherbear:$6$Ll02FrqPcpTww5OX$s468xQQbQUwdIxHZLO2yN7IwvyRgzE7rzA6DoAFudBJOJLGYZIcvuwYvLZynMMCCTCjvbj2xX5HU8SJV9X/Z..:1016:1016:,,,:/home/brotherbear:/bin/bash
</pre>
110 submissions across two classes.  The answers:

* (MD5) sisterbear:99B4D7p => 89 students cracked this
* (MD5) grizzlybear:tranquillizzeranno => 47 students cracked this
* (MD5) jackbear:addoglio => 97 students cracked this
* (MD5) pandabear:south1 => 109 students cracked this
* (MD5) yogibear:ujvhtw => 33 students cracked this
* (MD5) mamabear:7t4#E8eh$WZ%cvHo@Wt => 0 student cracked this 😛
* (MD5) barneybear:xx134113 => 80 students cracked this
* (MD5) papabear:pumbaa1 => 101 students cracked this
* (SHA-512) bluebear:Exigen => 97 students cracked this
* (SHA-512) cozybear:W7N2ix => 64 students cracked this
* (SHA-512) polarbear:vgjzlVWE => 0 student cracked this 😛
* (SHA-512) teddybear:Z0h412i73 => 90 students cracked this
* (SHA-512) carebear:L!verpool => 25 students cracked this
* (SHA-512) blackbear:C<&~DipE;}<[0=h=@y => 0 student cracked this 😛
* (SHA-512) fancybear:321304 => 84 students cracked this
* (SHA-512) brotherbear:meant2be => 98 students cracked this

To earn all 10 / 10 points for the lab, students had to crack 10 or more passwords.  The final distribution:

<pre>
13 (x1)
12 (x10)
11 (x21)
10 (x54)
9 (x3)
8 (x2)
7 (x5)
6 (x1)
4 (x3)
3 (x1)
2 (x3)
1 (x5)
0 (x1)
</pre>

Average number of passwords cracked: 9.218181818

Median number of passwords cracked: 10

How I created this fall's password cracking contest:
* sisterbear's password => taken from `xato-net-10-million-passwords-10000.txt` in Daniel Miessler's SecLists
* grizzlybear's password => taken from `darkc0de.txt` in Daniel Miessler's SecLists
* jackbear's password => taken from `darkc0de.txt` in Daniel Miessler's SecLists
* pandabear's password => taken from `darkweb2017-top10000.txt` in Daniel Miessler's SecLists
* yogibear's password => randomly generated using all [a-z]
* mamabear's password => randomly generated using all [a-zA-Z0-9!@#$%^&*()specialcharacters], less than 8 characters
* barneybear's password => taken from `NordVPN.txt` in Daniel Miessler's SecLists
* papabear's password => taken from `Ashley-Madison.txt` in Daniel Miessler's SecLists
* bluebear's password => taken from `xato-net-10-million-passwords-10000.txt` in Daniel Miessler's SecLists
* cozybear's password => taken from `md5decryptor-uk.txt` in Daniel Miessler's SecLists
* polarbear's password => => randomly generated using all [a-zA-Z], less than 8 characters
* teddybear's password => taken from `darkc0de.txt` in Daniel Miessler's SecLists
* carebear's password => It is no secret I am not a Liverpool fan
* blackbear's password => randomly generated using all [a-zA-Z0-9!@#$%^&*()specialcharacters]
* fancybear's password => randomly generated using all [0-9], length 8
* brotherbear's password => taken from `milw0rm-dictionary.txt` in Daniel Miessler's SecLists

Selected methodologies and hauls from students:

> Initially, I downloaded individual wordlists from
> `github.com/danielmiessler/SecLists/tree/master/Passwords` and ran
> John the Ripper on each one individually. This yielded a few
> passwords, but I knew I needed to use a larger wordlist. To this end,
> I cloned Daniel Miessler's GitHub directory with all wordlists using
> `git clone
> git@github.com/danielmiessler/SecLists/tree/master/Passwords`. I then
> filtered out all of the wordlists, excluding README and config files,
> and combined them all into a single, master wordlist using `find
> seclists-master -type f -name "*.txt" -exec cat {} + >
> combined-wordlist.txt`. I then ran john the ripper on this wordlist
> with the combined shadow file (both algorithms). This took too long,
> so I then manually separated the shadow file into two files, one with
> MD5-hashed passwords and one with SHA512-hashed passwords. Finally, I
> ran hashcat and john the ripper concurrently on each shadow file using
> the master wordlist.

> The first few were found using hashcat on rockyou, darkc0de,
> xato-net-10-million-passwords-10000 from SecLists. Then I ended up
> running almost all .txt files in SecLists and
> weakpass_4a.txt. yogibear was found by brute forcing A-Za-Z passwords
> under 8 characters

> Password Cracking Methodology: I used John the Ripper to crack all the
> passwords I found. I first separated the hashes into two files by hash
> type. My initial methodology was to call Jack the Ripper on the hash
> files with it's default word list. (command ex: john crackme-md5.txt
> ). Then I started calling John using individual wordlist text files
> from the Seclists GitHub repository
> (ie. danielmiessler/Seclists/Passwords) for the hash files (command ex
> john --wordlist=darkc0de.txt crackme-md5.txt). To systemize and speed
> up the process I used a bash script to run John The Ripper with each
> text file (word list) in a specified folder for both hash files.

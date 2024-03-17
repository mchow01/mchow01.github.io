---
layout: post
title:  "Results of a Password Cracking Contest in My Security Class (Spring 2024)"
date:   2024-03-16 22:30:00
categories: education security
---

Each time I teach my Security class, I give a month-long lab to crack as many passwords as possible.  For this spring's contest (opened on February 13, 2024), I used two different hash types: MD5 and SHA-512.  The contest closed on March 15th at 11:59 PM PDT.  The password hashes (16 total):

<pre>
jackbear:$1$BGVAnquQ$CB3xkCCex9KYoBLpIzfKO.:1001:1001:,,,:/home/jackbear:/bin/bash
barneybear:$1$OoI8Gjdp$HVZ30fBr92pUZlmJ24XJU0:1002:1002:,,,:/home/barneybear:/bin/bash
teddybear:$1$aT6RQywT$AAbeQ/FvaaLIV.kENTQcA.:1003:1003:,,,:/home/teddybear:/bin/bash
yogibear:$1$1j/LPdi9$it6s0c5XwILlgyg76FFPi/:1004:1004:,,,:/home/yogibear:/bin/bash
sisterbear:$1$.hnet9VI$gpizSxPrpDhWwCJCKggXF0:1005:1005:,,,:/home/sisterbear:/bin/bash
cozybear:$1$/aZIbtfM$7KJvymmIMjzCvtTSGvNrA1:1006:1006:,,,:/home/cozybear:/bin/bash
brotherbear:$1$TAQgSLW0$3YhU40/nln.VqwvdBUMd81:1007:1007:,,,:/home/brotherbear:/bin/bash
carebear:$1$l61DSWE0$yOKLn/jZn7UWlvdMvQgXR0:1008:1008:,,,:/home/carebear:/bin/bash

bluebear:$6$XcMHMb9zwWQ5AQuE$i1E3VYIf8KuRLUxQA1eWGPmgWOTlsReLZtwHbmpz/Hbp3zIxyR8nARhZXwfkXHhEnrrmKoaJA4kmACk0RNrRI/:1009:1009:,,,:/home/bluebear:/bin/bash
papabear:$6$HJRtNnBl1iucewsi$.yxuW2al1ijw15C92CxEIhBKL55yyw.TH3i/zWCFXbIqWlSXdjWe7MjMUAEcUwoLEidmCGhiet.cGyK/KOdst0:1010:1010:,,,:/home/papabear:/bin/bash
blackbear:$6$ObRBq.7idqguqcq8$kVHv6VTxsIH/FHlCLemyyr/YDpYPg262x9p.xgKEdZXDehxzmZv3DnYKdlFnFg2T66YflMLasmhXmxkaZpXBz.:1011:1011:,,,:/home/blackbear:/bin/bash
grizzlybear:$6$p3gbSlLd7JjIoAja$8RsK2eKmnKpE1CuUr1M1fSVo31EsG6ea9I3pjMehsqZp4kk9XwUrshYIh5SE8rOfE3uzqZasxWg4z3.QcJ7rQ/:1012:1012:,,,:/home/grizzlybear:/bin/bash
mamabear:$6$KQZ/ZVnM3FeyfIui$d09eSBXBTA1Who8H6W9WYHF1sh6Y6xjiILQOMwwGt5FssmJQ8v31j2PgXGhG50mmgOXV9L2OfiXaccJnhUUyz0:1013:1013:,,,:/home/mamabear:/bin/bash
pandabear:$6$jgC0GUdU1ZdhLG7D$fzQYiBeZK3xapOF/PXqks62Op3Q2.fEbxQSfIerx6a3sPcj4TW5OQ2VdRa.83ilfELMqhXaghjMf23d/UYh9Q.:1014:1014:,,,:/home/pandabear:/bin/bash
polarbear:$6$FHFLEVv/g0Cf13HB$guZIX/WJSozPB84FNaMo33OPb8KYjxwSriPOkl.62p7wtjPzH8Bd1zB2r0Q6iEyJssIqUb4rHbmFBRT3w/cOL.:1015:1015:,,,:/home/polarbear:/bin/bash
fancybear:$6$MMDvT/foLBfYO.6v$KcIpHBbg9DTS4X9wCllY.UoF23Mysxq.kEy2vYaYMvW8Dyjq3uK91.bNAZo7KGVi16aQ/lL38N0fIgHCr5DwU/:1016:1016:,,,:/home/fancybear:/bin/bash
</pre>

116 submissions across two classes.  The answers:
* (MD5) jackbear:speed-order => 104 students cracked this
* (MD5) barneybear:dha4 => 110 students cracked this
* (MD5) teddybear:ebrosg => 25 students cracked this
* (MD5) yogibear:Curtium => 110 students cracked this
* (MD5) sisterbear:Ne2Fw74C => 0 student cracked this
* (MD5) cozybear:500768 => 113 students cracked this
* (MD5) brotherbear:x8yJ82L44,F; => 0 student cracked this
* (MD5) carebear:rd2tgq7k => 102 students cracked this
* (SHA-512) bluebear:Stranger Things => 6 students cracked this # you know...
* (SHA-512) papabear:anthony => 114 students cracked this
* (SHA-512) blackbear:edQ%=2-6gJ50 => 0 student cracked this
* (SHA-512) grizzlybear:147852369 => 113 students cracked this
* (SHA-512) mamabear:765870 => 27 students cracked this
* (SHA-512) pandabear:Password21& => 40 students cracked this
* (SHA-512) polarbear:lustick => 62 students cracked this
* (SHA-512) fancybear:noycoafe => 71 students cracked this

To earn all 10 / 10 points for the lab, students had to crack 8 or more passwords.  The final distribution:

<pre>
13 (x5)
12 (x1)
11 (x8)
10 (x15)
9 (x22)
8 (x50)
7 (x8)
6 (x1)
5 (x3)
4 (x1)
2 (x1)
1 (x1)
</pre>

Average number of passwords cracked: 8.594827586

Median number of passwords cracked: 8

How I created this spring's password cracking contest:
* jackbear's password => taken from `bt4-password.txt` in Daniel Miessler's SecLists
* barneybear's password => taken from `darkc0de.txt` in Daniel Miessler's SecLists
* teddybear's password => randomly generated using all [a-z]
* yogibear's password => taken from `darkc0de.txt` in Daniel Miessler's SecLists
* sisterbear's password => randomly generated using all [a-zA-Z0-9!@#$%^&*()specialcharacters]
* cozybear's password => taken from `xato-net-10-million-passwords.txt` in Daniel Miessler's SecLists
* brotherbear's password => randomly generated using all [a-zA-Z0-9!@#$%^&*()specialcharacters]
* carebear's password => taken from `xato-net-10-million-passwords.txt` in Daniel Miessler's SecLists
* bluebear's password => not randomly generated, a special one for this semester
* papabear's password => taken from `darkweb2017-top1000.txt` in Daniel Miessler's SecLists
* blackbear's password => randomly generated using all [a-zA-Z0-9!@#$%^&*()specialcharacters]
* grizzlybear's password => taken from `darkweb2017-top1000.txt` in Daniel Miessler's SecLists
* mamabear's password => randomly generated using all [0-9]
* pandabear's password => taken from `common_corporate_passwords.lst` in Daniel Miessler's SecLists
* polarbear's password => taken from `openwall.net-all.txt` in Daniel Miessler's SecLists
* fancybear's password => taken from `xato-net-10-million-passwords.txt` in Daniel Miessler's SecLists

Selected methodologies and hauls from students:

>I used John the Ripper to crack each of these passwords. The first five on my list were cracked using the xato-net-10-million-passwords.txt wordlist found on Seclists. Papabear, grizzlybear, and fancybear were all cracked when I ran JtR with the SHA-512 encrypted password hashes, while carebear and cozybear were cracked when I ran JtR with the MD5 encrypted password hashes.  For the final three, I used the Ultimate2016 wordlist found on github (https://github.com/kennyn510/wpa2-wordlists/tree/master/Wordlists/Ultimate2016Links to an external site.). This wordlist was separated into separate files based on the starting letter of the words in the list, so I had to run JtR with each letter (the downloads for X, Y, and Z wouldn't work for some reason though. Website would freeze and stop responding). These final three were cracked when I ran JtR with the MD5 encrypted password hashes.

>Used john the ripper. First ran without wordlists and found barneybear. Rockyou on the SHA5s found papa and grizzly. Ran other wordlists, ran xato 10 million passwords on MD5s where I found carebear and cozybear, and on SHAs where I found fancybear. Ran the `darkc0de` wordlist next where I found yogibear in the MD5s. I then boarded a flight where I elected to run `hk_hlm_founds` from the weakpass site for all the hashes (was 4 hours and I could read, lol). Found nothing :(. I continued to run with as many seclists as I could before I found the 5th MD5 (my 8th! Yay!) using openwall (jackbear). For the rest of my flight I ran various  different wordlists and rules to try to hit 13. Found polarbear using openwall, and submitting 9.

>I found papabear and grizzybear with some initial messing around from SecLists/Passwords/Common-Credentials/10-million-password-list-top-1000000.txt. Then, I decided to just get all the passwords from SecLists and run them as one document (or rather 4 b/c one document crashed my computer). I ran `find /path/to/directory -type f -name "*.txt" -exec grep -hE '^[^[:space:]]+$' {} + > single_word_unique_wordlist.txt` (or something similar, I can only find the command ChatGPT gave me not the one I ended up running). Then I sorted the lines and kept only the unique lines. Then just ran it. This gave me jackbear, barneybear, yogibear, cozybear, carebear, mamabear, polarbear, and fancybear. Then I found an enormous worldist at ohmybahgosh/RockYou2021.txt on GitHub. After I finally got it downloaded, I was able to split it into several hundred files and run it on the MD5 hashes (took a couple days). Then I started running it on the SHA512 passwords and wasn't getting anywhere (other than a large electric bill) when you said we only needed 9 passwords, so I decided I needed to stop running it. A couple notes if this gets shared with future students: grepping all of SecLists is a fairly easy way to get a lot of passwords if you have the infrastructure to leave the program running for several days. The large RockYou is likely worth it, but requires a more powerful computer than I have (I split the file into about 470 odd files - about 16 million lines each) with 12 cores to run on and it took about 6.5 hours for a single file of SHA512 passwords.

>I divided the list into two separate text files: "crackme1.txt" contained the MD5 ($1$) lines, and "crackme2.txt" contained the SHA-512 ($6$) lines. I cracked a total of 9 passwords. All word lists were taken from SecLists/Passwords on Github. Going in order of the username/password list below, here were the word lists used to crack each set: "darc0de.txt" with MD5 list for the first two, "darc0de.txt" with SHA-512 list for the third, "xato-net-10-million-passwords.txt" with MD5 for the 4th and 5th, "xato-net-10-million-passwords.txt" with SHA-512 for the 6th and 7th, "openwall.net-all.txt" with the MD5 for the 8th, and "openwall.net-all.txt" with the SHA-512for the 9th

>Using John the Ripper, I successfully cracked 9 passwords at this point in time. For two passwords (barneybear:dha4 and cozybear:500764) I simply ran the program with no options specified (default mode) for just over 25 hours. After my computer crashed I decided to attempt using wordlists. I utilized wordlists from the SecLists github repo. I created multiple different wordlists using the available .txt files (Downloaded a hand full of word lists and used the copy *Directory*\*.txt *Target Name*.txt command to combine the word lists and used notepad++ to remove duplicates). Using these wordlists I applied them to each set of passwords (Two different encryption methods) and these were my results.
---
layout: post
title:  "Results of a Password Cracking Contest in My Security Class (Spring 2025)"
date:   2025-03-08 15:00:00
categories: education security
---

Each time I teach my Security class, I give a month-long lab to crack as many passwords as possible.  For this spring's contest (opened on February 11th), I used two different hash types: MD5 and SHA-512.  The contest closed on March 7th at 11:59 PM PDT.  The password hashes (16 total):

<pre>
sisterbear:$1$ApfSxfFO$FknsTo4Mlv3nO82.ilT0q1:1001:1001:,,,:/home/sisterbear:/bin/bash
grizzlybear:$1$PS0QXCyB$r228P.Y4VUFFWBzgKUAqn1:1002:1002:,,,:/home/grizzlybear:/bin/bash
jackbear:$1$BCbOtUqv$SJoRNYs7sx1gjtlxWlw6I0:1003:1003:,,,:/home/jackbear:/bin/bash
pandabear:$1$5pnCnez/$0lp7z5NlxGWgP.PJgAyrs.:1004:104:,,,:/home/pandabear:/bin/bash
yogibear:$1$qkSg6/Pc$3MUsJYeXZ3sUPnmm7KXbe.:1005:1005:,,,:/home/yogibear:/bin/bash
mamabear:$1$MULXzyNA$isycuC.G0gmPpX8hivcek/:1006:1006:,,,:/home/mamabear:/bin/bash
barneybear:$1$4Y873ZFk$7ft1lM6uIg4AJpMbUROd7/:1007:1007:,,,:/home/barneybear:/bin/bash
papabear:$1$bKfR50pc$IefSeN.y4qLYLD6ekC8Xw1:1008:1008:,,,:/home/papabear:/bin/bash
bluebear:$6$NlI8hjOs11//5.rC$iUP2pA0vK/TQFVJi5Jg91ATPtvydVDKxDLWU8kOXj6v503RPrbOKhKozY.JctPKC.4lctdNEJrFNsdcVztiP.0:1009:1009:,,,:/home/bluebear:/bin/bash
cozybear:$6$2HCZ.g49dQiTtKbm$JR3ydpTfCVHZBpSWZbjlkpIvfJGvmVr6wt/mFlqfwRJFxkPUWr7y7QBZk7GcwAXFK9tA1ZgrocavDiDcSOqEW.:1010:1010:,,,:/home/cozybear:/bin/bash
polarbear:$6$j0WfMaEjGMU4vS7y$X3JkHtc0jiBoEcMdpKH2ErMi15XxIwIL/HqF2vCZGsztj3gy0F6zAx1eA2UX6.hiuc/MPREiurVcKfebEY8JU.:1011:1011:,,,:/home/polarbear:/bin/bash
teddybear:$6$BPNWlNlfW.yWiA8B$OOUgW37LtigvbeM37e0ZHCFrMP6zyrO5.YMPayMCx.3b1Vk8v8vHRrontNYIie9JppGNe3qHtdNGV2NpbqMLh0:1012:1012:,,,:/home/teddybear:/bin/bash
carebear:$6$uV3bcm89VJaSHSmH$v0oVxLdKv0ym2u4GWU4x00joxvVzhRRhImAVFeeSi4zUfIkz1zteytLCh.hZN9qrDhCp6l4DPOgiOvUxvltPT/:1013:1013:,,,:/home/carebear:/bin/bash
blackbear:$6$nALZ3.IixrdDxDaj$6.JO0YPa.E0fictmyhcwjNJvDXB5K47/iSDZBwfFeZmG8aOFX/372tGT2C.xaqse/mat/xSIfxZVVK/4NTe5k1:1014:1014:,,,:/home/blackbear:/bin/bash
fancybear:$6$yLu0m9rfARN0B1HH$12w40GXiInIl8/EL3QF2jCN7XmJN5XMDMJGfjUqMFMlJUFlZMR3.c64zs0meBO/9EZv3DhGFD0HhRt/gbzIyN1:1015:1015:,,,:/home/fancybear:/bin/bash
brotherbear:$6$d0DrALmhR5cxXfSn$BgUx6QegMs150Ndi3taJjfJVQaSTRKCi0DaMpGZqiRyxku3e0hinAGI4wmsIOfG/03loR1XelKOymJ6OqPwdM0:1016:1016:,,,:/home/brotherbear:/bin/bash
</pre>

113 submissions across two classes.  The answers:

* (MD5) sisterbear:frederic => 113 students cracked this
* (MD5) grizzlybear:bisbocciavano => 102 students cracked this
* (MD5) jackbear:n0n4nc3571241 => 98 students cracked this
* (MD5) pandabear:dodgers1 => 113 students cracked this
* (MD5) yogibear:ethsbm => 28 students cracked this
* (MD5) mamabear:noB!.132EP;F/u35 => 0 student cracked this 😛
* (MD5) barneybear:yasuoshu => 80 students cracked this
* (MD5) papabear:lynnw00d => 92 students cracked this
* (SHA-512) bluebear:cbr900rr => 100 students cracked this
* (SHA-512) cozybear:datblygu23 => 38 students cracked this
* (SHA-512) polarbear:qaxSYIAL => 0 students cracked this 😛
* (SHA-512) teddybear:Magoveny => 79 students cracked this
* (SHA-512) carebear:13p70m3nin6i7i5 => 93 students cracked this
* (SHA-512) blackbear:Rh|ZY=TCvw4$*4fT => 0 student cracked this 😛
* (SHA-512) fancybear:69770257 => 20 students cracked this
* (SHA-512) brotherbear:soccer10 => 102 students cracked this

To earn all 10 / 10 points for the lab, students had to crack 10 or more passwords.  The final distribution:

<pre>
13 (x9)
12 (x5)
11 (x17)
10 (x52)
9 (x6)
8 (x4)
7 (x2)
6 (x3)
5 (x5)
4 (x5)
3 (x1)
2 (x4)
</pre>

Average number of passwords cracked: 9.362831858

Median number of passwords cracked: 10

How I created this spring's password cracking contest:
* sisterbear's password => taken from `xato-net-10-million-passwords-10000.txt` in Daniel Miessler's SecLists
* grizzlybear's password => taken from `darkc0de.txt` in Daniel Miessler's SecLists
* jackbear's password => taken from `darkc0de.txt` in Daniel Miessler's SecLists
* pandabear's password => taken from `darkweb2017-top10000.txt` in Daniel Miessler's SecLists
* yogibear's password => randomly generated using all [a-z]
* mamabear's password => randomly generated using all [a-zA-Z0-9!@#$%^&*()specialcharacters], less than 8 characters
* barneybear's password => taken from `md5decryptor-uk.txt` in Daniel Miessler's SecLists
* papabear's password => taken from `Ashley-Madison.txt` in Daniel Miessler's SecLists
* bluebear's password => taken from `xato-net-10-million-passwords-10000.txt` in Daniel Miessler's SecLists
* cozybear's password => taken from `md5decryptor-uk.txt` in Daniel Miessler's SecLists
* polarbear's password => => randomly generated using all [a-zA-Z], less than 8 characters
* teddybear's password => taken from `darkc0de.txt` in Daniel Miessler's SecLists
* carebear's password => taken from `darkc0de.txt` in Daniel Miessler's SecLists
* blackbear's password => randomly generated using all [a-zA-Z0-9!@#$%^&*()specialcharacters]
* fancybear's password => randomly generated using all [0-9], length 8
* brotherbear's password => taken from `darkweb2017-top10000.txt` in Daniel Miessler's SecLists

Selected methodologies and hauls from students:

> sisterbear:frederic, cracked using John the Ripper default wordlist
>
> grizzlybear:bisbocciavano, cracked using John the Ripper darkc0de.txt wordlist
>
> jackbear:n0n4nc3571241, cracked using John the Ripper darkc0de.txt wordlist
>
> pandabear:dodgers1, cracked using John the Ripper default wordlist
>
> papabear:lynnw00d, cracked using John the Ripper ashley-madison.txt wordlist
>
> bluebear:cbr900rr, cracked using John the Ripper rockyou.txt wordlist
>
> cozybear: datblygu23, cracked using John the Ripper md5decryptor-uk.txt wordlist
>
> teddybear:Magoveny, cracked using John the Ripper darkc0de.txt
>
> carebear:13p70m3nin6i7i5, cracked using John the Ripper darkc0de.txt wordlist
>
> brotherbear:soccer10, cracked using John the Ripper rockyou.txt wordlist 

<br/>

> Description: So far I have been using John the Ripper and hash cat as my 
> password crackers and for my wordlists: darkc0de.txt, ignis-10M.txt,
> md5decryptor-uk.txt, rockyou.txt, and the standard check John the Ripper runs 
> without providing any wordlist (all wordlists mentioned are from sec-list by 
> Daniel Meissler). I asked deepseek to write code that would write all
> combinations of "word" of six letters all lowercase which found the password
> for yogibear.

<br/>

> My first approach is to take the easy way out and try out some cyberchef and crackstation and any online decryptor for some of the > md5 hashes. This got me no passwords.
> My second approach was to run john with no wordlist on the file. Passwords gotten: sisterbear:frederic, pandabear:dodgers1
> Third approach was to use wordlists. I used lower_it.txt, Ashley-Madison.txt, wpa-over200k.txt, and got grizzlybear:bisbocciavano, papabear:lynnw00d, brotherbear:soccer10 and bluebear:cbr900rr respectively.
> After this I downloaded a bunch of wordlists and added them to a directory. I made a script that ran john on all of the wordlists in a directory. I got no passwords from those lists.
> I was stagnant for a bit, so I checked piazza and saw a post about looking at the strategy from previous password hacking contests…
> I downloaded Daniel Miessler’s SecLists and ran john on a directory with all the password files. Passwords gotten: teddybear:Magoveny, Carebear:13p70m3nin6i7i5, jackbear:n0n4nc3571241, barneybear:yasuoshu (md5decryptor-uk.txt)
> My next step is to use hashcat
> Final note: my first step was separating the hash types so everything specified above was done twice on both hash files.

<br/>

> Made all the wordlists in SecLists into one big wordlist and got rid of 
> duplicate words using the command:
> find SecLists/Passwords/ -type f -exec cat {} + | sort -u > combined_wordlist.txt
> (I got this command from ChatGPT)
> 
> By using John with this wordlist on the md5 hashes, I found the following passwords
> grizzlybear:bisbocciavano
> pandabear:dodgers1
> sisterbear:frederic
> papabear:lynnw00d
> jackbear:n0n4nc3571241
> barneybear:yasuoshu
> 
> By using John with this wordlist on the sha512 hashes, I found the following passwords
> carebear:13p70m3nin6i7i5
> teddybear:Magoveny
> bluebear:cbr900rr
> cozybear:datblygu23
> brotherbear:soccer10
> 
> By using John with incremental mode and testing only lower case letters I found
> yogibear:ethsbm
> 
> By using John with incremental mode and testing only numbers I found
> fancybear:69770257

<br/>

> sisterbear:frederic  -   SOLUTION: darkc0de.txt or john Md5 john -wordlist=darkc0de.txt 'hash-file.txt'
> 
> grizzlybear:bisbocciavano    -   SOLUTION: darkc0de.txt Md5 john -wordlist=darkc0de.txt 'hash-file.txt'
> 
> jackbear:n0n4nc3571241   -    SOLUTION: darkc0de.txt Md5 john -wordlist=darkc0de.txt 'hash-file.txt'
> 
> pandabear:dodgers1     -     SOLUTION: darkc0de.txt or john Md5 john -wordlist=darkc0de.txt 'hash-file.txt'
> 
> barneybear:yasuoshu   -    SOLUTION: md5decryptor-uk.txt. Md5 john -wordlist=md5decryptor-uk.txt 'hash-file.txt'
> 
> papabear:lynnw00d    -    SOLUTION: Ashley-Madison.txt Md5 john -wordlist=Ashley-Madison.txt 'hash-file.txt'
> 
> bluebear:cbr900rr    -   SOLUTION: xato-net-10-million-passwords-10000.txt SHA512crypt   john -wordlist=xato-net-10-million-passwords-10000.txt -format=sha512crypt 'hash-file.txt'
> 
> cozybear:datblygu23   -   SOLUTION: md5decryptor-uk.txt (I'm pretty sure it is md5decryptor-uk.txt I wasn't watching closely when the file was generated as I was running SecLists back to back it could also be alleged-gmail-passwords.txt as this is what I ran before it although I think it is the first one) SHA512crypt.  hashcat -m 1800 -a 0 -o solved.txt 'hash-file.txt' /SecLists/Passwords/Leaked-Databases/md5decryptor-uk.txt
> 
> carebear:13p70m3nin6i7i5   -   SOLUTION: darkc0de.txt SHA512crypt    john -wordlist=darkc0de.txt -format=sha512crypt 'hash-file.txt'
> 
> brotherbear:soccer10 SOLUTION: xato-net-10-million-passwords-10000.txt SHA512crypt    john -wordlist=xato-net-10-million-passwords-10000.txt -format=sha512crypt 'hash-file.txt'

<br/>

>Passwords were cracked using various wordlists found on Daniel Miessler's Passwords GitHub. Some took longer than others due to the size of the wordlists being used. I began combining smaller wordlists together to minimize the number of uses required for John the Ripper. But otherwise, fairly straightforward to download the required wordlists, utilize JtR and see if any passwords were cracked.

<br/>

> sisterbear:frederic
> 
> pandabear:dodgers1
> 
> jackbear:n0n4nc3571241 (this was cracked using wordlist SecLists-master/Passwords/bt4-password.txt)
> 
> grizzlybear:bisbocciavano (this was cracked using wordlist SecLists-master/Passwords/darkc0de.txt)
> 
> papabear:lynnw00d (cracked John the Ripper using wordlist SecLists-master/Passwords/Pwdb-Public/Wordlists/ignis-10M.txt)
> 
> barneybear: yasuoshu (Used hashcat)
> 
> cozybear: datblygu23
> 
> bluebear: cbr900rr
> 
> carebear: 13p70m3nin6i7i5
> teddybear: Magoveny (Used hashcat -m 1800 -a 0 -w 3 -o crackme_output4.txt --username crackme2.txt SecLists-master/Passwords/darkc0de.txt
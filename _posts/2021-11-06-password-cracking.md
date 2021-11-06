---
layout: post
title:  "Results of a Password Cracking Contest in My Security Class (Fall 2021)"
date:   2021-11-06 15:30:00
categories: education security
---

Each time I teach my Security class, I give a month-long lab to crack as many passwords as possible.  For this fall's contest (opened on October 4, 2021), I used two different hash types: MD5 and SHA-512.  The contest closed on November 5th at 11:59 PM EST.  The password hashes (16 total):

<pre>
papabear:$1$kZDH71xq$alA2JftQaUWHlfrIENNIU.:1001:1001:,,,:/home/papabear:/bin/bash
bluebear:$1$HS8m5A12$Ea22yiq0YjxSlc2CSSel5.:1002:1002:,,,:/home/bluebear:/bin/bash
carebear:$1$yFRLir2I$FVJZ7xiQmK15Ae3gWONOx0:1003:1003:,,,:/home/carebear:/bin/bash
polarbear:$1$Kn5uFJEh$H.MV5kUMuDaQ9X4t1vrwP/:1004:1004:,,,:/home/polarbear:/bin/bash
sisterbear:$1$aBe48qS3$5ZvmIyFnjbehi4Zrd.5WK0:1005:1005:,,,:/home/sisterbear:/bin/bash
barneybear:$1$lxWP2.6n$QLn5qBe95Eqwah7qRlGOh/:1006:1006:,,,:/home/barneybear:/bin/bash
grizzlybear:$1$3ld2q9Oy$6/ZbRiTaAbUMlYgUHB2/H.:1007:1007:,,,:/home/grizzlybear:/bin/bash
mamabear:$1$1bmGbv8A$cpdsAX3AYwDaU0aafJLZs/:1008:1008:,,,:/home/mamabear:/bin/bash
brotherbear:$6$n9/hFY8Bd0FKsyWo$tBb/4UcJ6UDUM8SwNs3LFP/K9LAYUUyNaN0a10evcPSaJV1UkopIkI.XK1hwvALRn2fpmTD9dzfcImBteyjcs0:1001:1001:,,,:/home/brotherbear:/bin/bash
pandabear:$6$Pm/RgBahkZLHPEj8$hTMTkUDTYulEuNm1jCQ8euWPnYGGbnoODsK7uP2sYfobUzKmfacDHkMDte0dQrEA9suTtJYTaXX.pEtnvn/Br0:1002:1002:,,,:/home/pandabear:/bin/bash
cozybear:$6$8OJwuiFE1Q5ciMQK$4Lj9G2l7guIFWocRN5th5lJ361y/T5/DbCvRmpUzYwavsKOV3EFk64g96mEjWGIgnYfHdid3OLiRWP3yxzIP51:1003:1003:,,,:/home/cozybear:/bin/bash
fancybear:$6$HNNO7e/xEtIzKilx$O9yFvvpFgzAUYD2w5ucIgSxGDRBKaMqb6Enn34vwyyt2QcT9SJRjtNANeOqVYGSHAHFxGLAX1EK1BNlUmdMb21:1004:1004:,,,:/home/fancybear:/bin/bash
teddybear:$6$J5uVdrUK2GhBWYbM$0YUwIFIMMcuTm1A9Lb2ltiMtokjERuQFGGk6xVlkTMi49KKu17g9kJsHwCsMczc0cvqRoI2J.UMBSVC2viqM70:1005:1005:,,,:/home/teddybear:/bin/bash
blackbear:$6$7PiFIzqAULeBkEFL$MYBjrfznucVWcElISyh.7SCd71jO2/J0N.dbzuhUEkgFgdnH9Sk4W8O3itHI5Z5De6Rn258VRsPJ/N5fO5E6l/:1006:1006:,,,:/home/blackbear:/bin/bash
yogibear:$6$ae7QknT7/WKAGvNp$y2ZxVrfVdPqOXMWw2Cw0.psVHcHxNaBSxSGJ4DI8M4tz1m8R6cd7qlWzPCVZ8XymFOqYfqC2l7nZWpfDb7CFd0:1007:1007:,,,:/home/yogibear:/bin/bash
jackbear:$6$jhAVayQIUbfKT3w2$qqOUPufJJI74EW5vlPMkZpmnr4wzxzkmjQxgv/qgNwC8JjA7sMwbf.XkXdR.xsuNz/a8vuDJU00Ehcz.BYzDA.:1008:1008:,,,:/home/jackbear:/bin/bash
</pre>

105 submissions across two classes.  The answers:
* (MD5) papabear:ishikariense => 94 students cracked this
* (MD5) bluebear:Leto => 99 students cracked this
* (MD5) carebear:panthers => 104 students cracked this
* (MD5) polarbear:931592 => 52 students cracked this
* (MD5) sisterbear:QHVRMHG => 1 students cracked this
* (MD5) barneybear:hUYBW5tB => 0 student cracked this
* (MD5) grizzlybear:WwdQUyJdXb => 0 student cracked this
* (MD5) mamabear:nwf_eBB{Bm => 0 student cracked this
* (SHA-512) brotherbear:hedleyite => 63 students cracked this
* (SHA-512) pandabear:41255066 => 71 students cracked this
* (SHA-512) cozybear:jacket025 => 53 students cracked this
* (SHA-512) fancybear:letmein123 => 97 students cracked this
* (SHA-512) teddybear:IDQhVo => 1 students cracked this
* (SHA-512) blackbear:zL8sYNSY => 0 student cracked this
* (SHA-512) yogibear:9ewmgtGJv6 => 0 student cracked this
* (SHA-512) jackbear:^/h5AVNH=b => 0 student cracked this

To earn all 10 / 10 points for the lab, students had to crack 6 or more passwords.  The final distribution:

<pre>
10
8 (x15)
7 (x29)
6 (x30)
5 (x13)
4 (x10)
3 (x4)
2 (x2)
1
</pre>

The winner's methodology and haul:

<pre>
Passwords Cracked (10):

carebear:panthers
polarbear:931592
papabear:ishikariense
bluebear:Leto
pandabear:41255066
fancybear:letmein123
brotherbear:hedleyite
cozybear:jacket025
sisterbear:QHVRMHG
teddybear:IDQhVo

Methods:

carebear    : found in rockyou.txt (MySpace leak)
polarbear   : bruteforced all 1-8 length digit combinations
papabear    : found in crackstation's password dictionary
bluebear    : found in crackstation's password dictionary
pandabear   : found in crackstation's password dictionary
fancybear   : found in crackstation's password dictionary
brotherbear : found in crackstation's password dictionary
cozybear    : found in the Hashmob Combined Full wordlist
sisterbear  : bruteforced length-7 all upercase
teddybear   : bruteforced length-6 uppercase-lowercase combinations

General details:

Since did not have enough power to brutforce longer password,
I decided to bruteforce smaller keyspaces using the mask feature of Hashccat
starting small (eg. only lowercase) and working my way up to harder ones.
Additonal Hashcat flags I like to use:

    -O : optimized kernel
    -w4 : using as many resources as possible. I turn this down to
          w3 if I'm doing something else on my computer.
</pre>

Methodologies used by students:

<pre>
Used john the ripper, ran simple "john file.txt" for 3.5 days and
found 3 passwords so far that way. Also ran john with password lists
from danielmeissler using --format== sha512crypt to get fancy bear,
and --format== HMAC-SHA256 for cozy bear.

carebear: panthers

bluebear: Leto

polarbear: 931592

fancybear: letmein123

cozybear: jacket025

pandabear: 41255066
</pre>

<pre>
papabear:ishikariense
bluebear:Leto
carebear:panthers
brotherbear:hedleyite
pandabear:41255066
cozybear:jacket025
fancybear:letmein123

 

METHODOLOGY

Used wordlists: 
    - darkc0de.txt
    - Common-Credentials/500-worst-passwords.txt
    - Common-Credentials/100k-most-used-passwords-NCSC.txt
    - unkown-azul.txt
    - Keyboard-Combinations.txt
    - darkweb2017-top10000.txt
    - xato-net-10-million-passwords.txt


I mainly used John the Ripper, and let it run in the background 
while I did other work. Specifically I looked for LONG wordlists,
that are MB long, so that I minimized the amount of time that I
spent picking/setting up/running the commands.

I also let my computer run overnight, changing the screen display 
to never time out. I hear that's bad for my battery, but my 
battery is already pretty bad, so I always make sure to have my
charger with me.
</pre>

<pre>
carebear: panthers, I cracked this password using john without adding
my own wordlist.

bluebear: Leto, I cracked this password by passing the first 8 into
john using the 10 million most common passwords as the wordlist.

fancybear: letmein123, I cracked this password by passing the last 8
into john using the 10 million most common passwords as the wordlist.

pandabear: 41255066, I cracked this password by passing the last 8
into john using the 10 million most common passwords as the wordlist.

cozybear: jacket025, I cracked this password by passing the last 8
into john using the 2020-200_most_used_passwords.txt

papabear: ishikariense, I cracked this password by passing the first 8
into john using the darkc0de.txt as the wordlist.
</pre>

<pre>
pandabear:41255066

fancybear:letmein123

brotherbear:hedleyite

cozybear:jacket025

papabear:ishikariense

bluebear:Leto

carebear:panthers

polarbear:931592

I divided the given set of hashes into two files based on hash
type. Then, I concatenated all of the text files in the outermost
directory of the SecLists Password folder into one large files of
passwords. I did the same for each directory within Passwords. Then I
ran John-Jumbo with each of these lists on each of the two files of
hashes. I also ran the MD5 passwords with a larger list from
crackstation.</pre>

<pre>
papabear:ishikariense

bluebear:Leto

carebear:panthers

polarbear:931592

brotherbear:hedleyite

fancybear:letmein123

cozybear:jacket025

For the MD5 hashes, I primarily used John the Ripper to crack the
passwords. I went through all files in SecLists and also went online
for additional lists such as Kaonashi. For the SHA512 hashes, I used
hashcat because I realized it would be faster after John the Ripper
took too long. I reran hashcat with the largest text files in SecLists
to search for SHA512, which is how I managed to find the 3 SHA512
hashes listed as the bottom 3 from the list above.  </pre>

<pre>
Passwords Cracked:

bluebear:Leto
carebear:panthers
papabear:ishikariense
polarbear:931592
brotherbear:hedleyite
cozybear:jacket025
fancybear:letmein123
pandabear:41255066

Methodology:

It did not take much time to realize that password cracking takes a
lot of time. Before starting I did a bit of research on john and
hashcat to understand how to efficiently use them. Additionally, I
searched the web for more wordlists other than those in SecLists to
download and run with the password crackers.

After doing a bit of research I tried split the given passwords into
two separate files, one file contained the md5 typed passwords and the
other contained the sha512 typed passwords. I then tried to use
hashcat, but after spending some time on it and reading tutorials, I
was not able to get the correct settings and kept get warnings, so I
resorted to using john.

My first run of john I ran without any arguments on the file
containing the md5 passwords. I quickly got carebear's password this
way, (carebear:panthers), after which john then began its incremental
password cracking strategy. I left john running on this mode for quite
some time (about 2 days) and was unsuccessful in cracking anymore
passwords, so I decided to terminate the process and try more
wordlists.

With this methodology I was able to crack a number of passwords. Using
the bt4-password.txt wordlist, I cracked bluebear's password
(bluebear:Leto). Using the darkc0de.txt wordlist, I cracked
papabear}'s password (papabear:ishikariense). Using a wordlist that I
had downloaded from the internet, kaonashi.txt, I cracked polarbear's
password (polarbear:931592).

While john ran to crack these passwords, I was doing more research on
how to crack the password hashes. One strategy was to literally search
for the usernames and hashes in google. To my surprise, I found write
ups to previous CS116 Password Cracking Contests this way. Since any
method other than collaborating with other students in the class was
fair game I looked at the password solutions for every previous
Password contest and made my own wordlist this way. However, even
though I was sure at least L1verpool were to be a password this year
as it had been a password used multiple times in previous semester,
this wordlists did not yield any cracked passwords.

After my wordlist of previous passwords was made, I found that it was
getting a bit tedious having to switch from wordlist to wordlist once
a wordlist had finished.  Additionally, if I were not at my computer
at the time a wordlist finished I lost valuable password cracking
time. To resolve this, I created a simple script in BASH that took in
a file of password hashes to crack, and a directory filled with
password cracking wordlists. The script would then proceed to run john
using each wordlist in the directory with the provided password hash
file. This method saved a lot of time as I would no longer have to
continuously check the progress john was making on a single wordlist
as the next wordlist in the directory would automatically run. I even
installed an application to my computer to prevent my computer from
going to sleep so the script could run continuously.

I let the script run for approximately a week on all the wordlists I
had downloaded, and was able to crack the following passwords:

- fancybear:letmein123 with wordlist 000webhost.txt
- cozybear:jacket025 with wordlist 100k-most-used-passwords-NCSC.txt
- pandabear:41255066 with wordlist
  10-million-password-list-top-10000000.txt
- brotherbear:hedleyite with wordlist bt4-password.txt

Some other methods I used including running a 15GB wordlist on a
separate computer I had available to me. This took a week to complete,
and after it completed, the passwords it cracked were ones I had
already cracked with the methods I used above.  Additionally, I looked
into running a password cracker on a cloud server, however, this
method was not practical for me to use, having really only one other
computer (my laptop) available at this point I was consistently moving
around and losing connection with the cloud server, which would then
stop the process. I attempted to research a way to resolve this issue
but was unsuccessful, likely with more time and experience with cloud
servers I would have been successful in solving this issue.

All in all, this was a great learning experience. In future password
cracking, some ways I would adjust my methods would be to merge all
the wordlists I plan to use into one master wordlist and remove any
intersections that might be found between wordlists.  Having zero
duplicate between wordlists would save a lot of time as it would avoid
processing the same password multiple times. I would also designate a
single computer to run the password cracker and a cloud server at the
same time so I would still have full use of the computer I use for
work. The main lesson learned is that password cracking takes a lot of
time and resources, and the more time and resources you have available
to you, the more successful you will be.  BASH Script

#!/bin/bash

if [ ${#} -lt 2 ]
then
echo "Usage: ${0} password_hashes wordlist_directory"
exit -1
fi

WORDLISTS=$(ls ${2}/*.txt)

for LIST in $WORDLISTS
do
echo "---------------------------------------------------------------------"
echo "Now running john with wordlist: "${LIST##*/}
echo "---------------------------------------------------------------------"
echo
john --wordlist=${LIST} $1
done
</pre>
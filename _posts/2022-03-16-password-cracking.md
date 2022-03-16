---
layout: post
title:  "Results of a Password Cracking Contest in My Security Class (Spring 2022)"
date:   2022-03-16 14:30:00
categories: education security
---

Each time I teach my Security class, I give a month-long lab to crack as many passwords as possible.  For this spring's contest (opened on February 15, 2022), I used two different hash types: MD5 and SHA-512.  The contest closed on March 15th at 11:59 PM PDT.  The password hashes (16 total):

<pre>
jackbear:$1$hywhATWG$MWDc414DyeSnztehEmi221:1001:1001:,,,:/home/jackbear:/bin/bash
brotherbear:$1$8bzZwROt$XUPwfIRdb07qXLLnCQw7B0:1002:1002:,,,:/home/brotherbear:/bin/bash
fancybear:$1$Nbe6ers2$ZW5VbAfMM9xBuLZSI61Ov0:1003:1003:,,,:/home/fancybear:/bin/bash
barneybear:$1$fZO404Ln$heJgdKHfFni.xzV8F1gUP.:1004:1004:,,,:/home/barneybear:/bin/bash
pandabear:$1$tYcIKTob$uoA4p/8OrzXsg.k/6w8370:1005:1005:,,,:/home/pandabear:/bin/bash
yogibear:$1$7fb/NYLR$ylwPOpUaS2q1NcHvBAt4K.:1006:1006:,,,:/home/yogibear:/bin/bash
papabear:$1$xwiEhbtM$miQ3uKUmHsgAvYgyluDDA/:1007:1007:,,,:/home/papabear:/bin/bash
grizzlybear:$1$pq9yY0tQ$GLQZa8gpG1Luf4iCOnBEK.:1008:1008:,,,:/home/grizzlybear:/bin/bash
sisterbear:$6$Wfq2HoGzG822Sqt0$jYC1RIk00A09pQRsVm0GveEaUJFjK4oOuJU9B2t1iJhH.LzsfKaE2z9QuRlEFmdM9ZUq8UtQAgolm1SNqvd6V/:1001:1003:,,,:/home/sisterbear:/bin/bash
teddybear:$6$t5ykTUMlMtbBg4TK$vdZl5z2CI7hoe/F0meeSpgdDUpw.gcenQ0MxF6QdbM73SvlocOO0UVcbKXjJQKZGscSFDd2wWZUfbW6ag8qaE/:1002:1004:,,,:/home/teddybear:/bin/bash
polarbear:$6$K21s24VHlHLEFSE1$cLHyDaRX6enEN6Wo/w8knfgnEXG1y6Jm5vw9EUWupy.8kPMIiDxsny2ew50.mcfc/RfGd6cqamvx0M1fI1tCt.:1003:1005:,,,:/home/polarbear:/bin/bash
bluebear:$6$b3OKo5na5waXTgwo$6Wx57nOL1r8Gfs74hq5qN0Pmmd97Dbu7yytCZH7OiPbisEtSsZHRsJttllAweN3NYeXYnhoTJgPcVxMsw67nN1:1004:1006:,,,:/home/bluebear:/bin/bash
blackbear:$6$AIniJcbZ39IT6/1L$4FeR9YbBkMVXa2tzxbZ3HR8JxhUhS.tKkOdE6XtV9I/5VLo07bzrw1T1rYQqhQMLLM8XpUpJGF1yTOPOCitKC0:1005:1007:,,,:/home/blackbear:/bin/bash
mamabear:$6$TpNBOtjR0Bhvh7bf$UK9SQLqhpq7fY2v7YgxFvqDFUHP8ttdqag0KoZ74BQAq.PqHBK8BjZ3WE/glc.ZpdZgepgPMpDWh6izXU6vsx.:1006:1008:,,,:/home/mamabear:/bin/bash
carebear:$6$/0nHqx8c8TYhzftJ$aEPcb/3AwDZvBsb3BPAql6c/HOzF86O73OB3oPnKJAKCvxBE0ic2cjSHW5xEr81qS70MtnZWxOVMIn7qsu2eK/:1007:1009:,,,:/home/carebear:/bin/bash
cozybear:$6$cyTr8Zjte//XOEEM$DgLhyB/WS0yZcEk4I8w//J.FVwxNKtLTn8F6QYw7R/ywhCpBb/0xiZ9g/u09ui.KADuhBbAerbk/uMCmXpqey/:1008:1010:,,,:/home/cozybear:/bin/bash
</pre>

114 submissions across two classes.  The answers:
* (MD5) jackbear:20100728 => 90 students cracked this
* (MD5) brotherbear:L!verpool => 39 students cracked this
* (MD5) fancybear:54ck3n => 108 students cracked this
* (MD5) barneybear:gofast => 113 students cracked this
* (MD5) pandabear:IDLER => 103 students cracked this
* (MD5) yogibear:Wh@t3ver! => 12 students cracked this
* (MD5) papabear:1632TEAR => 107 students cracked this
* (MD5) grizzlybear:069rG2 => 4 students cracked this
* (SHA-512) sisterbear:774415 => 43 students cracked this
* (SHA-512) teddybear:csh1sA => 0 students cracked this
* (SHA-512) polarbear:220493 => 104 students cracked this
* (SHA-512) bluebear:ukflbjkec => 88 students cracked this
* (SHA-512) blackbear:4utumn1# => 28 students cracked this
* (SHA-512) mamabear:Concurrent => 60 students cracked this
* (SHA-512) carebear:C@gx"9ZY)V => 0 student cracked this
* (SHA-512) cozybear:#BHRN(@xKoa/ => 0 student cracked this

To earn all 10 / 10 points for the lab, students had to crack 6 or more passwords.  The final distribution:

<pre>
13 (x2)
12 (x2)
11 (x13)
10 (x11)
9 (x11)
8 (x16)
7 (x23)
6 (x29)
5 (x6)
4
</pre>

The co-winner's methodology and haul:

<pre>
For this lab, I employed several cracking strategies. First, I used
cat and file redirection to combine all of the SecLists repository
into one massive file, which I ran through John the Ripper for all the
hashes. I also downloaded several other wordlists, including a list by
berzerk0 on GitHub of 109 million "most probable" passwords, a
wordlist called Kaonashi, and CrackStation's human based wordlist,
combining them into one list called BCK_full.txt, which was also run
through John the Ripper. Some other wordlists I experimented with was
one I wrote code to generate which created all possible digit-only
strings up to a certain length, the full CrackStation wordlist, the
full Kaonashi wordlist, OpenWall's entire wordlist, and a wordlist
taken by combining several wordlists created by someone from Oxford
University. I ran a vast majority of my cracking attempts using the
Tufts HPC, which proved even more effective when I eventually switched
to using Hashcat, which could utilize multiple GPUs in parallel. I
typically used NVIDIA A100 or NVIDIA Tesla 4 GPUs, up to at least 16
at a time running several cracking instances. I also utilized
OnlineHashCrack.com, which ran some cloud password cracking on its own
hidden wordlists and rules on the hashes I gave it, and it was able to
crack one password, which I paid 15$ to reveal (since it was over 8
characters in length). I also ran some pure brute force on Hashcat,
including generating all possible strings for some small lengths, and
also trying this on larger length strings by restricting the
characters that could be used in the passwords. Finally, I also
utilized some rules as a way of "mangling" wordlists; the rules I
mainly used was the best64 rule and the InsidePro-PasswordsPro rule.

yogibear:Wh@t3ver!
barneybear:gofast
jackbear:20100728
papabear:1632TEAR
pandabear:IDLER
brotherbear:L!verpool
fancybear:54ck3n
grizzlybear:069rG2
polarbear:220493
bluebear:ukflbjkec
mamabear:Concurrent
sisterbear:774415
blackbear:4utumn1#
</pre>

<pre>
MD5 
jackbear:20100728 (From 2020-200_most_used_passwords.txt)
barneybear:gofast (From Most-Popular-Letter-Passes.txt)
fancybear:54ck3n (From bt4-password.txt)
pandabear:IDLER (From darkc0de.txt)
papabear:1632TEAR (From xato-net-10-million-passwords-1000000.txt)
brotherbear:L!verpool (From crack station wordlist )
yogibear:Wh@t3ver!  (From weakpass_3 from weakpass.com)
grizzlybear:069rG2 ( Hashcat Brute force with A100 GPUs in GCP)

SHA512 
(From hashesorg2019)
polarbear:220493
sisterbear:774415
mamabear:Concurrent
bluebear:ukflbjkec 
blackbear:4utumn1# (from seclists)
 
The first 7 password ran from M1 chip. switch to GPU later for optimal
performance.  Wordlists from SecLists Git Repo, Crack Station, and
weakpass.com. Had to brute force on GCP A100 GPU for grizzlybear.

Commands:

ls ~/wl/*.txt | xargs -t  -I% john --session=attack1 --wordlist=% -fork=8 hash1.txt

john --format=md5crypt-opencl --wordlist=weakpass_3 --devices=gpu crack1.txt

SHA512. All jobs done in GCP A100 GPU instances with hashcat. John had
some problems in opencl driver with the instances.

Command: hashcat -O -m 1800 -o result.txt -a 0 -w 3  hash.txt wordlist
</pre>

<pre>
Used john the ripper, ran simple "john file.txt" for 3.5 days
and found 3 passwords so far that way. Also ran john with password
lists from danielmeissler using --format== sha512crypt to get fancy
bear, and --format== HMAC-SHA256 for cozy bear.

carebear: panthers
bluebear: Leto
polarbear: 931592
fancybear: letmein123
cozybear: jacket025
pandabear: 41255066
</pre>

The runners-up methodology and haul:

<pre>
barneybear:gofast
fancybear:54ck3n
pandabear:IDLER
jackbear:20100728
mamabear:Concurrent
blackbear:4utumn1#
bluebear:ukflbjkec
polarbear:220493
papabear:1632TEAR
sisterbear:774415
yogibear:Wh@t3ver!
brotherbear:L!verpool

John the ripper using: all wordlists from SecLists, rockyou.txt, and
cyclone.hashesorg.hashkiller.combined.txt.
</pre>

<pre>
barneybear:gofast
papabear:1632TEAR
jackbear:20100728
brotherbear:L!verpool
fancybear:54ck3n
pandabear:IDLER
yogibear:Wh@t3ver!
sisterbear:774415
polarbear:220493
bluebear:ukflbjkec
mamabear:Concurrent
blackbear:4utumn1#

Passwords cracked: 12 (7 MD5 + 5 SHA512)

My process:

1. Used one of the largest list from the SecLists repository,
containing a million of the most common passwords. Ran this wordlist
with john and cracked 1 or 2 of the MD5 hashes in under 5 minutes.

2. Used a list of 1.4 billion passwords found online mentioned in
seclists somewhere. This wordlist is ~10 GB. Using this list, john ran
for 20 minutes and found 2 or 3 more MD5 hashes, so I had 4 cracked
MD5 hashes total.

3. Battled to get john or hashcat cracking SHA512 hashes on my M1 Mac,
but had no luck.

4. Switched to my PC for cracking SHA512 hashes. Downloaded the
rockyou dataset (~140 MB) and used it on the SHA512 hashes with
hashcat, which cracked two of them in under 10 mins.

5. Downloaded CrackStation.net’s entire dictionary (~15 GB) and used
it to try to crack the remaining MD5 hashes with hashcat. Got two more
of the MD5 hashes with this method in about 40 minutes.

6. Found some of the most effective rules for hashcat. Many of them
took too long to run, so I found a simpler rule file called
cyclone_250 containing the 250 top rules for cracking hashes. Running
this file with the rockyou dataset on the MD5, I found another one of
the MD5 hashes in just under an hour. I tried a bunch of other rules
with some of the smaller datasets, but had no luck.

7. Ran the 1.4 billion password wordlist on the SHA512 hashes
overnight, which cracked another two of them.

8. Merged all the other password files from the SecLists repository
together, then used that combined wordlist to crack another SHA512
hash.  </pre>

Methodologies used by students:
<pre>
I used hashcat with all the small wordlists (< 1mb) and some big
wordlists (darkc0de.txt, bt4-password.txt, SCRABBLE-large.txt,
SCRABBLE-munged-large.txt, xato-net-10-million-passwords-1000000.txt)
to crack the passwords. The first five are from MD5, last four are
from SHA512.
</pre>

<pre>
- I started with just having john the ripper use the automatic
  wordlist on the first three hashes in my file "crackme.txt" but it
  didn't crack any passwords that way, and it has been running using
  the brute force method and still hasn't cracked any passwords that
  way. Then, I had two terminal windows running: "crackme2.txt" with
  the first 8 hashes and "crackme3.txt" with the last 8. I used the
  wordlist with 10,000,000 passwords and have been having much more
  success with that.

- I got pandabear after 12 hours of running john the ripper using a
  wordlist by crackstation called "humanwordlist"

- I got sisterbear after about a day of running john the ripper using
  "humanwordlist" by crackstation.

- I got jackbear in less than 1 second by running john the ripper
  using "2020-200_most_used_passwords.txt" by danielmiessler

- I got fancybear in about 2 minutes running john and using wordlist
  “darkc0de.txt"I got mamabear in about 1 hour running john and using
  “darkc0de.txt”

- I got mamabear in about 1 hour running “darkc0de.txt”
</pre>

<pre>
Methodology: I set up an Ubuntu instance on Google Cloud to run John
the Ripper using as much of the CPU as possible with --fork. I found
the first three passwords with the rockme.txt wordlist, then ran JtR
incremental mode for about a week and got the next two. Once I hadn't
gotten any for a few days, I switched tactics and ran all of the
wordlists from SecLists using a bash script that iterated through them
and got the next five (lesson learned: run all the lists, not just the
biggest one).
</pre>

<pre>
I used wordlists to crack these passwords. I used SecLists as my
wordlist.

For fancybear and pandabear, I used darkc0de.txt 

For jackbear, I used 2020-200_most_used_passwords.txt 

For barneybear, papabear, bluebear and polarbear, I used
xato-net-10-million-passwords.txt

I first saved the first 8 passwords in a file and ran john on that
file with the wordlist files, and then did the same for the last 8
passwords
</pre>

<pre>
Overall: 7 passwords were cracked. 

First Submission: 

Cracking methodology was running the word list SecLists on a
crackme.txt file I created and put both of those in my Desktop folder
called "lab5." I ran the command: john
--wordlist="SecLists/Passwords/darkc0de.txt" crackme.txt, which was a
file which had all the hashes we could run on john the ripper through
the mac terminal.

Password       Username 
IDLER (pandabear)
54ck3n (fancybear)

Second Submission: 

This was run on john
--wordlist="SecLists/Passwords/xato-net-10-million-passwords-1000000.txt"
crackme.txt I also had put the format into format=md5crypt-long to
find two more passwords.

Password    Username 
gofast (barneybear)
1632TEAR (papabear)

Third Submission: 

This was run on john --wordlist="SecLists/Passwords/darkc0de.txt"
password.txt I took out the format=md5crypt-long to find another
password and simply ran the last 8 as these are not md5.

Password    Username 
Concurrent

Fourth Submission:

This was ran on john
--wordlist="SecLists/Passwords/xato-net-10-million-passwords-1000000.txt"
password.txt I took out the format=md5crypt-long to find another
password and simply ran the last 8 to find these two, as the last 8
are not md5.

Password    Username 
ukflbjkec (bluebear)
220493 (polarbear)
</pre>

<pre>
For these passwords, I split the MD5 into two sets of four (because it
seemed as though there were different MD5 variants) and ran them on a
combined wordlist I made. The way I created the wordlist was by
concatenating all the files in the SecLists wordlist directory with a
simple script. I also used the rockyou wordlist and am in the process
of using the crackstation wordlist. I got the first SHA password via
brute force.
</pre>

<pre>
I've been using John the Ripper. I took the original file of password
hashes and separated it into 2 files with the 2 differrent types of
hashes. I first ran JtR on the default wordlist. Then I then
downloaded all the password lists from Daniel Miessler's github. I
combined all the lists into 1 big txt file and used that on each of
the hash files. Then I googled around and found a couple more very
large word lists that i downloaded (~2 GB) and ran each word list
through those. I cn currently still running each hash list on a new
wordlist but this is what i have so far.  </pre>

<pre>
basic john md5 on wsl

barneybear:gofast

fancybear:54ck3n

jackbear:20100728

 

hashcat w/ darkc0de password list

pandabear: IDLER

mamabear: Concurrent

 

hashcat w/ xato-net-10-million-passwords-1000000

papabear: 1632TEAR

polarbear: 220493

bluebear: ukflbjkec
</pre>
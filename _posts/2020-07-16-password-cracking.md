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

The winner cracked 9 of the 17 passwords.  The winner's haul and strategy:

>The methodology I used to crack 9 of the 17 hashed passwords given was:
>
>Throw the kitchen sink at them! 
>
>Honestly, I tried every single method I could think of, write myself or find online. 
>
>Briefly, the things/tools I used were:
>
>1. A program I wrote myself called crypt.py. 
>2. Three shell scripts I wrote, run_crack.sh, run_hashcat.sh, and run_john.sh
>3. A program I wrote called genmask.py, that, well, generates masks!
>4. Another program called maskgen.py, that, well, generates masks (but more smartly than mine)
>5. The rest of the PACK suite, including policygen.py, rulegen.py and statsgen.py
>6. hashcat
>7. john the ripper
>8. john jumbo (when I realized how limited regular john was!)
>9. rainbowcrackalack (but not really since rainbow lists are insanely expensive)
>10. AWS service.  Specifically an EC3 P3 instance with the beastly NVIDIA Tesla V100GPU!
>    I ran Amazon Linux as the OS, which I relaize now was a big mistake.
>
>With all of the tools above I did brute force attacks (up to length 7 for each type),
>straight wordlist attacks, wordlist attacks with rules and attacks using masks (and
>probably some others I've since forgotten about).
>
>More sneaky things I tired:
>
>I did a google search for each of the hashes, and chanced upon a few articles written by one
>Ming Chow of Tufts University.  It seems like this professor posts the hashes, passwords and
>methodologies of the winners each semetster! : )  Using that knowledge, I compiled a list of
>all the passwords used in previous semesters.  I noticed that one password in particular was
>used in the last 3 semesters!  Specifically it was "L!verpool", but alas!  This was not used
>for our semester... I really thought I had one there!  I did of course, use this list to run
>a simple wordlist attack, and I also generated several different masks based on the patterns
>of the previous winners, but this didn't yeild any results unfortunately.  I thought maybe
>the patterns were re-used every semester, but it seems like they are very random, which is
>good for competition, but bad for me!
>
>Here is a description of each of the programs I wrote:
>
>~~~ crypt3.py ~~~
>
>Big Idea:
>
>Compare the hashes given to us to hashes I generate with my program to find a
>match.  The program I wrote does (in short):
>
>1. Read from the file of hashes and parse them to grab the hash and username
>2. For each username/hash parsed, run over an entire directory of known
>   wordlists.
>3  Convert each word in each wordlist to the correct hash format
>4. Then, simply compare the two strings.
>
>NOTE: Only works in the Kali Linux VM since it seems like python is depreciating the
>      crypt module.  Somehow Kali Linux has all the modes pre-installed, whereas a fresh
>      python3.8.3 install does not! This caused a few hours of wasted time looking up
>      dependencies and reading documentation, which is largely incorrect.
>
>      You can see what modes are installed by starting a python3 instance by
>
>      python3
>      import crypt
>      crypt.methods()
>
>      The latest python install only supports the good old fashioned crypt.METHOD_CRYPT whereas
>      the Kali Linux install has many more modes...annoying!
>
>
>~~~ run_crack.sh, run_hashcat.sh, run_john.sh ~~~
>
>Big Idea:
>
>Shell scripts that run crypt_3.py, hashcat or john-the-ripper over an entire directory.  The three
>programs are identical what they do.  They simply run the given program with in wordlist mode for any
>files with extension .txt in a directory.  They differ in the command line arguments they accept, since
>there are different requirements for each program this calls.
>
>1. Parses all files in directory for extension .txt
>2. Runs crypt.py, hashcat or john with arguments provided on command line (usage varies per program)
>3. Prints out how many passes it will attempt, the filename currently running, time elapsed, and prints any
>   found passwords to screen and to a pot file. 
>4. If a hash is found, it removes the found hash from file to speed up consecutive runs
>
>
>~~~ genmask.py ~~~
>
>Big Idea:
>
>Generates a mask file by generating a given number of random mask strings a given number of times and
>prints them to a given file, one line at a time, hence creating x number of random masks of the given length.
>
>1. Uses pythons random module to pick from a list of 4 strings, '?l', '?u', '?s', and '?d'.
>   I chose to use python for this because the random module has been optimized for a more even
>   distribution of numbers.  Even if the choices are only 0 - 3 I wanted a better random generator than
>   srand in c++, but without the hassle of that unique_distribution crazy syntax that better random
>   number generators use. 
>2. Compares the newly created mask to the ones already generated in the file, and does not print duplicates
>   to the file. If a collision occurs, it prints the offending mask to the screen.
>
>   Basically this is a permutator.  It works pretty well and is decently fast.  For example it created a
>   10,000 line mask file of length 10 masks in about 2 minutes.  The real problem with it is that the way
>   it handles collisions is very naive.  It reads the entire file in and compares line by line.  I think
>   this makes worst case runtime O(n^2), but it is good enough for my purposes.  Pretty sure a 10,000 line
>   length 10 mask file would take on the order of a few years to run even on a decent GPU.
>
>
>With these tools I was able to crack the following hashes:
>
>MD5 Hashes
>Username: papabear Password: Pan-orthodox
>Username: bluebear Password: LUJAN
>Username: carebear Password: bottelborsel
>Username: polarbear Password: 59262
>
>
>SHA 512
>Username: mamabear Password: ster56
>Username: brotherbear Password: eater
>Username: jackbear Password: 193838
>Username: pandabear Password: become55
>
>
>NTLM
>Username: cindybear Password: secret
>
>
>Specifically, the tool attack and/or wordlists for each were:
>
>
>Fri 19 Jun 2020 02:24:04 AM EDT
>
>Method: crypt.py
>hash: MD5
>wordlist: bt4-password.txt
>
>Username: papabear    Password: Pan-orthodox
>
>
>Method: crypt.py
>hash: MD5
>wordlist: darkc0de.txt
>
>Username: bluebear    Password: LUJAN
>
>Username: carebear    Password: bottelborsel
>
>
>Method: john jumbo brute force
>hash: MD5
>wordlist: N/A
>
>Username: polarbear   Password: 59262
>
>
>Method: crypt.py
>hash: SHA-512
>wordlist: bt4-password.txt
>
>Username: brotherbear    Password: eater
>
>
>Method: crypt.py
>hash: SHA-512
>wordlist: 10-million-password-list-top-1000000.txt
>
>Username: mamabear    Password: ster56
>
>
>
>Sat 20 Jun 2020 03:42:52 PM EDT
>
>Method: hashcat -m 1000 -a 0 NTLM_hashes.txt ./wordlists/Passwords/Leaked-Databases/rockyou-75.txt -r /usr/share/hashcat/rules/combinator.rule
>hash: NTLM
>wordlist: rockyou-75.txt
>
>Username: cindybear:          Password: secret
>
>Method: hashcat with a wordlist (forgot which one) in increment mode with trailing ?a?a?a?a mask
>hash: SHA512
>wordlist: ???
>
>Username: pandabear           Password: become55
>
>Some time later... (I forgot the date and didn't document this one properly)
>
>Method: hashcat brute force on AWS
>hash: SHA512
>wordlist: N/A
>
>Username: jackbear            Password: 193838
>
>
>Caveats:
>
>Remember above when I said I had run a brute force attack on each of the types up to length 7?
>Well, I thought I had successfully done this, but, as of the revelation of this years winning
>passwords, I was shocked to notice that there were two passwords of less than length 7
>that my brute force attacks missed!! Specifically:
>
>(MD5) sisterbear:VTPtQu => 0 student cracked this
>(SHA512) cozybear:zjhag7 => 0 student cracked this
>
>I think what happened was, that after noticing how painfully long brute force attacks take,
>I gave up running them on my personal laptops, (since my GPUs are terribly slow) and
>decided I would run all my brute force attacks on AWS.  Well, when you get finally get an instance of
>AWS running, you get a completely blank slate.  Meaning no programs besides the very most basic
>of what you would expect to find in /usr/bin. So you have to go through and install EVERYTHING you
>need on your own!  (also, I had never used yum before, so there was a slight learning curve there).
>
>Hashcat is the most powerful brute force cracker, and AWS servers, specifically the P3 instance have
>crazy powerful GPUs, so I thought this was a perfect marriage.  Well, some people/programs just aren't
>meant to be together!
>
>For hashcat to really work properly, it requires that you have very specific drivers installed for
>each particular GPU.  Installing the dependencies and then the CUDA drivers for this was a
>nightmare!  Here's what I had to do (I made notes of this as I had to do this several times):
>
>First:
>
>sudo yum groupinstall "Development Tools"
>sudo yum install gcc
>sudo yum install git
>
>Second:
>
>Building hashcat for Linux and OSX
>
>Get a copy of the hashcat repository
>
>$ git clone https://github.com/hashcat/hashcat.git
>$ cd hashcat
>
>Get a copy of the OpenCL Headers repository
>
>$ git submodule init
>$ git submodule update
>
>Run "make"
>
>$ make
>
>Install hashcat for Linux
>
>The install target is linux FHS compatible and can be used like this:
>
>$ sudo make install
>
>For CUDA drivers:
>
>wget http://developer.download.nvidia.com/compute/cuda/11.0.1/local_installers/cuda_11.0.1_450.36.06_linux.run
>sudo sh cuda_11.0.1_450.36.06_linux.run
>
>^^^ Click on that link and see how insane it is to properly install the drivers! So many steps! ^^^
>
>The result is that it takes around 1-2 hours just to get up and running.  AWS services are not cheap! 
>I went the cheap route by getting a spot instance, which means you get 6 hours of time at a reduced rate.
>It was about 90 cents an hour.  Not terribly costly, but then to get the storage to save your work is
>another cost. etc. etc.... To have an instance running for the amount of time you'd need to actually
>crack a password of over length 6, well, you'd better be getting something valuable out of that password!
>
>What I did was save the state of the hashcat session I was running, then scp that file over each time
>I resumed the attack. It is very possible that this is where the error occured, but hashcat didn't seems
>to mind picking up from where it left off each time, so I assumed this was working properly.
>
>HOWEVER! Apparently, there must have been some issue with how the drivers were working with hashcat, because
>as far as I knew, I did run up to length 7 for each of the types!  This kind of thing is well documented
>on the hashcat forums, of which I am now a contributing member! lol.
>
>I've since learned that haschat works better with consumer grade GPUs, specifically ones that have
>better integer performance, not floating point performance (whatever that means!). So all my efforts
>to get the Tesla V100 GPU up and running were really a waste of time! Live and learn.
>
>That's it! As you can see I got a little obsessed with this, and I had a lot of fun doing it.
>Maybe I'll sneak a peek at next semesters hashes and try again with all the knowledge I have now,
>just to see if I can crack 'em all!

---
layout: post
title:  "Results of a Password Cracking Contest in My Security Class (Summer 2021)"
date:   2021-07-29 15:00:00
categories: education security
---

Each time I teach my Security class, I give a month-long lab to crack as many passwords as possible.  For this summer's contest (opened on June 21, 2021), I used two different hash types: MD5 and SHA-512.  The contest closed on July 28th at 11:59 PM EST.  The password hashes (24 total):

<pre>
belgium:$1$cHcZPALS$R73l40hQ4uULNXaRVuwb9.:1001:1001:,,,:/home/belgium:/bin/bash
russia:$1$07OeT24w$nZC9lhyUvLS5ZSIpSlBdR/:1002:1002:,,,:/home/russia:/bin/bash
italy:$1$KILD50Wu$ZavxnSFW.rJFw2ZqjabQA/:1003:1003:,,,:/home/italy:/bin/bash
wales:$1$76T7YtxD$zveRCuyTFYDcTtdTcgUOt/:1004:1004:,,,:/home/wales:/bin/bash
switzerland:$1$MvA3qNdR$WjqgkWLoZs2hZ1QfERlSJ.:1005:1005:,,,:/home/switzerland:/bin/bash
turkey:$1$Rkofp2AE$sYSQL71wWeJ2ozDlulmJG/:1006:1006:,,,:/home/turkey:/bin/bash
finland:$1$RoNzitJE$4ypcFUfQeuGvWCROQJjM7/:1007:1007:,,,:/home/finland:/bin/bash
denmark:$1$CCxdcrXz$sIpfymDf9wftTZ2YyWyg31:1008:1008:,,,:/home/denmark:/bin/bash
netherlands:$1$hI4mNVPZ$axj5KW3V8pkRE5TChDdEi0:1009:1009:,,,:/home/netherlands:/bin/bash
ukraine:$1$Iw/e.Fu3$v1le47O4m/wf28tj5K0Aj1:1010:1010:,,,:/home/ukraine:/bin/bash
austria:$1$0fyXp9OJ$CyS9ekf2flJMWTi/kUNLU1:1011:1011:,,,:/home/austria:/bin/bash
nmacedonia:$1$QOorRQ7I$N2IDJN9iwGqbiytH2FMMd.:1012:1012:,,,:/home/nmacedonia:/bin/bash
czechrepublic:$6$HRwOf4/FCUYr/zvG$CqNrTfVVjnPp5rExtWfPs2nxL9dYUUVELIastZQ3eMq3F2jcAlEZtFOL9GEHhzZN8r31OSj.F/pPIKlo23Zli0:1001:1002:,,,:/home/czechrepublic:/bin/bash
england:$6$foIJz9z4Us3/DwZ5$3LH4PH3DpgYlCIE6rWqoHUrhN5sXSWeT4WH/LoMWcJeTEo4NIRo47GqjyTyffta/m4v9K495.LKgVAJcjKskM.:1002:1003:,,,:/home/england:/bin/bash
scotland:$6$PvAZLH2mD5NTfGtI$4HYdb2c1/7smTU1OK.Fl5UBJsdwx0S20QAhx6b36jHPxhGQTQE9YEq8qb/1T0x42irdlF7uRIGOgj/5ELuFWv.:1003:1004:,,,:/home/scotland:/bin/bash
croatia:$6$ynLKp4ycKKapo3o1$6gURCexs5cL0uNfqnKQLSAL2JJEHr1MTq16WHHrcWIfL7vYjE86HReaQBZgLL0YvVhxOKGWUzUVTsmsVezwL9/:1004:1005:,,,:/home/croatia:/bin/bash
slovakia:$6$cmbew2k4yfISqGFh$asC/5Cw2v4hs76xih36cy8Y69cssDAHBByEngvpV/t7kC.pIiky0LTI8ICeRe6vPolqwawxV1ZKTgAYhXguWy.:1005:1006:,,,:/home/slovakia:/bin/bash
spain:$6$d4jFwDQcYiEWTpNr$iEfHg62Nao7yI4wDW5FATV2pbbcc0oL/lxtKCLAbdo4JO2/XOWr9RMZuNBDezxOPAHOmh9g//fsfC4f7w/yFl0:1006:1007:,,,:/home/spain:/bin/bash
sweden:$6$TKyej9Zbm.l2Du0n$r7572ERZzDKaZBxStaso5rJJkM435Z416qebPG2vhxQ8Ak4GVfdOcfh2ZGcWgxKPKsezMA6BCwMrNvi2p6d6N/:1007:1008:,,,:/home/sweden:/bin/bash
poland:$6$iIqKKM.2buc740Za$rs/6tgbvrpFYeeUPX0/62UxIBFfBqxVHz5wRR14Kk5gRJkfuB4Gvx44IvW1ogap4GnthSN7RJVKiOseYEZH4j1:1008:1009:,,,:/home/poland:/bin/bash
portugal:$6$nrZn0QN4KgsOfW96$NjpoAk4WOgeqaxaBUuSyzCamne0XSjY.SLLgnYxoQEnlQhr2mKbH0rHOhBTHKIt1NUZGuMpfaFR5oeNzxmd/c0:1009:1010:,,,:/home/portugal:/bin/bash
france:$6$TGByQYcWcFZC9E8e$C7XvNTVYrhyl2D7jpf2t.0h0Tb.qrSLqgikqPpZV0ALeTzabMezdoD5KBKO4MMlAm9woSAv5hfe/f8YoJoifZ1:1010:1011:,,,:/home/france:/bin/bash
germany:$6$J.dsxyFJUq/cIUS2$XvURhmAj6QooNZ7hUd2osNgycDeYnVrOMAUDF8C3FxkpeIAsN0Za0Yv4Hv6ah7sSdWH9Q2bfOGdvhQuSvMjo.0:1011:1012:,,,:/home/germany:/bin/bash
hungary:$6$pk1.ySvrRtpqJSHJ$/BOSLqcSueNIsrhAf/b46gR6qk1V34krQs3vWUag97RmQ0eeI0V2jIKyfUIRO9f3IwIHVLCg5XGU.l4w4cR3S.:1012:1013:,,,:/home/hungary:/bin/bash
</pre>

16 submissions across two classes.  The answers:
* (MD5) belgium:GME => 10 students cracked this
* (MD5) russia:rinforzanti => 15 students cracked this
* (MD5) italy:buela => 15 students cracked this
* (MD5) wales:ve3oao => 12 students cracked this
* (MD5) switzerland:nicole => 15 students cracked this
* (MD5) turkey:7771an => 10 students cracked this
* (MD5) finland:747690 => 8 students cracked this
* (MD5) denmark:fcimo8 => 3 students cracked this
* (MD5) netherlands:5ObePg => 2 students cracked this
* (MD5) ukraine:UJKVBXVI => 0 student cracked this
* (MD5) austria:LAlNzChRcJ => 0 student cracked this
* (MD5) nmacedonia:Wh@t3ver! => 0 student cracked this
* (SHA-512) czechrepublic:AMC => 12 students cracked this
* (SHA-512)england:H31icid43 => 9 students cracked this
* (SHA-512)scotland:Fiend => 12 students cracked this
* (SHA-512)croatia:Tristram => 13 students cracked this
* (SHA-512)slovakia:aaron431 => 12 students cracked this
* (SHA-512)spain:laak36 => 4 students cracked this
* (SHA-512)sweden:76394953 => 0 student cracked this
* (SHA-512)poland:ohfg => 3 students cracked this
* (SHA-512)portugal:OzHcji => 2 students cracked this
* (SHA-512)france:6RiZDfCXic => 0 student cracked this
* (SHA-512)germany:=[Jh~BPc4e => 0 student cracked this
* (SHA-512)hungary:k>Y.6%2JtD => 0 student cracked this

To earn all 10 / 10 points for the lab, students had to crack 8 or more passwords.  The final distribution:

<pre>
17
15
14
11 (x3)
10 (x2)
9 (x3)
8 (x2)
7
6
2
</pre>

Methodologies used:

<pre>Overall strategy:
I initially used John the Ripper, then switched to hashcat to check my work
and crack the longer hashes. I made liberal use of shell scripting to 
automate the cracking. 

Step-by-step:
I installed JtR and git cloned Daniel Miessler's SecLists. I tested some JtR 
commands and read the documentation, then tried my first crack. I separated 
the hashes into the 2 halves (using a hash identifier online to figure out 
the difference) and began john-the-ripping the first half (MD5). I wanted a 
wordlist (since wordlisting is the best way to crack passwords), and I 
know how much Ming likes darkc0de.txt, so I started with that and got a
few out of there. Then, I wrote a script that iterated through every 
.txt file in /SecLists/Passwords and used them as wordlists for JtR. I 
had to skip some of them because they were taking too long, so after a first
pass I wrote a second script which ran on a compiled version of every 
text file, concatenated, and ran it as a background process using nohup. 
I took a day or so, and I ended up with 6 passwords. 

I knew I would need some heavy-duty material to try the SHA512 half of 
the list, so I installed hashcat and tried it out. I wrote a similar 
script and started cracking using the full combined Passwords list. 
Truth be told, it is still running and is barely 15% done after 2 full 
days of pumping, but it's yeilded (blissfully) 5 passwords so far. I'll
submit more if I get them, and am also looking into brute-force attacking. 

I tried some stuff on the Tufts Cluster but found little success. Perhaps
I'll look at it again. 

Lastly, hashcat gave me the cracks as hash:password, so I had to manually
re-insert the usernames. Please forgive any errors in re-alignment.</pre>

<pre>Methodology: separated passwords into files for those encoded with MD5 and SHA512, then used john. First used basic wordlist, then downloaded a bunch of files from Daniel Miessler's SecLists and used those with John. Passwords above were found in: dutch_passwordlist, darkc0de, darkweb2017-top10000, xato-net-10-million-passwords-1000000, and the horrendously enormous wordlist I downloaded from crackstation.

I've tried a bit with hashcat but I'm mostly missing the SHA512 passwords now and John is a bit faster at those. I'm still plodding away with John on Kali on VMware - I have tried many times and wasted many hours trying to install John on native, both using a linux emulator and straight Windows, and cannot for the life of me get it to work - despite being a CS student, I am NOT tech inclined.</pre>

<pre>
My methodology was exceedingly simple. I started by googling any extra information and similar projects that I could find online
as references and jumping off points. I stumbled upon a certain blog with some very relevant information. I found that by far the 
most successful strategies were just throwing dictionaries and dictionaries and dictionaries at the hashes to see if anything sticks.
I spent about 10 minutes with a python script to try to download every dictionary off the seclists github repo that I could programatically
until I said screw it there aren't that many anyway and hand downloaded the raw files of each. I started with John The Ripper and used a GUI
called Johnny because I'm a weak, weak person. I threw all the dictionaries I could find at all of the hashes, obviously separated into
MD5 and SHA files using Johnny. 

I also found out that John the Ripper wants '.lst' files, which from research seem to be just Linux plaintext
files. My machine being Windows threw me a weird little quirk that took me a while to fix and I hope to save time for someone in the future if
they run into the same problem. You can download a '.txt' file and change the extension to '.lst', and John will accept the file UNLESS you open
the file even once with Notepad, which seems to leave artifacts in the file that violate the '.lst' protocol. So if you're using John on Windows
with '.txt' files, DON'T OPEN THEM!!!

After messing with dictionaries for a while to great success, which took me all the way into the 10/10 zone, I decided to just brute force and
see if I could get anything else. I got Hashcat working on my computer, which had some issues with my AMD graphics card, and having to use the
'-O' flag for optimized kernel mode. I used Hashcat since, from my research, Hashcat uses the GPU and John the CPU, and Hashcat has various
levels of 'intensity' on the device. I cranked that bad boy up and let it rip on both password files. I tried 6 and 7 character passwords with
the '?l', '?u', and '?d' default charsets, basically '[a-z][A-Z][0-9]'. This took about a week to finish, then I added in the '?s' special
character charset '[ !"$#.....]' and the expected time of completion rocketed up. I could do 6 character passwords with this extended alphabet,
and then stopped, because 7 character passwords were expected to take 330 days to exhaust. Goes to show how potent added special characters
to your password is, and structuring your password in such a way that a brute force attack is necessary. It got me thinking of going back
to all of my current passwords and appending a '
$$' string or something to the end, which I feel would make them significantly stronger.

So that was my overexplanation for a very simple strategy. Dictionaries, and when I ran out, brute force attacks of increasing complexity.
</pre>

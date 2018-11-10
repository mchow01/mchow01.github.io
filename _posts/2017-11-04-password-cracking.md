---
layout: post
title:  "Results of a Password Cracking Contest in My Security Class (Fall 2017)"
date:   2017-11-04 02:30:00
categories: education security
---

Each time I teach my Security class, I give a month-long lab to crack as many passwords as possible.  For this fall's contest [(opened on October 1, 2017 coinciding with the start of National Cyber Security Awareness Month](https://twitter.com/0xmchow/status/914531472656228354)), I used three different hash types: NTLM, MD5, and SHA-512.  The password hashes:

<pre>
nikita:$1$V4ULZp1H$igC3gPTV3ILlqDvGLCMpa0:1003:1003:,,,:/home/nikita:/bin/bash
chenxiwang:$1$gJVv0xlf$E7KalOk/W4kfiPNBYC/nq.:1004:1004:,,,:/home/chenxiwang:/bin/bash
smb:$1$v2iWpvgH$33JHK0x0VcB3OfMNDZNdU1:1005:1005:,,,:/home/smb:/bin/bash
hackingdave:$1$v.9cyqCo$om6cn4jLSUqLvYAjWkLN41:1006:1006:,,,:/home/hackingdave:/bin/bash
dotmudge:$1$yNugMXbd$lciJyrO3miEEYP3XqxjYB/:1007:1007:,,,:/home/dotmudge:/bin/bash
weldpond:$1$34i9e95R$bPUn.RdUhZdBanLmoQ.dj.:1008:1008:,,,:/home/weldpond:/bin/bash
deidrediamond:$1$QKvrOyAG$CtAVftor1hHUuAyafnPVP/:1009:1009:,,,:/home/deidrediamond:/bin/bash
infosecjen:$1$9tfnfmdo$jgb.GdFQ8Fmi.oUsPiDCU/:1010:1010:,,,:/home/infosecjen:/bin/bash
k8em0:$1$NXtXPorx$Ce9ZvYBQKRTvHd2wvugrG/:1011:1011:,,,:/home/k8em0:/bin/bash
sushidude:$6$dAOxGBKj$Hi79U8/0PvpwWKq1U/u4ISWe9F9qcF1fVnvH0mPJie3mEyAsv7HFZ9c6g4.MKVf.s2Tz/9fvKSzZCxM69D0Pl.:1000:1000:,,,:/home/sushidude:/bin/bash
wendynather:$6$FD4R/9co$oUgADRoJhVqxaARa9QAN/6rF0AUHxhiPyvGACn9DscXr5guTs1nQDY0cAmKsQoBPIt19kSfngTQ6NFQn5LMWX.:1001:1001:,,,:/home/wendynather:/bin/bash
mattblaze:$6$mpJ.ZoOT$1AOTS/HNOomsiUKlATToYYht9UbKmsrur9i8k.ikyBhG5LXpkEQdmYVgAnXVMSZGOHK5tZ6s11UddIcetESGS/:1002:1002:,,,:/home/mattblaze:/bin/bash
apiary:$6$SRnzcyQI$GLmHqVRq1GciikxRJFyLRUbHPy3Z1oSDOTVkOTr/sNBI9KqWc3sK6cROoJJ56noLZQRXutGTKe9T5.I9bvlwe/:1003:1003:,,,:/home/apiary:/bin/bash
chriseng:$6$Q1KGyrzr$NwifTEwMAtnqhkevWV43qmvSQzpn88L8IhJyDtfsz8PomYMDyRcq5xbfkwJ2Jj4NNgT2Xe0wru8ZjUaIEqpUJ.:1004:1004:,,,:/home/chriseng:/bin/bash
scarielli:$6$5M5VTz..$qL2lIAt5RVCZpSGQinwrE6y6oNEwjsDvHK3RxWpip68MXywP8DCVeReyEHJOgY8gg5G3NZFyMqwCrU/wrXFAv0:1005:1005:,,,:/home/scarielli:/bin/bash
tottenkoph:$6$19Ux3/Sz$XMuAt28YmR9w9IXTwODGe0DuWedvO.H05.ct8Xu7xZyj6BH4bTFxmYfYmZr22DTkxvLOXiAqoliJ23smYsJnd0:1006:1006:,,,:/home/tottenkoph:/bin/bash
erratarob:$6$eqnUKgsJ$2AdWNgZO3k1EVtU9Q348kipdc9GJ9Q35MtRKKgNjW5fduiNzbnCjqJAo9UBUjgxRtZwXyztD4CbPPhDQ15mHI1:1007:1007:,,,:/home/erratarob:/bin/bash
osuciohelen:$6$/sFoATOl$X6ve/u2MpudUUVe6zg1S.H1vxF0FIb/83TBOLwmGd6WJA4WJ65D2bqNVJ4gIcNSqsNrtkjnQouJv1xb.J5XfO.:1008:1008:,,,:/home/osuciohelen:/bin/bash
cigitalgem:1006:aad3b435b51404eeaad3b435b51404ee:b9f112f18a7a5b31b65d7358995d4165:::
gdead:1004:aad3b435b51404eeaad3b435b51404ee:6c8cc3ba8a3917512185052f7ef7525d:::
hacks4pancakes:1003:aad3b435b51404eeaad3b435b51404ee:c9b34ac1b90d8f73372fcb135d855034:::
jackdaniel:1005:aad3b435b51404eeaad3b435b51404ee:8327798cd80768bb5e8a0cc9159b3d11:::
malwareunicorn:1007:aad3b435b51404eeaad3b435b51404ee:267b0270c85cd7b4737f60393f8eefc8:::
selenakyle:1002:aad3b435b51404eeaad3b435b51404ee:82abea8bf22810b05bb009622df5c12c:::
</pre>

I combed through the submissions today: 88 total submissions.  The answers:

<pre>
(MD5) nikita:n3*T^o => 0 student cracked this
(MD5) chenxiwang:vi3%N^ => 0 student cracked this
(MD5) smb:J%Mi7e => 0 student cracked this
(MD5) hackingdave:xqksc => 47 student cracked this
(MD5) k8em0:jwhio => 57 student cracked this
(MD5) dotmudge:pzadc => 53 student cracked this
(MD5) weldpond:bcoei => 56 student cracked this
(MD5) deidrediamond:L!verpool => 21 student cracked this
(MD5) infosecjen:TeddyBear => 62 student cracked this
(SHA512) sushidude:9NfD => 5 student cracked this
(SHA512) wendynather:GnTb => 6 student cracked this
(SHA512) mattblaze:ssLpz5z => 0 student cracked this
(SHA512) apiary:Xbnedp => 0 student cracked this
(SHA512) chriseng:dFCYl8R => 0 student cracked this
(SHA512) scarielli:5WaNS1w => 0 student cracked this
(SHA512) tottenkoph:W7ad => 16 student cracked this
(SHA512) erratarob:@zGg => 3 student cracked this
(SHA512) osuciohelen:TheOhioStateUniversity => 0 student cracked this
(NTLM) selenakyle:loluwt0mg => 53 student cracked this
(NTLM) hacks4pancakes:Futbol82392 => 15 student cracked this
(NTLM) gdead:Trump => 68 student cracked this
(NTLM) jackdaniel:TheFalcao => 13 student cracked this
(NTLM) cigitalgem:Kermit123 => 60 student cracked this
(NTLM) malwareunicorn:harrypotter => 74 student cracked this
</pre>

The winner cracked 16 of the passwords.  The student's haul:

<pre>
$1$9tfnfmdo$jgb.GdFQ8Fmi.oUsPiDCU/:TeddyBear
$1$NXtXPorx$Ce9ZvYBQKRTvHd2wvugrG/:jwhio
$1$34i9e95R$bPUn.RdUhZdBanLmoQ.dj.:bcoei
$1$v.9cyqCo$om6cn4jLSUqLvYAjWkLN41:xqksc
$1$yNugMXbd$lciJyrO3miEEYP3XqxjYB/:pzadc
6c8cc3ba8a3917512185052f7ef7525d:Trump
267b0270c85cd7b4737f60393f8eefc8:harrypotter
b9f112f18a7a5b31b65d7358995d4165:Kermit123
c9b34ac1b90d8f73372fcb135d855034:Futbol82392
$1$QKvrOyAG$CtAVftor1hHUuAyafnPVP/:L!verpool
8327798cd80768bb5e8a0cc9159b3d11:TheFalcao
82abea8bf22810b05bb009622df5c12c:loluwt0mg
$6$dAOxGBKj$Hi79U8/0PvpwWKq1U/u4ISWe9F9qcF1fVnvH0mPJie3mEyAsv7HFZ9c6g4.MKVf.s2Tz/9fvKSzZCxM69D0Pl.:9NfD
$6$FD4R/9co$oUgADRoJhVqxaARa9QAN/6rF0AUHxhiPyvGACn9DscXr5guTs1nQDY0cAmKsQoBPIt19kSfngTQ6NFQn5LMWX.:GnTb
$6$19Ux3/Sz$XMuAt28YmR9w9IXTwODGe0DuWedvO.H05.ct8Xu7xZyj6BH4bTFxmYfYmZr22DTkxvLOXiAqoliJ23smYsJnd0:W7ad
$6$eqnUKgsJ$2AdWNgZO3k1EVtU9Q348kipdc9GJ9Q35MtRKKgNjW5fduiNzbnCjqJAo9UBUjgxRtZwXyztD4CbPPhDQ15mHI1:@zGg
</pre>

The student's methodology:

>Mostly dictionary attacks using hashcat on my GPU; I ran john for quite a while on CPU in parallel, but it didn't manage to get any of the passwords.  
>
>Wordlists that produced a lot of passwords:
>  - rockyou
>  - HashesOrg
>  - Also used phpbb, top1000000, Nummer_DB
>Rule sets that produced a lot of passwords:
>  - OneRuleToRuleThemAll (https://github.com/NotSoSecure/password_cracking_rules)
>  - d3adhob0 (https://github.com/praetorian-inc/Hob0Rules)
>  - best64 and hob064
>
>A few of the passwords came from brute force, which I ran on NTLM and MD5 because it was fairly fast for short passwords, and on 4 character passwords with SHA512 because I got a couple of them from HashesOrg and took a guess that there might be more, given that (for the other passwords I had cracked) many of the passwords within a given hash function were of the same length.
>
>Overall conclusions: good hash functions and salting don't fix bad passwords, but they do help -- the 4-character SHA512 passwords would have been trivial to break if they were hashed with NTLM (or even MD5), but they ended up being some of the last ones I cracked.
>
>Exact notes about what managed to crack each of the hashes, in (roughly) the order in which I cracked them:
>
>$1$9tfnfmdo$jgb.GdFQ8Fmi.oUsPiDCU/:TeddyBear
>    MD5 -- cracked with Hashcat using the Rockyou password dictionary
>$1$NXtXPorx$Ce9ZvYBQKRTvHd2wvugrG/:jwhio
>    MD5 -- cracked with Hashcat using Rockyou dictionary and best64 rules
>$1$v.9cyqCo$om6cn4jLSUqLvYAjWkLN41:xqksc
>    MD5 -- cracked with Hashcat, brute force
>$1$yNugMXbd$lciJyrO3miEEYP3XqxjYB/:pzadc
>    MD5 -- cracked with Hashcat, brute force
>6c8cc3ba8a3917512185052f7ef7525d:Trump
>    NTLM -- cracked with Hashcat, brute force
>267b0270c85cd7b4737f60393f8eefc8:harrypotter
>b9f112f18a7a5b31b65d7358995d4165:Kermit123
>c9b34ac1b90d8f73372fcb135d855034:Futbol82392
>    All broken with Hashcat, Rockyou dictionary and d3adhob0 rules
>$1$QKvrOyAG$CtAVftor1hHUuAyafnPVP/:L!verpool
>$1$34i9e95R$bPUn.RdUhZdBanLmoQ.dj.:bcoei
>    Broken with Hashcat, Rockyou dictionary and d3adhob0 rules
>8327798cd80768bb5e8a0cc9159b3d11:TheFalcao
>    Broken with Hashcat, phpbb and OneRule
>82abea8bf22810b05bb009622df5c12c:loluwt0mg
>    Broken with Hashcat, HashesOrg and hob064
>$6$dAOxGBKj$Hi79U8/0PvpwWKq1U/u4ISWe9F9qcF1fVnvH0mPJie3mEyAsv7HFZ9c6g4.MKVf.s2Tz/9fvKSzZCxM69D0Pl.:9NfD
>$6$FD4R/9co$oUgADRoJhVqxaARa9QAN/6rF0AUHxhiPyvGACn9DscXr5guTs1nQDY0cAmKsQoBPIt19kSfngTQ6NFQn5LMWX.:GnTb
>$6$19Ux3/Sz$XMuAt28YmR9w9IXTwODGe0DuWedvO.H05.ct8Xu7xZyj6BH4bTFxmYfYmZr22DTkxvLOXiAqoliJ23smYsJnd0:W7ad
>    Broken with Hashcat, HashesOrg
>$6$eqnUKgsJ$2AdWNgZO3k1EVtU9Q348kipdc9GJ9Q35MtRKKgNjW5fduiNzbnCjqJAo9UBUjgxRtZwXyztD4CbPPhDQ15mHI1:@zGg
>    Broken with Hashcat, brute force on ?a?a?a?a"
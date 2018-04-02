---
layout: post
title:  "Results of a Password Cracking Contest for My Security Class (Spring 2018)"
date:   2018-04-02 00:15:00
categories: education security
---

Each time I teach my Security class, I give a month-long lab to crack as many passwords as possible.  For this spring's contest [(opened on February 25, 2018](https://twitter.com/0xmchow/status/967850845042806784)), I used three different hash types: NTLM, MD5, and SHA-512.  The password hashes:

<pre>
yogiduke:$1$Q4g60Y/B$yDThQ6BWKsSjaqMNNbNi2/:1003:1003:,,,:/home/yogiduke:/bin/bash
bigduke:$1$WCay.hxX$wMX2c3Yl0n6rv5ddIXAlT.:1004:1004:,,,:/home/bigduke:/bin/bash
grizzlyduke:$1$B.wi/t0Z$fQo.rAwvW5JCiCCpC7F2Y0:1005:1005:,,,:/home/grizzlyduke:/bin/bash
pandaduke:$1$lnbM4Z4i$gjOjE0BasRIGK0t90YrlI1:1006:1006:,,,:/home/pandaduke:/bin/bash
foofooduke:$1$qQ0SGhrr$qNJ/02Xz5RyHZnqM55AYr.:1007:1007:,,,:/home/foofooduke:/bin/bash
yolandaduke:$1$GJ5zceLI$3HJuSAi4KZ0SpECJ1EmfZ/:1008:1008:,,,:/home/yolandaduke:/bin/bash
fancyduke:$1$CDnK9/E6$ceO1FS7ptGOf1oOijIPw9/:1009:1009:,,,:/home/fancyduke:/bin/bash
jojoduke:$1$9HuHlpfc$ibFX5EwhDScIUWOqsKA4O0:1010:1010:,,,:/home/jojoduke:/bin/bash
peachduke:$1$s3s.Cz2k$nQIZ9RN2Fo8obJ4LjqPBP.:1011:1011:,,,:/home/peachduke:/bin/bash
edrojas:$1$0WxFBCft$e.p0B2NEAe3zaxk1cTTxs/:1012:1012:,,,:/home/edrojas:/bin/bash
smokeyduke:$6$Y75XiK8o$GC2LhHRituUUiZN4ktd5BkUZ67MsVZbXLlBRiy4cHMpLEe5mzrpbhCJ.H2uYwK8P7d12YBeo0WxudkomGH4dW0:1000:1000:,,,:/home/smokeyduke:/bin/bash
cocoduke:$6$Pu9iyDgq$n2jGnAH.y9FpPbg0QuPfh7K0G1ChbC1t8SYhHjIzqXP9qYZW0bCBrcDWSuASD3gUKSEhjCMkfPrLXP.zjCwj0.:1001:1001:,,,:/home/cocoduke:/bin/bash
yetiduke:$6$oVK2jXhT$FaoOoa/hZC1EUC02eV5wPPdrBpHLmeuAlVBKnDZ6y9SPlJIQNR.IYA5EAGQ1g.peV0doX827A/rntRLmhJnNr0:1002:1002:,,,:/home/yetiduke:/bin/bash
blackduke:$6$.X8Oq/..$iSWqEyTmqtJp7Zgu9X6/6v7iy7ezXR7tEeTge5U/RnytN12s1rorG5a3JTLeIL5rX.Xw73COhSz3oxCFGrbzy.:1003:1003:,,,:/home/blackduke:/bin/bash
fozzieduke:$6$.yevPHBB$pZe2PugvY6X4V08ZYUUj7HOHQaHGLArtOj8Ho1HofRtXM5IGjW7cRH2zUOm4opVfCYKI2NY/5vE4XFDsv9d1b.:1004:1004:,,,:/home/fozzieduke:/bin/bash
pedroduke:$6$Q4AmBVZL$mZYFGKmUGYNPwDPjBqhnCKotqdQLb/S9bmvS71WjPfE1JHTSiZd9VMG0hvjQscaHkcXiT3ur.UAtVUcs1TrkL0:1005:1005:,,,:/home/pedroduke:/bin/bash
willyduke:$6$anfRBH3H$OzYRbdfHoB3p1KuEMTv1bTEiIKFb/I7TMaasal0nfkAetojQ0JkkqEEv9i/a38kYqzJgRqzKPYqm0km3o7bBf.:1006:1006:,,,:/home/willyduke:/bin/bash
blinkyduke:$6$C8UU6E8.$aBr7aHZLRkczaHPzuRnGhuafYOoIpEXWr8eu2ZL7lnI608UKeVobrK7qJFl/VYw6c4vF0MIvPR4E1FKYLQqMa0:1007:1007:,,,:/home/blinkyduke:/bin/bash
slothduke:$6$CyRswJbB$Cm04byuMqxJNoytaSN9YO7lbV4f2vFx8M2gZATpjxv9msP2MYv8oQ8NKduoic3qc5YGe4wpVM030iGyQ.TTjm/:1008:1008:,,,:/home/slothduke:/bin/bash
cacaduke:1010:aad3b435b51404eeaad3b435b51404ee:f442c6b2efcfa296065eb8e83738cc3a:::
chicagoduke:1009:aad3b435b51404eeaad3b435b51404ee:79fddffd223d7cde00a628adbf6bd045:::
cozyduke:1008:aad3b435b51404eeaad3b435b51404ee:01dbbbe2cce034344fdc4d28c4c398ca:::
crazyduke:1012:aad3b435b51404eeaad3b435b51404ee:8e09a2c04e8822da6157d4c89af9f5fd:::
edrojasagain:1013:aad3b435b51404eeaad3b435b51404ee:5a7d64eb4bd95a67ea4feb6783e87aa9:::
teddyduke:1011:aad3b435b51404eeaad3b435b51404ee:ff7ac54a5de4e2819dcb3160f3cb9eea:::
</pre>

I combed through the submissions today: 73 total submissions.  The answers:

<pre>
(MD5) yogiduke:oE48YD => 0 student cracked this
(MD5) bigduke:uqKvwZ => 0 student cracked this
(MD5) grizzlyduke:wardere => 59 student cracked this
(MD5) pandaduke:tmann16 => 48 student cracked this
(MD5) foofooduke:w3chLp => 0 student cracked this
(MD5) yolandaduke:Ca5S%! => 0 student cracked this
(MD5) fancyduke:cMJ9cYe9t => 0 student cracked this
(MD5) jojoduke:BdyuZ6Tqh => 0 student cracked this
(MD5) peachduke:jY@3%q$M65 => 0 student cracked this
(MD5) edrojas:L!verp00l => 47 student cracked this
(SHA512) smokeyduke:8nfJ => 5 student cracked this
(SHA512) cocoduke:tLUR => 10 student cracked this
(SHA512) yetiduke:ferraro => 49 student cracked this
(SHA512) blackduke:123kat => 50 student cracked this
(SHA512) fozzieduke:Q7Fqyc => 0 student cracked this
(SHA512) pedroduke:N&8Lgz => 0 student cracked this
(SHA512) willyduke:sUqQJ3nr2 => 0 student cracked this
(SHA512) blinkyduke:hsh4BJJ3v => 0 student cracked this
(SHA512) slothduke:S6t?c?DmUw => 0 student cracked this
(NTLM) cozyduke:M6E3 => 59 student cracked this
(NTLM) chicagoduke:v5a1 => 59 student cracked this
(NTLM) cacaduke:zr4LmK => 49 student cracked this
(NTLM) teddyduke:Yj-4@!k => 33 student cracked this
(NTLM)crazyduke:Wkf6Fm3PU => 0 student cracked this
(NTLM) edrojasagain:HumanHorn => 9 student cracked this
</pre>

The winner cracked 12 of the passwords.  The student's haul:

<pre>
edrojas:L!verp00l        Using hashcat, a and rockyou
chicagoduke:v5a1            
cozyduke:M6E3                 Using hashcat, rockyou, and OneRule
cacaduke:zr4LmK          Hashcat, mask attack on ?a?a?a?a?a?a
pandaduke:tmann16       Hashcat, dic attack using realhuman_phill.txt
grizzlyduke:wardere   
blackduke:123kat        Using hashcat and Rockyou dictionary
smokeyduke:8nfJ                Using hashcat mask on ?a?a?a?a
cocoduke:tLUR
yetiduke:ferraro        Hashcat, dic attack using realhuman_phill.txt
edrojasagain:HumanHorn        Rainbow cracks on a large downloaded table
teddyduke:Yj-4@!k
</pre>

The student's methodology:

>I started off looking at the password cracking contest from previous years, ran all the hashes through the rockyou dictionary, and then used rule sets. I ending up trying some masks and a huge password list because I was stuck, and finally I tried out rainbow cracks because I hadn't gotten a ton of hits on the NTLM.

Looking at password cracking contest from previous years was very very smart!
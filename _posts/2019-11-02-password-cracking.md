---
layout: post
title:  "Results of a Password Cracking Contest in My Security Class (Fall 2019)"
date:   2019-11-02 03:00:00
categories: education security
---

Each time I teach my Security class, I give a month-long lab to crack as many passwords as possible.  For this fall's contest [(opened on October 1, 2019](https://twitter.com/0xmchow/status/1179054428315238402)), I used three different hash types: NTLM, MD5, and SHA-512.  The password hashes (31 total):

<pre>
mandyrose:$1$AXkQpCFa$kDEG2XXJpV2dmTZ8SCub5.:1003:1003:,,,:/home/mandyrose:/bin/bash
sonyadeville:$1$U/Yg2ZCq$LJtkO9Io31eqLggcSymd21:1004:1004:,,,:/home/sonyadeville:/bin/bash
mickiejames:$1$i1Ci.hwp$PzVoXQqp4dwqdrjgO.5341:1005:1005:,,,:/home/mickiejames:/bin/bash
undertaker:$1$jnWrDSGR$EqfKT7EvmsIm6EEr3CIBd1:1006:1006:,,,:/home/undertaker:/bin/bash
dolphziggler:$1$nujempjs$yRCaYrrWfispxFMIYujTB1:1007:1007:,,,:/home/dolphziggler:/bin/bash
randyorton:$1$gewhx8T6$QaMbFG6yn8Yf5QyZ./07W1:1008:1008:,,,:/home/randyorton:/bin/bash
brocklesnar:$1$kIMbN6/5$FnwGnfILTDZYZecRGWtQF.:1009:1009:,,,:/home/brocklesnar:/bin/bash
kevinowens:$1$yJuiQa.L$N0yi9tKHoOpRFVT8d7PmI0:1010:1010:,,,:/home/kevinowens:/bin/bash
rubyriott:$1$OkgKL/ku$uCcAawCg5ZhAZ48GxBVha0:1011:1011:,,,:/home/rubyriott:/bin/bash
shanemcmahon:$1$0vgU0gEM$F/WSFxNDI4Ml8zCSt4inv/:1012:1012:,,,:/home/shanemcmahon:/bin/bash
beckylynch:$1$Os6w5Mjj$nj1G76vpvYYvMYWJDl1me/:1013:1013:,,,:/home/beckylynch:/bin/bash
bobbyroode:$1$XV7vBCHp$MidzkJpBTa6hssOrojlT7.:1014:1014:,,,:/home/bobbyroode:/bin/bash
finnbalor:$6$FPWMg52D$UTvhC9mNxL4bqHfueA.bxLxrmoQTQ1cJCcFs5FjCWu0ZvXOTQfXpaR7qVXNCS8EwUjS9y5l3KOVTykNPmJ/Mo1:1001:1003:,,,:/home/finnbalor:/bin/bash
carmella:$6$DzR0UL5l$TQfN1x2YmGrgHgSWuuXPXHI/GATBXuE5/NzQdrVyJ4arg7Xwusdq5tzcdI.gak.Q8jKN2Q8JRg5jzf5l7nmln1:1002:1004:,,,:/home/carmella:/bin/bash
nikkicross:$6$4AaXs8NV$HtVqIoGxwVt4h3.CbStEiswY7LpvVyQQOwcHDAWuIbaKZ.AVVm8ZIVSf3LuiijtAntWl93RjcmuAZ18ATZzrP0:1003:1005:,,,:/home/nikkicross:/bin/bash
alexabliss:$6$jALxie.T$8Zk3YqLVKudMi86i3ZfuSBENUK8PeT.ykWjZRJdNFXEI9HigUzo4beFyVOWlTlk4RkSKH3.A.m3fzCxcJu8ux1:1004:1006:,,,:/home/alexabliss:/bin/bash
rondarousey:$6$HGNY0QKz$ywBM50wVU4GTE/bALnnYLFWlrznfi.soaMxz2Z1Fa6A1Wqke6t.VObYhe5z1QQQFg.3tkjfKQWkvBdtH1p.rJ1:1005:1007:,,,:/home/rondarousey:/bin/bash
kofikingston:$6$cSGHHJ6/$ArOrkac2D.S96lReZlDsBaCg8MRAF0IXSa0XSd5g8AIUWjbdHy6gbSu5FPImNVfGzQFlkftcPgAmkoamLAHIc0:1006:1008:,,,:/home/kofikingston:/bin/bash
ajstyles:$6$LahA3R9.$qCi9mF27SU56e1ETeBGgC2IyTPob93Q97Nt9eD9FhoEjOjpbg9ioZD3oBoRJmjmfqSUmURbOgPr/C9tagiFeF/:1007:1009:,,,:/home/ajstyles:/bin/bash
sashabanks:$6$zOdwQRRp$6JSzdyV0T1HgLcy6TrvWBQmxLZ7I4sku7UwHKDoXcALt/Low78.ZtLxlimdzjywLanU4a5pxWWGtgfcUnu71/.:1008:1010:,,,:/home/sashabanks:/bin/bash
braywyatt:$6$qi0MAYqP$gZ8CSKQfez64WNneOg9Hb.IzK2/svlDw1I6NrEUvPvtsgIP2gSMYEmRdgfhVISPmCtkPmruxL73Fy9lgKeqHn0:1009:1011:,,,:/home/braywyatt:/bin/bash
themiz:$6$9lFFAgZh$/LuGXIjLp5GKSBxDbXYMsNvnQQkKCuHfHpqr3GUxwM0FEDRFvg4PDlg15tS214JSEotzeAM/ISkivjE8tLSHN/:1010:1012:,,,:/home/themiz:/bin/bash
sethrollins:$6$pDwy44Uh$9yDYrqwBDpoo8.DISjReroJvCu4rU0ZWvTOzjAfZsBDyxoLD9VP3eY2S/U1ckDEOnDGIyN.QKJvTK8vpl12sR/:1011:1013:,,,:/home/sethrollins:/bin/bash
romanreigns:$6$d0WGbMSd$uoCKOxV6QxW5TL57bXcoer86HGbhuLKsaIoKlX0aZ1K2WtN50I4p6hOE0L6p4mgJFX5TylrkBGF59/btoXG7/0:1012:1014:,,,:/home/romanreigns:/bin/bash
defcon:1000:aad3b435b51404eeaad3b435b51404ee:e19ccf75ee54e06b06a5907af13cef42:::
bayley:1002:aad3b435b51404eeaad3b435b51404ee:41a143c6de2051140d0bd20857a5ac3c:::
charlotteflair:1001:aad3b435b51404eeaad3b435b51404ee:3c40bcdda7f702b24803624dbfc9960f:::
danabrooke:1004:aad3b435b51404eeaad3b435b51404ee:aec43b5f0b3d0a16e607e4d45de9d00f:::
embermoon:1005:aad3b435b51404eeaad3b435b51404ee:40a958b5dfc3be966447be12399642c7:::
johncena:1003:aad3b435b51404eeaad3b435b51404ee:8d4a914f69b6c2d1b28094c587b13f60:::
niajax:1006:aad3b435b51404eeaad3b435b51404ee:d6d3832a59bc7e57c9ee08f46756d3ab:::
</pre>

79 total submissions.  The answers:

* (MD5) mandyrose:q59dds => 5 students cracked this
* (MD5) sonyadeville:YIM1 => 16 students cracked this
* (MD5) mickiejames:Zz6.Ud;Y => 0 students cracked this
* (MD5) undertaker:L!verpool => 20 students cracked this
* (MD5) dolphziggler:V':UQTe3XMan=P6 => 0 students cracked this
* (MD5) randyorton:divvsdivu => 48 students cracked this
* (MD5) brocklesnar:v2p6jc => 7 students cracked this
* (MD5) kevinowens:game-destroying => 45 students cracked this
* (MD5) rubyriott:re2404 => 21 students cracked this
* (MD5) shanemcmahon:kJmL => 13 students cracked this
* (MD5) beckylynch:sojjjsojj9 => 38 students cracked this
* (MD5) bobbyroode:abc123 => 78 students cracked this
* (SHA-512) finnbalor:frobnitz => 41 students cracked this
* (SHA-512) carmella:VG;q => 5 students cracked this
* (SHA-512) nikkicross:neMG1Dak => 0 students cracked this
* (SHA-512) alexabliss:Mlsw => 6 students cracked this
* (SHA-512) rondarousey:yagubets1d => 37 students cracked this
* (SHA-512) kofikingston:eCauGt6V => 0 students cracked this
* (SHA-512) ajstyles:syphilitic => 27 students cracked this
* (SHA-512) sashabanks:im46in312 => 16 students cracked this
* (SHA-512) braywyatt:5pin873 => 20 students cracked this
* (SHA-512) themiz:p3yh28 => 3 students cracked this
* (SHA-512) sethrollins:kane311 => 20 students cracked this
* (SHA-512) romanreigns:11128 => 50 students cracked this
* (NTLM) defcon:P@ssw0rd => 62 students cracked this
* (NTLM) charlotteflair:L7L8oPwK => 3 students cracked this
* (NTLM) bayley:pD{E5}kj => 0 students cracked this
* (NTLM) johncena:CU6rn}a4 => 0 students cracked this
* (NTLM) danabrooke:Gopal => 62 students cracked this
* (NTLM) embermoon:yaruga7 => 65 students cracked this
* (NTLM) niajax:Competitive => 45 students cracked this

To earn all 10 points for the lab, students had to crack 8 passwords.  The final distribution:

<pre>
25 25 (2 total)
23 23 23 (3 total)
18 (1 total)
15 (1 total)
14 14 14 (3 total)
13 13 13 (3 total)
12 12 (2 total)
11 11 11 11 11 (5 total)
10 10 10 10 10 10 10 (7 total)
9 9 9 9 9 9 9 9 9 9 (10 total)
8 8 8 8 8 8 8 8 8 8 8 8 8 8 8 8 8 8 8 8 8 8 8 8 (24 total)
7 7 7 7 7 7 7 (7 total)
6 6 6 (3 total)
4 4 (2 total)
3 3 3 (3 total)
2 2 (2 total)
1 (1 total)
</pre>

The winners (tied) cracked 25 of the 31 passwords.

Winner 1's haul and methodology:
> Gopal                                    – Hash Suite – Facebook wordlist + rules
> yaruga7                 – Hash Suite
> abc123                  – Hashcat – 10 mil + best64
> P@ssw0rd                           – Hashcat – 10 mil + best64
> re2404                  – Hash Suite
> frobnitz                 – Hashcat – 10 mil + best64
> 11128                                    – Hashcat – 10 mil
> yagubets1d                        – Hashcat – 10 mil + best64
> Mlsw                                     – Hashcat – Brute Force
> q59dds                 – Hashcat – Brute Force
> p3yh28                 – Hashcat – Brute Force
> v2p6jc                                   – Hashcat – Brute Force
> YIM1                                      – Hashcat – Brute Force
> kJmL                                      – Hashcat – Brute Force
> VG;q                                      – Hashcat – Brute Force
> L!verpool                             – Hashcat – 10 mil + hob064
> sojjjsojj9                              – Hashcat – 10 mil + hob064/ORTRTA
> kane311                               – I don’t remember
> Competitive                       – Hashcat – English dictionary + best64/hob064
> L7L8oPwK                            – I don’t remember
> divvsdivu                             – Hashcat – 700 MB wordlist + best64/hob064
> 5pin873                                – Hashcat – 700 MB wordlist + best64/hob064
> im46in312                            – Hashcat – 700 MB wordlist + best64/hob064
> syphilitic                               – Hashcat – English dictionary + best64/hob064
> game-destroying             – Hashcat – English dictionary + best64/hob064
> 
> I initially used Hash Suite as starting unable to setup Hashcat. But I don’t recommend it.

Winner 2's haul and methodology:
> bobbyroode:abc123 => Using john the ripper without wordlists
> defcon:P@ssw0rd => https://hashkiller.co.uk/Cracker/NTLM
> danabrooke:Gopal => https://hashkiller.co.uk/Cracker/NTLM
> embermoon:yaruga7 => https://hashkiller.co.uk/Cracker/NTLM
> beckylynch:sojjjsojj9 => Hashcat with 10-million-wordlist
> undertaker:L!verpool => Hashcat with 10-million-wordlist and rules
> romanreigns:11128 => Hashcat with rockyou.txt
> sethrollins:kane311 => Hashcat with rockyou.txt and best064 rules
> niajax:Competitive => Hashcat, 10-million passwords, ORTRTA
> charlotteflair:L7L8oPwK => Hashcat, brute force 8 character alphanumeric strings on gCloud
> randyorton:divvsdivu => Hashcat, Crackstation list, hob064 rule
> kevinowens:game-destroying => Crackstation list, ORTRTA
> braywyatt:5pin873 => Hashcat, 15GB wordlist
> sashabanks:im46in312 => Hashcat, 15GB wordlist
> ajstyles:syphilitic => Crackstation list
> rubyriott:re2404 => brute force alphanumeric
> finnbalor:frobnitz => Wordlists with rules
> rondarousey:yagubets1d => Wordlists with rules
> alexabliss:Mlsw => brute force alphanumeric
> andyrose:q59dds => Wordlists with rules
> themiz:p3yh28 => Wordlists with rules
> brocklesnar:v2p6jc => Wordlists with rules
> sonyadeville:YIM1 => brute force alphanumeric
> shanemcmahon:kJmL => brute force alphanumeric
> carmella:VG;q => brute force special chars

> My method was as follows. Follow this tutorial (gist.github.com/koenrh/801766782fe65b279b436576d935d5d3) to set up Google Cloud GPUs. Then, run Crackstations 15GB wordlist through it (https://crackstation.net/crackstation-wordlist-password-cracking-dictionary.htm. Obviously you want to use rules, to keep it simple: Use short rules for hard to crack hashes such as SHA512 (https://github.com/praetorian-code/Hob0Rules/blob/master/hob064.rule, and use more extensive rules for faster hashes like NTLM (https://github.com/NotSoSecure/password_cracking_rules.

Runner up 1's haul and methodology:
> Rockyou.txt wordlist with best64 rule
> $1$XV7vBCHp$MidzkJpBTa6hssOrojlT7.:abc123 
> $1$jnWrDSGR$EqfKT7EvmsIm6EEr3CIBd1:L!verpool 
> $6$d0WGbMSd$uoCKOxV6QxW5TL57bXcoer86HGbhuLKsaIoKlX0aZ1K2WtN50I4p6hOE0L6p4mgJFX5TylrkBGF59/btoXG7/0:11128
> aec43b5f0b3d0a16e607e4d45de9d00f:Gopal
> e19ccf75ee54e06b06a5907af13cef42:P@ssw0rd
> 40a958b5dfc3be966447be12399642c7:yaruga7
> d6d3832a59bc7e57c9ee08f46756d3ab:Competitive
> 
> HashesOrg wordlist, no rule
> $1$gewhx8T6$QaMbFG6yn8Yf5QyZ./07W1:divvsdivu
> $1$yJuiQa.L$N0yi9tKHoOpRFVT8d7PmI0:game-destroying
> $1$0vgU0gEM$F/WSFxNDI4Ml8zCSt4inv/:kJmL
> $1$U/Yg2ZCq$LJtkO9Io31eqLggcSymd21:YIM1
> 
> $6$qi0MAYqP$gZ8CSKQfez64WNneOg9Hb.IzK2/svlDw1I6NrEUvPvtsgIP2gSMYEmRdgfhVISPmCtkPmruxL73Fy9lgKeqHn0:5pin873
> 
> $6$FPWMg52D$UTvhC9mNxL4bqHfueA.bxLxrmoQTQ1cJCcFs5FjCWu0ZvXOTQfXpaR7qVXNCS8EwUjS9y5l3KOVTykNPmJ/Mo1:frobnitz
> 
> $6$zOdwQRRp$6JSzdyV0T1HgLcy6TrvWBQmxLZ7I4sku7UwHKDoXcALt/Low78.ZtLxlimdzjywLanU4a5pxWWGtgfcUnu71/.:im46in312
> 
> $6$jALxie.T$8Zk3YqLVKudMi86i3ZfuSBENUK8PeT.ykWjZRJdNFXEI9HigUzo4beFyVOWlTlk4RkSKH3.A.m3fzCxcJu8ux1:Mlsw
> 
> $6$LahA3R9.$qCi9mF27SU56e1ETeBGgC2IyTPob93Q97Nt9eD9FhoEjOjpbg9ioZD3oBoRJmjmfqSUmURbOgPr/C9tagiFeF/:syphilitic
> 
> HashesOrg
>  wordlist, best64 rule
> 
> $1$OkgKL/ku$uCcAawCg5ZhAZ48GxBVha0:re2404
> 
> $1$AXkQpCFa$kDEG2XXJpV2dmTZ8SCub5.:q59dds
> 
> SkullSecurity Wordlist, best64 rule
> 
> $1$Os6w5Mjj$nj1G76vpvYYvMYWJDl1me/:sojjjsojj9
> 
> $6$HGNY0QKz$ywBM50wVU4GTE/bALnnYLFWlrznfi.soaMxz2Z1Fa6A1Wqke6t.VObYhe5z1QQQFg.3tkjfKQWkvBdtH1p.rJ1:yagubets1d
> 
> NummerDB wordlist, no rules
> 
> $6$pDwy44Uh$9yDYrqwBDpoo8.DISjReroJvCu4rU0ZWvTOzjAfZsBDyxoLD9VP3eY2S/U1ckDEOnDGIyN.QKJvTK8vpl12sR/:kane311
> 
> NummerDB wordlist, OneRuleToRuleThemAll rule
> 
> 3c40bcdda7f702b24803624dbfc9960f:L7L8oPwK
> 
> Brute force, ?a?a?a?a?a
> 
> $1$kIMbN6/5$FnwGnfILTDZYZecRGWtQF.:v2p6j
> 
> Brute force, ?a?a?a?a
> 
> $6$DzR0UL5l$TQfN1x2YmGrgHgSWuuXPXHI/GATBXuE5/NzQdrVyJ4arg7Xwusdq5tzcdI.gak.Q8jKN2Q8JRg5jzf5l7nmln1:VG;q

Runner up 2's methodology:
>First, I downloaded hashcat on my personal computer (MacBook Pro 2016 with 16GB RAM) and ran the different collections of hashes (MD5, SHA512crypt, NTLM) in three different terminal windows with the SecList directory of passwords. Once that was exhausted, I downloaded other various multi-GB dictionary files and used them for other vanilla dictionary attacks. Once those were all exhausted, I tried masked attacks on the hashes with the “?a” mask (lowercase, uppercase, numerical, and special characters) with incrementing lengths for possible passwords. I gave up once I reached a time estimate of ~2 years for finishing the mask attack for a certain password length.

Runner up 3's methodology:
> I first began by using online tools for the NTLM passwords to obtain 4/31 passwords. Then I used John the Ripper and over 100GB of password lists (many came from: https://thehacktoday.com/password-cracking-dictionarys-download-for-free/ (Links to an external site.)) to reach 19/31 by cracking a total of 15 MD5 and SHA512 passwords. I used the same lists on the NTLM passwords with Hashcat, but had no luck. At this point, I started a brute force approach to try to ensure that no short passwords slipped through. I ultimately cracked a total of 4 more MD5 and SHA512 passwords, bringing my total to 23. I also tried brute force on NTLM but had no luck. Finally, I tried rules with Hashcat (hob064 and ORTRTA) on all categories but had no luck. Ultimately, I started about 10 days late used only my own hardware, so I am pleased with the results. But, I am surprised that I did not have better luck with the NTLM passwords.
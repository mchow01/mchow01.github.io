---
layout: post
title:  "Results of a Password Cracking Contest in My Online Security Class (Summer 2017)"
date:   2017-08-15 01:00:00
categories: education security
---

I offered my [Introduction to Computer Security](https://tuftsdev.github.io/DefenseAgainstTheDarkArts) class as an online course for the first time.  I give a month-long summer lab to crack as many passwords as possible.  For this summer's contest [(opened on July 3, 2017](https://twitter.com/0xmchow/status/882073476886089731)), I used three different hash types: NTLM, MD5, and SHA-512.  The password hashes:

<pre>
chicagobear:$1$P3QnPJRC$ZiUGVezmZmHP3FwGBrSvx0:1003:1003:,,,:/home/chicagobear:/bin/bash
bigbear:$1$0HXmPq6a$b6SJ9SFllGgOz2dU/J1t1.:1004:1004:,,,:/home/bigbear:/bin/bash
jojobear:$1$iSCIcnDl$GhUJv320ZA7aEkmFlLBRb/:1005:1005:,,,:/home/jojobear:/bin/bash
crazybear:$1$Ojbempgo$5GSSpK2r2McB8pyfhsEiy0:1006:1006:,,,:/home/crazybear:/bin/bash
slothbear:$1$nTQQPLJE$go2/.YC/4evqQKE4fPIiB0:1007:1007:,,,:/home/slothbear:/bin/bash
cocobear:$1$xLkX79Xq$gVMgVkhzjkGODtL79NgLY0:1008:1008:,,,:/home/cocobear:/bin/bash
willybear:$1$RdCmq9HN$YhybIiTYwSjywxTotYub4/:1009:1009:,,,:/home/willybear:/bin/bash
yogibear:$1$s.vVsfIL$YWZ.49mClunDlkJapYKZ1/:1010:1010:,,,:/home/yogibear:/bin/bash
blackbear:$6$xGcUMQHK$eOPlvJwoLa3BIrDwHb9k5g3TyukWnmMgXlG6rXc/JiEeBTQ1GMzbm.6jHsxO1ofsMp.PbTVdMQqKDIlCQcfmz0:1000:1000:,,,:/home/blackbear:/bin/bash
blinkybear:$6$Ga52kSM3$3T6ri0./UFR6V/6ICzMX1wB.GG26eKpP2HhaQUpQKTzKfSwqWaTK4CX8kyjwZZA4PH2ns5oH6SrxHMImg.kfb/:1001:1001:,,,:/home/blinkybear:/bin/bash
cacabear:$6$GSEyFgvt$CUjBn1cspBlxmi0YZbFHs.JfR/6FIzh8RRUMhXIYQZXherSbluLlehghZ3Yi2Su2TazjMg3aRNj4V9mWDyhgA1:1002:1002:,,,:/home/cacabear:/bin/bash
cozybear:$6$QklnyMgo$b0MQ9qJwyCjVG7txLANcH2a49h/f5KcA5eoS82T7IKRJqmGWHqO8F5tadHukuibwoUitj5ctQLVX2DXk94vkK/:1003:1003:,,,:/home/cozybear:/bin/bash
yetibear:$6$.u.lAiwI$ZQ1gWfUkquUoSjgjHQsyty.bRvXUYtuSLjLgZYvlQ.fZz6R.4zHPFqcfeqsaCUBH.P9IbZn4wHGyOADfrbiS1/:1004:1004:,,,:/home/yetibear:/bin/bash
grizzlybear:$6$dslx5A3f$g3OVHjyw.2X1gp/C55bHu.s6WRzZD5Iu5j0/3lCMRfnh.fNzyMArQZn56J2J/tB2EG0iKHQnz62pNAtHBt0yk.:1005:1005:,,,:/home/grizzlybear:/bin/bash
smokeybear:$6$yY5UKBjz$wINjW.wdjzaFHD6ytdOGFPjzUoUrRN1dGtr4iNU93/hTVVXO/pqG18nhopZX/7Koc.A3l2kLSxWhykQUFUGF0/:1006:1006:,,,:/home/smokeybear:/bin/bash
fozziebear:$6$K.BwBqhO$NVW0itQwjECKIbPjHy9b6qys2lv92r6ExvIzSA9dhIUKdvHO223ud7fr7JYLHQ1R9dW.ziMNWX4vd.QfsY3vk1:1007:1007:,,,:/home/fozziebear:/bin/bash
Administrator:500:aad3b435b51404eeaad3b435b51404ee:e19ccf75ee54e06b06a5907af13cef42:::
fancybear:1009:aad3b435b51404eeaad3b435b51404ee:be1773ca5eccc0102006d0f12ee9aeba:::
pedrobear:1000:aad3b435b51404eeaad3b435b51404ee:572954208e36c94da325117731186344:::
polarbear:1003:aad3b435b51404eeaad3b435b51404ee:8c1653757cb5205609a524b1b3e1c5f7:::
teddybear:1004:aad3b435b51404eeaad3b435b51404ee:ebb2b64f58ade30183b2155a567b1c7a:::
</pre>

I combed through the submissions today: 23 total submissions (students can submit multiple times but only the last submission will count).  The answers:

<pre>
(MD5) chicagobear:P1rate$ => 5 students cracked this
(MD5) bigbear:Va-[B~ => 0 student cracked this
(MD5) jojobear:SRYSQF => 1 student cracked this
(MD5) crazybear:mrfVlkECv => 0 student cracked this
(MD5) slothbear:L!verpool => 4 students cracked this
(MD5) cocobear:CCc3 => 4 students cracked this
(MD5) willybear:wGPLek => 1 student cracked this
(MD5) yogibear:rqb3Hc => 1 student cracked this
(SHA512) blackbear:dave => 22 students cracked this
(SHA512) blinkybear:zUnR => 1 student cracked this
(SHA512) cacabear:/|rv]y => 0 student cracked this
(SHA512) cozybear:is0g0TriE => 0 student cracked this
(SHA512) yetibear:thx1138 => 22 students cracked this
(SHA512) grizzlybear:extreme => 20 students cracked this
(SHA512) smokeybear:B00ty => 2 students cracked this
(SHA512) fozziebear:PCMASTERRACE => 0 student cracked this
(NTLM) Administrator: P@ssw0rd => 9 students cracked this
(NTLM) pedrobear:JJyI8f3MG => 0 student cracked this
(NTLM) polarbear:HomerSimpson1 => 4 students cracked this
(NTLM) teddybear:K-(*4@ => 3 students cracked this
(NTLM) fancybear:6F2Xx2f6 => 0 student cracked this
</pre>

The winner cracked 11 of the passwords.  The student's haul:

<pre>
jojobear:SRYSQF
cocobear:CCc3
willybear:wGPLek
yogibear:rqb3Hc
blackbear:dave
blinkybear:zUnR
grizzlybear:extreme
smokeybear:B00ty
yetibear:thx1138
Administrator:P@ssw0rd
teddybear:K-(*4@
</pre>
---
layout: post
title:  "Results of a Password Cracking Content for My Security Class (Fall 2016)"
date:   2016-11-6 17:00:00
categories: education security
---

For my [Introduction to Computer Security](https://tuftsdev.github.io/DefenseAgainstTheDarkArts) class that I teach once an academic year since 2012, I give a month-long lab in October to crack as many passwords as possible.  For this year's contest (opened on October 3, 2016), I used three different hash types: NTLM, MD5, and SHA-512.  The password hashes:

<pre>
bigbear:$1$xJJUvMhn$PnAhcJUFtPrqcgPLTfkH6/:1012:1012:,,,:/home/bigbear:/bin/bash
blackbear:$6$LbFQXixl$Ozskf08sMdjuk2IDgpwwqwTtVPJEid3euQBrxtzsNqiif4wuP7s/CLe7PHeuVmDJLVan8lMXhmqPMvR7Zztll.:1003:1003:,,,:/home/blackbear:/bin/bash
blinkybear:"":"":AAD3B435B51404EEAAD3B435B51404EE:E5E47C3D94AF02C2798FBE510DF7F01B
cacabear:$6$D8RyIoSq$T6/L8Nt56.AEf5YZ8oc99sX5WvLf6V5guBWQGr173oDPFSJdxCvCy7qocmLjr9KA7/tyxkQG5pMXtpymOfVRT1:1001:1001:,,,:/home/cacabear:/bin/bash
chicagobear:$6$ZiRsvy9t$tSJPZWkuN/osPl3Ai21t13E/5JLpPote/LPFCU/EUggZB4IiLHHjT.b.zC2Sy8z.Ufh9s7CKbyL3CH4zct1KM/:1008:1008:,,,:/home/chicagobear:/bin/bash
cocobear:"":"":AAD3B435B51404EEAAD3B435B51404EE:3C7E2D527B77687A4681B0400F9D9F25
cozybear:$1$8RT.TaL6$gNsnjq9LF2yjgsuBC/QZ0/:1003:1003:,,,:/home/cozybear:/bin/bash
crazybear:$1$8yZuL1Bo$CFgDFz92z3la0nXa2u/Dp/:1004:1004:,,,:/home/crazybear:/bin/bash
daisybear:$1$YGX1Xwac$gmreBVss7axOOcd0uTOc.0:1008:1008:,,,:/home/daisybear:/bin/bash
fancybear:"":"":AAD3B435B51404EEAAD3B435B51404EE:C0112B9DB3187CD752A54AAA23F5221C
foofoobear:$1$XCzh81qm$yhPc5ZUrD/Hisol1pmW061:1007:1007:,,,:/home/foofoobear:/bin/bash
fozziebear:$1$syLzkzPE$AC2byibcPyEYOQHOTOAIB0:1006:1006:,,,:/home/fozziebear:/bin/bash
grizzlybear:$6$dOczf73V$QeJe7NqQwY01dfFHVBimqFuQONSswXsQjN7X9cdADLgBQIl5OHiC58sEH6gSSMU8jMOBrOXCyI8B.VCQD3Bs00:1004:1004:,,,:/home/grizzlybear:/bin/bash
jojobear:"":"":AAD3B435B51404EEAAD3B435B51404EE:6BE5E7CBB322E62348285DD15F61C674
pandabear:$6$/PgVCL9l$A35Mq3OUtCAH6.itt939KnAfedwLnixmIs7Culx9OjolS0WPIf2eO/a4w0GwCn1ytjaH5WgEz4LPRphmhtz6Q.:1005:1005:,,,:/home/pandabear:/bin/bash
peachbear:$1$hKbWRBKb$Z6u6bSrI/jjs21kCGUeYW1:1009:1009:,,,:/home/peachbear:/bin/bash
pedrobear:$1$Mc99h/YO$wyXQUl4PcL3445YIorKPB0:1005:1005:,,,:/home/pedrobear:/bin/bash
slothbear:$6$7HPLjgWS$7PKyhvnoEXK6aIFmMRlBJ/hnh26EoH/BWe7mF1nuOc7aEW/05gcrzadYsxMpIr9Q2aMRWAK5V4jidEGOpFnDN.:1006:1006:,,,:/home/slothbear:/bin/bash
smokeybear:$6$nZvgK5hA$IIzI1X3pQyqw6HHifJvzmFbqy4YsvfWEUr7ziDxTFAskM0MgWcLnNe2GytOg9fuH2Q8Fj6NqvATynl4OTOln3.:1007:1007:,,,:/home/smokeybear:/bin/bash
teddybear:$1$Lz.US6gS$uzZW7jqRMJyNSImlMSmxs/:1011:1011:,,,:/home/teddybear:/bin/bash
willybear:"":"":AAD3B435B51404EEAAD3B435B51404EE:D0B9293D8D9B19C2521035CAD9EEA62F
yetibear:$6$ymHxOcle$Fld.1NstIFNUj0isoNreqAiFDz9lKmsCW4ZHE8MLljOLh7CCwTLsj8AH/qu3bK9pMeMWyIOfvZZyzqVsVxAZ.0:1002:1002:,,,:/home/yetibear:/bin/bash
yogibear:"":"":AAD3B435B51404EEAAD3B435B51404EE:A742EEEDC81F844277927E3CE83817D7
yolandabear:$1$B90md6v6$L78BfqeVKpj2scI18FT1y1:1010:1010:,,,:/home/yolandabear:/bin/bash
</pre>

I combed through the submissions today: 64 total submissions (students can submit multiple times but only the last submission will count).  The answers:

<pre>
bigbear:!Liverpool (MD5) => 11 students cracked this
blackbear:KDI9quo8 (sha512) => 0 students cracked this
blinkybear:EdRojas (NTLM) => 54 students cracked this
cacabear:uc12SL (sha512) => 0 students cracked this
chicagobear:ch!pmunks (sha512) => 2 students cracked this
cocobear:XQ\Y0VJsk (NTLM) => 0 students cracked this
cozybear:gpxkr4 (MD5) => 3 students cracked this
crazybear:c1jkfp5 (MD5) => 0 students cracked this
daisybear:Booger  (MD5) => 62 students cracked this
fancybear:ECX[0Wr (NTLM) => 3 students cracked this
foofoobear:k/&lt;vQC (MD5) => 0 students cracked this
fozziebear:w7b1vcz1a (MD5) => 0 students cracked this
grizzlybear:@Pp|3 (sha512) => 19 students cracked this
jojobear:3scrow (NTLM) => 57 students cracked this
pandabear:AshleyMadison (sha512) => 15 students cracked this
peachbear:ncc1701a (MD5) => 58 students cracked this
pedrobear:kghu2d0m (MD5) => 0 students cracked this
slothbear:OHMYGODTHEYKILLEDKENNY (sha512) => 5 students cracked this
smokeybear:allyourbasesarebelongtous (sha512) => 0 students cracked this
teddybear:kafka21 (MD5) => 32 cracked this
willybear:M@rc0P0l0 (NTLM) => 35 students cracked this
yetibear:7QunlW8 (sha512) => 0 students cracked this
yogibear:u1-1$A#Q (NTLM) => 0 students cracked this
yolandabear:jabron1 (MD5) => 52 students cracked this
</pre>

The winner cracked 13 of the passwords.  The student's haul:

<pre>
bigbear:!Liverpool
blinkybear:EdRojas
chicagobear:ch!pmunks
cozybear:gpxkr4
daisybear:Booger
fancybear:ECX[0Wr
grizzlybear:@Pp|3
jojobear:3scrow
pandabear:AshleyMadison
peachbear:ncc1701a
teddybear:kafka21
willybear:M@rc0P010
yolandabear:jabroni1
</pre>
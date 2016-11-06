---
layout: post
title:  "How often does a *Google* Android device phones home?"
date:   2015-06-12 23:19:00
categories: mobile, security
---

[_"We don't love Google so much any more, mainly because we trust it less and less. More and more people have realized that the Google search engine is hugely biased in favor of advertisers, and the results are increasingly manipulated by Google for inscrutable purposes. Google seems to track anything and everything we do -- it peruses our emails, our files stored on its servers, our locations, and our chats."_](http://www.infoworld.com/article/2610866/techology-business/too-big-to-trust--google-s-growing-credibility-gap.html){:target="_blank"}

So what about a Google Android device?  Notice that I specifically added the word "Google" preceding Android as there are non-Google versions Android available (e.g., Cyanogenmod).  I took a Nexus 5 and flashed it with [Google's factory Android image, version 5.1.1 (a.k.a., "stock" Android)](https://developers.google.com/android/nexus/images){:target="_blank"}. Next I [installed a mitmproxy certificate onto the phone](https://mitmproxy.org/doc/certinstall/android.html){:target="_blank"}, and captured all the HTTP and HTTPS traffic on the phone to `mitmproxy` running on my laptop.  I left the phone stationery for one hour in another room.  The result: 10 requests, 9 HTTP post requests.

![Android phones home](/images/mitmproxy-android.png)

Hmmm, seems like two of the requests were ad-related and two related to voice search?

The data sent back to Google is interesting.  I posted the flow of all HTTP and HTTPS traffic from the Nexus running Android 5.1.1 for your analysis and interest: [`android.flow`](/docs/android.flow).  You can open the file from `mitmproxy`.

People are getting worried about all of this creepiness, nonsense.  So what can you do?  The extreme option: don't use a cell phone.  Dan Geer doesn't use one:

[_"I am, as a rule, skeptical of coming to rely upon things that I don’t know how they work. If there’s anything that I’ve come to be relatively adamant about is that, as humans, we have repeatedly demonstrated that we can quite clearly build things more complex than we can then manage, our friends in finance and flash crashes being a fine example of that.  Given what I know in the cyber security arena, the number of things that, in effect, nobody understands how they work causes me to say, well, then why do I want to depend on it?"_](http://www.wired.com/2015/06/cia-cybersecurity-guru-dan-geer-doesnt-use-cell-phone/){:target="_blank"}

Another option: go back to a "flip phone."

If you have an Android device, you can change the operating system to a non-Google Android such as [Cyanogenmod](http://www.cyanogenmod.org/){:target="_blank"}.  It is still Android, but without the bloat (hardly anything Google), and even features such as built-in root support.
---
layout: post
title:  "Technical Project Ideas Towards Learning Cyber Security"
date:   2020-06-19 00:00:00
categories: education security projects
---

Quite often, I am asked about _technical_ Cyber Security project ideas to do from people who want to get into the field.  I have never been able to produce a concrete list of technical project ideas --until now.  Looking back at my career, the knowledge gained from doing these projects helped me immensely.  Each of these projects has an underlying big idea that will prove to be very valuable for the long term in the Security field.  Each of these projects can start out very small and can morph into something big.  These projects do not have a significant financial cost, all under $75.00.  I am mindful of the issue of financial cost, so I did not include project ideas such as building a home lab.  The only requirement is to have access to a computer of some sort.

### Create a Virtual Machine in VirtualBox
Download ISO of either a Linux distribution or a version of Windows.  Using VirtualBox, create a virtual machine (VM) using the ISO.  Upon successfully creating the virtual machine, run it, and play around inside the VM.

Get comfortable with creating and running virtual machines.  This skill is necessary for various activities including creating a lab environment for malware analysis.  Virtualization is also what makes cloud computing works.

### Create a Virtual Machine in VirtualBox --Linux Server Only, No Desktop

Download ISO of a Linux server that has no desktop or graphical interface. [Ubuntu Server](https://ubuntu.com/download/server) is recommended because of its popularity --which matters because of the amount of support available.  Using VirtualBox, create a server VM.  Upon successfully creating the server VM, run it, update all software via Advanced Package Tool (`apt`).  Use `apt` to also install software such as `emacs`, `vim`, `wget`, `curl`.  You can also turn the server into a web server by installing either `nginx` or `apache`.

This project will help you get comfortable using the command line, and to install software.  Not everything can be accomplished by fancy graphics and graphical interfaces (sometimes constraining to).  Graphical interfaces also mean more software requirements, more overhead, more bloat, and more vulnerabilities.  Many security tools are command line-based.

### Build a Web Server in the Cloud

Very similar to creating a Linux server virtual machine using VirtualBox, but instead, use a cloud environment such as Amazon Web Services (AWS) EC2 or Google Cloud's Compute Engine to build a web server.  If you are a new user to a cloud environment, you will be given free credits.  If you are a student, get the [GitHub Student Developer Pack](https://education.github.com/pack) which comes with credits to AWS, Microsoft Azure, and Digital Ocean.  Spinning up a virtual machine in the cloud will also give a public IP address to that machine.  SSH into the virtual machine in the cloud to install a web server software (e.g., `nginx` or `apache`).  After installing web server, open a web browser on your computer, type in IP address (of the cloud VM you created) in the address bar to see if web server software was successfully installed.  Monitor the access and error logs of your web server (can be found usually in `/var/log/`).

This project provides skills of installing software and using a cloud environment.  While using a cloud environment can be overwhelming as it provides lots of services, it is becoming a necessary skill for many opportunities in tech.

### Build a Static Website Using HTML, CSS, JavaScript, and Amazon S3

Without using a front-end framework such as Bootstrap, write a simple static website using HTML, CSS, JavaScript, and Amazon S3.  One idea for a website is a personal website.  I do not recommended using a front-end framework for this project because it provides so much for you where you don't need to understand how things really work.  Build the website using a good code editor (e.g., Atom, Sublime, Visual Studio Code).

If your goal is to do web application security, it is necessary to know how the web works.  This includes the syntax and structure of HTML, CSS, and JavaScript files.  I also included Amazon S3 in this project, not because it is part of AWS, but because of the rash of security incidents involving open S3 buckets exposing troves of secrets.  Hence, this is a system that security practitioners should know about.

### Create a Blog Using WordPress

Create a blog using either WordPress Cloud Hosting service or installed on your web server using the [source code](https://github.com/wordpress/wordpress).  Customize your blog using a theme and install plug-ins.

WordPress powers over [20%](https://w3techs.com/blog/entry/wordpress-powers-25-percent-of-all-websites) of the world's websites.  However, WordPress and plugins are riddled with vulnerabilities.  A serious vulnerability in WordPress or in a popular WordPress plugin [can affect 100000+ websites](https://www.zdnet.com/article/wordpress-plugin-vulnerability-can-be-exploited-for-full-website-hijacking/).  Generally speaking, all WordPress websites follow the same structure.  It is beneficial to know the structure of a WordPress website including where plugins, themes, and uploads are stored (in `wp-content`), and how to administer a WordPress blog (via `wp-admin`).

### Build a Honeypot in the Cloud

A honeypot is a trap.  You can even turn your web server in the cloud into a honeypot by installing some software.  There are many [honeypot software available on GitHub](https://github.com/paralax/awesome-honeypots).  I use [cowrie](https://github.com/cowrie/cowrie), an SSH honeypot.

The value of a honeypot is the data.  Honeypots are commonly used to lure attackers to get an understanding of how they are gaining access into a system, what malware or malicious scripts they are using, where geographically they are from, what commands are they using, etc.  Configuring a honeypot will also be necessary, including setting up firewall rules.

### Build a Pi-hole Using a Raspberry Pi

A [Pi-hole](https://pi-hole.net/) is a network-wide blocker of Internet ads and trackers.  I've been running one for [years](https://twitter.com/0xmchow/status/864308067659370496).  Install Pi-hole on a Raspberry Pi, [a $35 computer](https://www.raspberrypi.org/), and then connect it to your router.  Even the $5 Raspberry Pi Zero works great.  You will also need a micro SD card, an Ethernet cable, and a power supply for the Pi.

The Pi-hole ["is a DNS sinkhole that protects your devices from unwanted content, without installing any client-side software."](https://docs.pi-hole.net/)  You can also use Pi-hole as a DHCP server.  You can learn a lot about networking, including how DNS works, with a Raspberry Pi running a Pi-hole.

### Build Native Mobile App Using Geolocation

Using either Xcode (for iOS) or Android Studio (for Android), build a native mobile app with a single view: a map.  Loading the app shall determine your geolocation.  Upon determining your location, mark your location on the map.

Building a mobile app is very different than building a web site or an app for desktop/laptop.  The app lifecycle, the distribution model (via app store), and security and privacy model are different for mobile.  Building such an app will help you understand the constraints, the opportunities, and also the nuances working in a mobile duopoly world.  Let's also not forget many mobile apps are riddled with vulnerabilities or [laced with malware](https://gitlab.com/mchow01/DancingPig).

### Write a Program That Uses a Third-Party API

Pick a programming language of your choice (e.g., Python).  Write a program to get data from a third-party API of your choice (e.g., [Twitter](https://developer.twitter.com/en/docs)).  For example, a write Python program that get tweets about COVID-19 or #covid19.

Most modern applications now use multiple third-party APIs to integrate with what people already use and know.  Doing this project will help you learn the fundamentals including basic programming, parsing data in JSON (JavaScript Object Notation) which most third-party APIs use, and how to use and store API keys --correctly or [incorrectly](https://www.zdnet.com/article/over-100000-github-repos-have-leaked-api-or-cryptographic-keys/).

### Build a Blog App Using a Web Application Framework

Using a web application framework like Django (Python), Ruby on Rails (Ruby), Flask (Python), Express (Node.js), build a blog app.  The official [Ruby on Rails tutorial](https://guides.rubyonrails.org/getting_started.html) is building a blog app.

A web application framework allows developers to write software with less code.  That is, some common tasks can be done with as little as one line --which is both a good and a bad thing.  Less code means faster development at the cost of abstracting away how things work.  Building a web application will also help you see the many different components (i.e., distributed system) required including database and middleware.  Using a web application framework also makes it easy for developers to include third-party libraries via programming language's package manager (e.g., `gem` for Ruby, `pip` for Python, `npm` for Node).  The latest OWASP Top 10 now lists ["Using Components with Known Vulnerabilities" as A9](https://owasp.org/www-project-top-ten/OWASP_Top_Ten_2017/Top_10-2017_A9-Using_Components_with_Known_Vulnerabilities.html).

### Build a Temperature Sensor Using Arduino and Send Data to Server Somewhere

I had to throw in an Internet of Things / embedded systems project of some sort.

### The Point of These Projects

Each of the project ideas started with the word "build", "create", or "write".  Not a single project mentioned penetration testing, using a security tool, ethical hacking, OSINT, or social engineering.

What really prompted me to write this blog was this tweet by friend Marcus Carey:

> More often than not if all you know if ethical hacking, OSINT, and social engineering it's going to be hard to get your first job in cybersecurity.

[https://twitter.com/marcusjcarey/status/1270876203306627072?s=21](https://twitter.com/marcusjcarey/status/1270876203306627072?s=21)

If all you know is how to fire up and run Metasploit and other security tools on Kali Linux, then you're just a script kiddie.

If you have an interest in understanding how things work underneath the hood, that goes a very long way.  *The point of these projects is to understand how systems work and fail --which is the core of Security.*

Once you know the fundamentals and how systems work, you will have a much better sense of what's going on when you use security tools like Metasploit, wpscan, Burp Suite, THC Hydra, Nmap, and countless security tools.
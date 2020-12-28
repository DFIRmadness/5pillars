# Hey There!

**This document spawned an entire website. Check it out at: [DFIRmadness.com](https://dfirmadness.com). We have labs, articles and resources like this! See you over there.**

# The Five Pillars of an Information/Cyber Security Professional

## TLD;DR:

"Mastering the basics will make you exceptional."

Master the basics and then specialize to be an invaluable asset to your team.

To start, or level up, a career in Information Security (aka Cyber) Security you need to be proficient in five key areas of technical skills.  You don't have to *master* each one of them, but you need to have a good understanding of them.  Whether you want to go offense or defense you will need to be functional in these five areas:

1. General Computing
2. Computer Networking
3. Scripting and Programming
4. Linux / MacOS
5. Windows

**Note**: I did not come up with the 5 pillars idea on my own.  I *believe* I heard this originally during a conference call with someone from SANS the CyberStart program.  I am not entirely sure of that or if the 5 above are the original 5 laid out.  I *do* remember hearing the 5 areas (or close to these) laid out and it immediately fit into my believe system of mastering the basics to become exceptional.  That idea was hammered home during a good butt chewing delivered during Special Forces training where the instructor told us between flutter kicks and sprints, "We look special because we master the basics".  I have applied to this every complex task I have learned from flying helicopters to hacking and it has served me well.

Don't be scared! While you won't learn it all over night you only need the fundamentals.

If you want to accel in this industry you must also **love** learning.  While it takes a lot of dedication a healthy balance is key.  Make sure your family and friends get time with you, or that you make time to do hobbies you love.

***
## Quick FAQ(ish)

### Wait! Wait! Wait! Where is the hacking!? No where in the list is there hacking or security

Correct.  These are the fundamentals that both defense and offense require!  More focused security paths are added to the second section of this document. Build the foundation and then the house. 

### A Note about Certifaction Pipelines / Schools

The cert farms that tell you A+, Net+, Sec+ and CEH in 6 weeks will get you a career are stealing your money. Certs are important and you will need some most likely, but you DO NOT need 5 in 5 weeks or 5 in 5 months.

### A Note about College Degrees

You do not need a degree in cyber security. You do not need a degree in cyber security.  If you just have to get a degree- get it in Computer Science.  There are sadly an over whelming amount of people with Cyber Security degrees who do not know their way around a keyboard and only know academic theory... they can only talk the talk without being able to walk the walk. Most degree programs do not provide nearly enough hands on fundamentals to set someone up for sucess.

### Typical Career Path

There is no typical career path currently.  Some of the best Cyber Security Pro's were musicians prior! If you have the talent and drive you can work your way in.  That said, a good path would be something like this:

IT Help Desk -> Systems Administrator -> Security Admin -> Specialized Security Role

You can absolutely skip right into security but you will have to study hard and practice a lot of labs that ensure you really have the 5 Pillars well cemented.

### A Note About the Image and Attraction of PenTesting

Before you start:  Perhaps Penetration Testing is all that interests you - or "catching bad guys" is the only thing you want in life.  Remember that learning both sides of the force will benefit you.  The better your understanding of defense the more lethal you can be on offense. **There are probably 10 Blue (defense) jobs to Red (offense).  There are a lot of fun jobs outside of Penetration Testing.**  That said, Penetration testing is a blast and is addicting.  It is also a lot of work and not simply pwning networks and dropping mic's.

Now on to the document...

********

## readme.txt

This document is a path forward for new, and experienced, cyber professionals to obtaining a concrete foundation of knowledge to enable them for success in the industry.  Mastering the basics of each functional area is required to operate on a cyber team (or alone) in a meaningful and effective way.  A lack of fundamentals in any one pillar can quickly render a team member ineffective during dynamic and rapidly evolving situations.  Conversely, no one person on the team should be, or can be, a cyber unicorn.

Ideally, everyone will have a specialty they excel at in addition to a solid baseline in the fundamentals.  It should not be expected that every one completely master each pillar.  The intent is to master the fundamentals.  The fundamentals are simply primal blocks of knowledge of each topic; somewhere between the absolute basics and intermediate.  As an example, a team member should understand: sub-netting, routing, internetworking, OSI model, packet capture, DNS and analysis basics.  This does not mean they need to be Cisco network engineer with a CCNA.

Layout of the document (roughly):

1. Fundamentals and getting started
2. Lab Set Up Advice
3. Security Focused Training and Immersion
4. Security Career Pathways

***
whoami

Twitter: @DFIRmadness

- Veteran
- Former pilot
- Senior Information Security Professional
- Perpetual n00b (always learning)
- Adjunct Professor
- Aspiring SANS Instructor

I have seen folks in multiple industries who would be rockstars if they had a solid mastery of all the basics and not simply pigeon holed into one niche of the field.

***

## Security Tips to Get Started

As you dive into security you should start with good security practices.

1. Don't pirate software.
2. Always have your Admin Account seperate from your daily driver account.
3. Never click a link you didn't ask for.
4. Never use a free VPN (OK - except maybe Proton's).
5. Always check executables and files from others at virustotal.com.
6. Use time based multi-factor on critical accounts like e-mail.
7. Use a password manager and have unique passwords for everything.
8. Use passphrases when able.  Example: 1DeerCloudSubmarine91* [XKCD Password Generator](https://xkpasswd.net/s/).

***

## What You Need (Equipment)

You do not need a $3000 Gaming Laptop or a Desktop with 2 GPU's and 10 TB SSD.  This is completely based on your budget.  You can get away with a $500 laptop if needed. I will explain.

|Level|Explaination|
|---|---|
|Good ($500)|A computer capable of web browsing and reading books. Seriously. The trade off is you will need to pay for web accessible labs versus building a small virtualized environment.|
|Better ($1100ish)|A laptop capable of building a small lab of 2-3 Virtual Machines. Something like an i7, 16 Gigs or RAM and 500 Gigs storage.|
|Best|The sky is the limit.  Something capable of cracking passwords decently (read a mid tier GPU), i9, 32 Gigs, and 1 TB storage.|

**Note**: A GPU is mentioned for password cracking.  You absolutely DO NOT NEED ONE to learn or level up cyber security.  Keep in mind this document is about learning and labs you encounter will be geared towards this anyhow.  You get the same training value in cracking a simple password with your CPU as you do with letting a GPU pound on a hash for 2 weeks.

***

## The Five Pillars (Functional Areas) of Cyber Security

1. General Computing
2. Computer Networking
3. Programming and Scripting
4. Windows
5. Linux

### Fundamentals Breakdown

The following are key skill sets within each pillar.  It is not an exhaustive list.

|Pillar aka Functional Area|Skills|
|---|---|
|**General Computing (Basic Computer Science)**|Hardware Components: <li>CPU<li>RAM<li>SSD/HDD<br>Science:<br><li>Threads<li>Processes<li>Process Trees<li>Memory (RAM)<li>Caching<li>Buffers|
|**Networking**|<li>OSI Model<li>TCP/IP Model<li>TCP vs UDP<li>Packet Analysis<li>Packet Capture<li>Routing<li>DNS<li>ARP<li>Subnets<li>VLANS|
|**Programming and Scripting**|<li>Python<li>Powershell<li>BASH<li>Bonus: C++ or C#|
|**Windows**|<li>Registry (5 Hives)<li>Volume Shadow Copies<li>UAC<li>Memory Paging<li>.msi vs .exe<li>DLLs<li>RIDs<li>SIDs<li>Tokens<li>Network Profiles<li>Server vs. Workstation<li>Commands: <li>Netstat<li>whoami<li>ping<li>ipconfig<li>Powershell Remoting<li>Tools: Sysinternals<li>Process Hacker.|
|**Linux**|<li>Directory Hierarchy<li>sudo accounts<li>/etc/shadow and /etc/passwd<li>ssh<li>telnet<li>ftp<li>Software Repositories<li>Be Familiar with Distributions: Kali, Debian, Ubuntu, CentOS, RedHat<li>Commands: w, find, whoami, which, who, ss, watch, ssh, lsof, ssh-add, top, htop, sudo, nano and vim.|

Yes.  That is a lot.  First, to be good in this industry you will want to be *familiar* with each of these things and beyond.  You will not learn it all over night nor should you try.  Just refer back to this often as a guide.  Be patient. Enjoy the journey.

### Desired Endstate of Each Pillar

The following are goals to shoot for in each area.  If you can meet each of these you will be a competent professional ready to shine at interviews and be an asset to any team you join.

|Pillar aka Functional Area|Skills|
|---|---|
|**General Computing (Basic Computer Science)**|Explain the difference between something being stored in memory vs. something stored on disk. Explain the basics of process injection. Explain the difference between killing a thread and killing a process.|
|**Networking**|Using all 7 layers of the OSI model explain how a piece of information flows from your computer to google.com and back when you type `ping google.com`.<li> Explain what a VLAN is and why they are used.<li>Explain what a subnet is and why they are used.<li>Explain the security protections offered by subnets and VLANs|
|**Programming and Scripting**|Be able to write a basic script to automate a simple task; and be able to read and understand the overall idea of what someone else’s script is attempting to do.|
|**Windows**|Be able to explain the function of the registry, the UAC, and tokens. Be able to maneuver the OS with command line only and look for network connections and their related processes. Possess basic PowerShell (a.k.a PoSh) abilities|
|**Linux**|Be able to explain sudo, shadow and passwd files, user groups and proper installation and maintenance of software (repos).Be able to maneuver the OS with command line only and look for network connections and their related processes.|

*Remember you have to know how things work to exploit them.  You have to know what right looks like to find the gaps in security.*

These goals above are a good measure of when you are ready to deep dive into a specific security path of learning (and of course have fun and sprinkle in security lessons along the way).

### A Note About Certifications

Certifications are a necessity in this industry.  They are far more valuable than a college degree.  That said, don't be a paper tiger where you have a list of certifications and no idea what you are actually doing.  Also- do not fall for the cert farm trap.  These companies that promise you a career is only 5 weeks (or even a few months) away, and that for $20K they will get you there by ram rodding you through A+, Net+, Sec+, and CEH.  They are practically stealing your money.  If you find a place that will teach you essentially the fundamentals laid out here ask to talk to alumni and ensure the instructors are actual industry professionals.

There will be certs listed in this document at times.  For general studies understand that most of the certs mentioned are just great bodies of knowledge to get materials from but the cert itself is not necessary.

#### Certs to Shoot for Early On

GSEC or Sec+.

**NOT A+**.  Friends don't let friends actually get the A+ cert.

**GSEC or Sec+**:  If you live around a lot of Department of Defense facilities that are hiring there is a set of requirements known as [8570](https://www.giac.org/certifications/dodd-8570).  You will basically need GSEC  or Security + for anyone to touch you during the hiring process.  SANS GSEC is the recommended cert here.  It is much more expensive to go through the course but well worth it.

**CEH**:  Certified Ethical Hacker does not make you a penetration tester and doesn't go very far outside of DoD circles.  For the same price you can get the course material for [Penetration Testing with Kali Linux from Offensive Security](https://www.offensive-security.com/pwk-oscp/).  Even if you can't pass the OSCP challenge the material and labs are well worth the $800 or so - certainly *more* so than CEH.

The trick when you are first starting out is to find an employer willing to pay for the certs you need or want.  Get it in writing.  If you can't then understand than the investment of paying for an initial cert or two to get a job will be an investment that will almost certainly have great returns.

***

## Resources:  How Do We Get 'There'?

Now may be a good time to think on *how* you approach learning this mountain of information. [How to learn anything...fast by Josh Kaufman](https://www.youtube.com/watch?v=EtJy69cEOtQ).

### General Approach

- Start free and cheap to see if you like it.  You may find it isn't for you.
- While studying the five functional areas ensure you are getting hands on keyboard and not just your nose in a book.  Do both!  Also - sprinkle in security lessons along with your general studies.  Also, try and rotate through the five continuously so you are leveling up in them all somewhat evenly.  Of course, you can do it in a serial fashion (in order one through five) if you want.  However, these skills are perishable. This means if you go through in order and haven't touched networking in 5 months (or 2 books ago) it is going to be rusty and you will have to relearn it!!!
- Try and have fun!
- Keep an eye out for things you think you may be passionate about!  You will want to specialize later on.

### Recommended Security Focused Resources to go with General Studies

### Hack and Detect: Leveraging the Cyber Kill Chain for Practical Hacking and its Detection via Network Forensics

![Hack and Detect](https://images-na.ssl-images-amazon.com/images/I/51CyN7q7LaL._SX403_BO1,204,203,200_.jpg)

The book to start with: [Hack and Detect](https://www.amazon.com/Learning-Practicing-Leveraging-Practical-Detection/dp/1731254458) ! by Nik Alleyne.  This book can be purchased or viewed free with a Kindle Unlimited account.  This book can't be recommended enough for beginners and experienced folks alike.  It is amazing in its presentation of both offense and defense methodologies with break downs and explanations of each and every command. **This is a great book to sprinkle in along with the 5 pillars studies. Consider it the quick start guide into security.**

### The Cyber Mentor

![The Cyber Mentor](https://yt3.ggpht.com/a/AGF-l7_-iGuCNgJT5TzZNBVoO4V6tCmHv6KOrRMNIA=s288-c-k-c0xffffffff-no-rj-mo)

[The Cyber Mentor](https://www.thecybermentor.com/beginner-linux-for-ethical-hackers): hands down is one of the first people you should start watching as you build your skill sets.  He focuses on Penetration Testing.  He, along with the community he has created in discord etc., will be a great place to find motivation, knowledge and support. Even if you want to go blue side / foreniscs etc. you will need an understanding of how people pentrating networks etc. move through the network and he does a superb job of teaching and explaining.

### General Studies Resources

These resources will have materials for all or multiple pillars.

- [Safari Books Online](https://www.safaribooksonline.com/topics) Free for military members and families
- [Humble Bundle Books](https://www.humblebundle.com/books) They often (every few weeks) have cheap (12 dollars) bundles of books
- [packtpub daily free book give away](https://www.packtpub.com/free-learning) Free IT and Security books given away daily! Some really good ones on occassion.
- <img src = "https://yt3.ggpht.com/a/AGF-l79FABgGifk6OVOrWGLKwdMiysqksJ57Mtp4tg=s288-c-k-c0xffffffff-no-rj-mo" width="50"> [ITPro.tv](https://www.itpro.tv/) is one of **the best** resources out there if you can afford it.  They have tiered pricing models that start as **low as $30 bucks a month!** That is a crazy cheap investment to get into a career with a potential to get you to between 65K and 100K+ annually. This is the first item on the list that you are required to pay for if you choose to use them. They have current, and constantly updated, video series on everything in the five pillars and beyond.  Additionally, they offer virtual labs you can remote into with step by step guides, test question banks and more.  Its an amazing resource.
- [CBT Nuggets](https://www.cbtnuggets.com/) - A direct competitor with ITPro.TV.  They have comparable pricing, virtual labs and *really* good instructional videos.  Their video library does not seem as extensive as that of ITPro.tv.
- [Professor Messer](https://www.professormesser.com/) Another solid instructor that gives A LOT for free.  The community there is also a great resource to connected to.  He sells "notes" for 10 bucks a piece for each cert that are great overviews and resources to keep in your kit bag.
- [Computerphile](https://www.youtube.com/user/Computerphile) an epic youtube channel of PhDs explaining computer science and security concepts.
- [Twitter](https://www.twitter.com) Later there will be a list of people to follow but essentially you can get started with #infosec and #dfir and start a daily ingest of what is going on in the community.  Immerse yourself!

There are so many more amazing people and channels that I will list later in the *Security Specific* Section later.

### Pillar Specific Resources

A Quick Table.  Certs listed here are only pointers to good sources of learning material. In most cases the first few chapters are probably what you need and then specific topic lookups.

|Pillar|Resources|
|---|---|
|General Computing (Basic Computer Science)|<li> A+ Cert videos from [Professor Messer](https://www.professormesser.com/) and [ITPro.tv](https://www.itpro.tv/).  Remember the objectives from above.  You aren't actually getting the cert.<li>[Threads v Processes](https://www.youtube.com/watch?v=O3EyzlZxx3g) video from udacity/Georgia Tech<li>[Professor Messer A+](https://www.professormesser.com/free-a-plus-training/220-901/comptia-220-900-course/)<li>Assosciated Certifications (Good references): A+|
|Networking|<li>[Professor Messer Network+](https://www.professormesser.com/network-plus/n10-007/n10-007-training-course/)<li>[malware-traffic-analysis.net](https://www.malware-traffic-analysis.net/) - Collection of PCAPs filled with evil along free tutorials on how to find it with WireShark<li>Any CCENT (Cisco Certified Entry Networking Technician) Materials in ITPro.TV, Safari Books etc. Typically the first few chapters.  Once it gets deep into iOS (Cisco Op System) specific material you’ve hit the limit of the fundamentals<li>[Todd Lammle Internetworking on ITPro](https://app.itpro.tv/course-library/ccent-updated-2016/internetworking/?tagcategory=course-library&tag=legacy) - Todd Lammle gives an amazing internetworking fundamentals course in 15 minutes.  Watch this often.<li>[ITPro 2018 CCENT Course](https://app.itpro.tv/course-library/ccent-updated-2018/overview-ccent2018/?tagcategory=course-library&tag=cisco) - Remember you aren't getting the cert here, but watch the first few hours.<li>[Microsoft Network Fundamentals](https://www.youtube.com/playlist?list=PLsrZV8shpwjMbK0ElithYzT4dGuunT40U) - Concise and to the point!  Excellent videos.<li>Assosciated Certifications (Good references): Net+, CCENT, CCNA<li>[Cisco Packet Tracer](https://www.netacad.com/courses/packet-tracer) - Not only is this software free for personal use but they have some free intro courses there too.|
|Programming and Scripting|<li>[Learn Python.org](https://www.learnpython.org/)<li>[Under The Wire](https://underthewire.tech) - An awesome CTF to learn PowerShell.  Walkthroughs littered through out the internet if you get stuck.<li>[Python for Beginners with Mosh](https://www.youtube.com/watch?v=_uQrJ0TkZlc&t=8500s) - Programming with Mosh. He gets you functional in Python in 6 hours! Looks like a great course.<li>[Code School Season 1](https://www.youtube.com/playlist?list=PLcKpytGyWm9rYbF9URFAjKy2MyWKZe0KS) - Learn to code by following along to make a video game! [Season 2](https://www.youtube.com/watch?v=a_8lfRDls3Y). You don't need to do both seasons or even all of season 1. Remember we are going for the fundamentals.  The more you watch and learn the better, but its not necessary to be a developer to get into Cyber Security.<li>[Microsoft Instructional videos on programming with Python](https://www.youtube.com/playlist?list=PLsrZV8shpwjMbK0ElithYzT4dGuunT40U)<li>[EdX Python Course](https://www.edx.org/learn/python) - Free course from top academic and industry leaders.  A good dive into the science behind it.<li> [Googles Python Course](https://developers.google.com/edu/python/)<li>[Learn Python The Hardway](https://learnpythonthehardway.org/book/)|
|Windows|<li>[ITPro.tv Windows Server Windows 101](https://app.itpro.tv/course-library/server-101/overview-server101/) - GREAT intro course into Windows Servers and Administration. Comes with the assosciated E-Book!<li>[ITPro.tv PoSh Basics](https://app.itpro.tv/course-library/powershell-2017/2017/) - ITPro's take on PowerShell. Great course.<li>[PoSh-Hunter](https://posh-hunter.com/) - A jeopardy style Capture The Flag game to learn PowerShell for InfoSec nerds.<li>[Microsoft Video Series on PowerShell](https://www.youtube.com/playlist?list=PLsrZV8shpwjMXYBmmGodMMQV86xsSz1si) - Another great video series on PowerShell.<li>[Microsoft Virtual Academy Active Directory Course](https://www.youtube.com/watch?v=RPzcxdiyVCM&list=PLsrZV8shpwjOtIz4LFKFQ6uoCt7RowYUZ) - A video series on Active Directory from Microsoft.<li>[Cyber Mentors Active Directory Hacking Lab](https://youtu.be/_OseTyfXr3Q) - Admittedly outside the "general studies" path here but a good one on setting the AD lab up and quick intro, then hacking it.<li> Remember the targeted fundamentals here... you do not need to be an MCSA (Msoft Certified Systems Admin.) to get started.|
|Linux|**Recommended Linux Distro to Start With is: Ubuntu**<li>[Over The Wire Bandit](https://overthewire.org/wargames/bandit/) - The most fun way to learn Linux. This site has many other goodies beyond Bandit games.  Levels 0-10 are a solid intro into linux.<li>[Kali Linux Revealed Free Legit PDF Downlaod](https://kali.training/downloads/Kali-Linux-Revealed-1st-edition.pdf) - An extensive and **FREE** professional book on using linux!<li>[ITPro.tv Becoming A Linux Power User](https://www.itpro.tv/courses/linux/becominglinux-power-user/) - A great video series to level up zero's, beginners and intermediate users.<li> [TCM's Linux Course](https://youtu.be/rZsJieGi8os) - The TCM does it again.  A well thought out course in linux to get you started.<li>[Linux Journey](https://linuxjourney.com/) - An amazing resource! With HTML labs you can do this anywhere on the go.|

***

## Lab Set Ups and Advice

There are two approaches to having a lab environment:

1. Local
2. Remote

### Local Lab

A local lab is built either on your laptop or home built server.  Again, budget dependent.  Building a local lab is actually pretty easy and the process alone will teach you quite a bit.  The world is using a lot of virtualized systems and networks.  Any progress in learning you make here will be a win either way.

To build a local lab on your laptop you will need either of the following (yes there are many more but these are the main staples and finding walk throughs and tutorials are easy) pieces of software:

1. (Paid) VMware Workstation Pro or VMware Fusion for MacOS
2. (Free) VirtualBox

Sadly, you get what you pay for here.  While Virtual Box works fine enough it is certainly no VMware.  You will save hours of troubleshooting and work arounds with VMWare.  It is expensive.  Though its probably a legal gray area, you can find keys for cheap on E-Bay.  The [Cyber Mentors Active Directory Hacking Lab](https://youtu.be/_OseTyfXr3Q) is good crash course on setting up a security lab.  There are a ton of youtube walk throughs and blogs on how to do this.  More will be added here in the future.

#### Local Lab Cyber Range Set-Up Overview

A well outfitted local cyber range that can run on a laptop may look something like this:

|Subnet|Hosts|
|---|---|
|Internal|<li> Windows Domain Controller (D.C.)<li>Windows Client machine on the domain connected to file share on the D.C.<li>Google Rapid Response Server<li>Vulnerable Web Server that in both networks (this allows you to learn to pivot into the network)|
|External|<li> Kali Machine<li>Other Network Connection of the Vulnerable Web Server|

The Kali machine can be moved into the Internal Subnet for "Internal Pentesting" etc.

#### Where to Get Vulnerable VM's

[Vuln Hub](https://www.vulnhub.com/) - A collection of vulnerable virtual machines for your home lab given for free and include a lot of awesome walk-through's to learn from.

[Vuln Hubs Guide to Building A Lab](https://www.vulnhub.com/lab/) - A guided tour on building a home pentesting lab.

### Remote Labs

Another great resource are lab networks set-up and maintained for you to VPN into and go after vulnerable servers or follow along with exercises.

[Hack The Box](https://www.hackthebox.eu/) - One of the most popular pentesting lab environments.  In addition, they have forensics challenges etc with stand alone files.  The community can be very welcoming and educational.  You have to hack your way in to get a membership.  Just follow their directions and have fun!  They have free and paid tier memberships. Paid memberships are something like 12 bucks a month.  Their Discord community is top notch.

[PenTester Academy](https://www.pentesteracademy.com/) - The video quality isn't amazing, but the write-ups, walk throughs and lab environment are great. You can catch great deals on the membership from time to time.  The pricing is between $49 and $69 a month depending on when you catch them.  Well worth it for the [Attack and Defense Labs](https://www.pentesteracademy.com/).

[PenTester Labs](https://pentesterlab.com/) - These are great labs! They are pentesting focused but they have a lot other skills and labs for building your base knowledge.  Once you get a membership you download walkthroughs and an accompanying ISO (a virtual machine image).

***

## Security Specific Studies and InfoSec Immersion

**Start your immersion immediately!**

Once you have a good handle on fundamentals or need some movtivation (or just a break from the more basic 
stuff)

[Vuln Hubs List of Resources](https://www.vulnhub.com/) - A great list of security specific resources!

### Training Companies

[SANS!](https://www.sans.org/) - Hands down the best security training on the planet!  Instructors are highly vetted security professionals with time in the trenches in the area of studies that they teach.  They are pricey. **HINT**: If you can't afford $6-8K a course then look up how to become a [SANS facilitator](https://www.sans.org/work-study/).  By volunteering your time and efforts to help the classes happen you can get a course for about $1500 which is a steal!

A SANS cert is recognized immediately by members of the industry as truly demonstrating that the beholder really understands the topic and can execute the skills assosciated.

### Youtube Channels and Personalities

- [Live Overflow](https://www.youtube.com/channel/UClcE-kVhqyiHCcjYwcpfj9w) - This guy breaks down complex hacking concepts into smaller easier concepts.  He is a good teacher and entertaining.
- [IPPSec](https://www.youtube.com/channel/UCa6eh7gCkpPo5XXUDfygQQA) - One *the* best at cracking open boxes on Hack The Box and a great teacher.
- [Cyber Mentor](https://www.youtube.com/channel/UC0ArlFuFYMpEewyRBzdLHiw) - One the best teachers of penetration testing on the internet.  He really gears his videos towards beginners with plenty of new tricks for more experienced folks to pick up.
- [Pauls Security Weekly](https://www.youtube.com/channel/UCg--XBjJ50a9tUhTKXVPiqg) - Security Weekly is one the best podcasts to watch.  The Friday shows have great tech segments. The entire show is informative and entertaining.
- [Brakeing Down Security \(BDS\) Podcast](https://www.youtube.com/channel/UCZFjAqFb4A60M1TMa0t1KXw) - The BDS Podcast is one of the best places to stay up with current security trends.
- [BDS Videos](https://www.youtube.com/playlist?list=PLqJHxwXNn7guMA6hnzex-c12q0eqsIV_K) - Look around here.  There are a ton of free training courses and other gems buried through out.
- [Tyler Hudak Reverse Engineer Training](https://www.youtube.com/watch?v=GYam_nJKr6E) - A great class that is free!  Tyler Hudak is one of the best in the industry and is also a great teacher.
- [NahamSec](https://www.youtube.com/channel/UCCZDt7MuC3Hzs6IH4xODLBw) - A very talented and successful bug bounty hunter and hacker who loves to share techniques with his audiences.

### Twitter Accounts and Personalites

No particular order.

- Cyber Mentor (@thecybermentor)
- Jake Williams (@MalwareJake)
- Derek Root (@\_r00k\_)
- Tyler Hudak (@SecShoggoth)
- Live Overflow (@LiveOverflow)
- Brad from malware traffic (@malware_traffic)
- IPPSec (@ippsec)
- Azeria (@Fox0x01)
- Kody Kinzie (@KodyKinzie)
- Tinker (@TinkerSec)
- Jack Rhysider (@JackRhysider)
- Cyber Gibbons (@cybergibbons)
- Lesley Carhart (@hacks4pancakes)
- Paul Asadoorian (@securityweekly)
- Rob Lee (@robtlee)
- Ed Skoudis (@edskoudis)
- SANS DFIR (@sansforensics)
- MalwareTech (@MalwareTechBlog)
- Malware Unicorn (@malwareunicorn)
- Malware Breakdown (@DynamicAnalysis)
- SANS Institute (@SANSInstitute)
- Ben Sadeghipour (@NahamSec)

There are a ton more I am not recognizing here but this will get you started.  Welcome to the community! And it is a community.  Most hackers out there are some of the best primates on the planet who are willing to help, teach and share.

### Slack Channels

- **Brakeing Down Security**(BDS) - One the best collections of hackers on the planet.  This is easily one of the best places to hang out and chat, learn and share.  You're never alone with the Internet nearby.  You may soon find that your friends and family have little interest in your new passion.

### Discord Channels

- Cyber Mentor
- Hack the Box

### Podcasts

- Darknet Diaries
- Pauls Security Weekly
- Security Now
- Brakeing Down Security
- Brakeing Down Incident Response (It seems dead now but still worth listening to over and over again)
- SANS Internet Storm Center
- The Cyber Wire
- Smashing Security
- Hackable?
- Breach
***
<br>

## Beyond here is in the early stages of fleshing out

1. Career Paths and Guidance
2. Materials for Moving Beyond Foundations (to the Hacking!!)
***

## Career Paths and Guidance

### How to Decide

As you work on the fundamentals you will almost certainly come across various aspects of security that interest you.  All of the following are simply a different flavor of hacker.  They are all vital for any team to function.  A ***general*** lay out of the roles in the security field are (no particular order):

#### Red (Offensive Security):
- **Penetration Tester** - They find and validate vulnerabilities in networks and web applications by demonstrating an attack on that vulnerability.
- **Exploit Developer** - They find vulnerabilities in software and develop exploits to give an attacker unauthorized access to the software or the underlying system.
- **Red Team** - Similar to Penetration Testers except the aim is to not simply validate a vulnerability, but to emulate a realistic threat to that particular environment.  Most likely this means a longer time period for them to operate low and slow to avoid detection and remain in the network for a long(er) period of time.

**Note**: Offensive teams (white hat and black hat alike) are typically made up of specialists.  A rough outline of that looks something like this:

- Entry Team - The initial exploitation to team to get access.
- Developers - The team ready to develop custom malware as needed
- Post Exploitation Team - A collection of folks who are fast at Privilege Escalation and lateral movement.

#### Blue (Defensive Security):
- **Security Operations Center Analyst** - They analyze alerts from intrusion detection sensors and find the root cause of the issue to detect if it is an anomaly or a malicious actor.
- **Security Engineer** - They design and build solutions to support security objectives and requirements.
- **Developer** - Often just another blend of Engineer or even the same title; they automate defesnse systems and things like forensics triage.
- **Forensic Analyst** - 
- **Incident Responder** - 
- **Threat Hunter** - 

### General Bodies of Knowledge Per Role

None of this is "law".

Recommended certs below are merely recommendations and in now way should this list be taken as all inclusive or a rule to be followed.  It also in no way guaruntees successful employment in the respective fields.

**You do not need every cert listed to work in that field!**

For the SANS recommended pathway you should see [their official guidance](https://www.sans.org/cyber-security-career-roadmap).  They have a recommended [road map](https://www.sans.org/cyber-security-skills-roadmap).

### Engineering

|Recommendation|List|
|---|---|
|**CERTIFICATIONS**|<li>SANS Security 401 (GSEC)<li>Linux +|
|**SKILLSETS**|<li>Linux Power User and Administration<li>BASH<li>Python<li>Networking<li>Cloud Technologies (AWS and or Azure)|

### Defensive Forensics and Incident Response (DFIR)

|Recommendation|List|
|---|---|
|**CERTIFICATIONS**|<li>SANS Security 401 (GSEC)<li>SANS Forensics 500 (GCFE)<li>SANS Forensics 508 (GCFA)<li>SNAS Forensics 501 (GCED)<li>SANS Forensics 504 (GCIH)<li>SANS Forensics 503 (GCIA)<li>SEC +<li>CySA +|
|**SKILLSETS**|<li>Linux Power User<li>Linux Security<li>Windows Power User<li>Windows Security<li>Digital Forensics<li>Windows Systems Internals<li>Memory Forenics<li>Networking|

### Threat Hunting

|Recommendation|List|
|---|---|
|**CERTIFICATIONS**|<li>SANS Security 401 (GSEC)<li>SANS Forensics 504 (GCIH)<li>SANS Forensics 500 (GCFE)<li>SANS Forensics 508 (GCFA)<li>SANS Forensics 572 (GNFA)<li>SANS Forensics 503 (GCIA)<li>SEC +<li>CySA +|
|**SKILLSETS**|<li>Linux Power User<li>Linux Security<li>Windows Power User<li>Windows Security<li>Digital Forensics<li>Windows Systems Internals<li>Memory Forenics<li>Threat Intelligence Consumption<li>Security Automation<li>Networking|

### Malware Reverse Engineer

|Recommendation|List|
|---|---|
|**CERTIFICATIONS**|<li>SANS Security 610 (GREM)|
|**SKILLSETS**|<li>Assembly Code<li>Windows Security<li>Linux Security<li>Python<li>Java<li>C<li>HTML|

## Penetration Testing

|Recommendation|List|
|---|---|
|**CERTIFICATIONS**|<li>SANS Security 401 (GSEC)<li>Offensive Security Certified Professional<li>Offesnive Security Certified Engineer<li>SANS Network Penetration Testing SEC560 (GPEN)<li>SANS Web Application Penetration Testing SEC542 (GWAPT)<li>Penetration Test +|
|**SKILLSETS**|<li>Linux Power User<li>Linux Security<li>Windows Security<li>Python<li>BASH<li>Networking<li>Windows Security<li>Windows Sys Internals|

***
## Beyond Foundations and Onto Hacking!

It seems that if you want to become an offensive focused hacker there are a ton of free lab materials and instruction. If you want to focus on the blue team / defensive skillsets it seems to come down to paying a lot of money or reading a lot of books.  E-Learn Security has some Blue Team focused courses that look appealing but I have not personally tested them.

1. Red
2. Blue

### Red

Topic|Links
---|---
Labs / Vulnerable Machines | <li> [Hack The Box](https://www.hackthebox.eu/) - Seriously one of the best places to hang out, learn, have fun, and meet other hackers - oh... and loads of vulnerable machines.  Their discord is invaluable. <li> [Vulnhub](https://www.vulnhub.com/) - Clearing house of vulnerable machines. <li> [Juice Shop](https://www2.owasp.org/www-project-juice-shop/) - One of the greatest projects to teach you Web App Hacking.  The VulnWeb App for your own range along with walkthroughs.<li> [Lesser Known Web Attack lab (LKWA)](https://github.com/weev3/LKWA) <li> [Damn Vulnerable Web App DVWA](https://github.com/ethicalhack3r/DVWA)
WiFi Hacking | .
Web Application Hacking | .
Scanning | .
Using Exploits |.
Developiong Exploits | .
Privilege Escalation | .
Persistence | .
Lateral Movement | .

### Blue

Topic|Links
---|---
Infrastructure Build Out | .
SIEM Building | .
Logs Analysis | .
Threat Intel | .
Threat Hunting | .
Incident Response | .

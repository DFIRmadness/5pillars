# The Five Pillars of a Information/Cyber Security Professional

## TLD;DR:
To start, or level up, a career in Cyber Security you need to be proficient in five key areas of technical skills.  You don't have to *master* each one of them, but you need to have a good understanding of them.  Whether you want to go offense or defense you will need to be functional in these arena's.  The five areas are:

1. General Computing
2. Computer Networking
3. Scripting and Programming
4. Linux / MacOS
5. Windows

Don't be scared! While you won't learn it over night you only need the fundamentals.  That said, you also can't expect to get to where you need to be over night.  If you want to accel in this industry you must also **love** learning.  While it takes a lot of dedication a healthy balance is key.  Make sure your family and friends get time with you, or that you make time to do hobbies you love.

Lastly: Before you start.  Perhaps Penetration Testing is all that interests you - or "catching bad guys" is the only thing you want in life.  Remember that learning both sides of the force will benefit you.  The better your understanding of defense the more lethal you can be on offense. **There are probably 10 Blue (defense) jobs to Red (offense).  There are a lot of fun jobs outside of Penetration Testing.**

### Wait! Wait! Wait! Where is the hacking!? No where in the list is their hacking or security

Correct.  These are the fundamentals that both defense and offense require!  More focused security paths are add to the second section of this document.

Now on to the document...

# readme.txt
This document is a path forward for new, and experienced, cyber professionals to obtaining a concrete foundation of knowledge to enable them for success in the industry.  Mastering the basics of each functional area is required to operate on a cyber team (or alone) in a meaningful and effective way.  A lack of fundamentals in any one pillar can quickly render a team member ineffective during dynamic and rapidly evolving situations.  Conversely, no one person on the team should be, or can be, a cyber unicorn.

Ideally, everyone will have a specialty they excel at in addition to a solid baseline in the fundamentals.  It should not be expected that every one completely masters each pillar.  The intent is to master the fundamentals.  The fundamentals are simply primal blocks of knowledge of each topic; somewhere between the absolute basics and intermediate.  As an example, a team member should understand: sub-netting, routing, OSI model, packet capture, DNS and analysis basics.  This does not mean they need to be Cisco network engineers with a CCNA.

## What You Need (Equipment)

You do not need a $3000 Gaming Laptop or a Desktop with 2 GPU's and 10 TB SSD.  This is completely based on your budget.  You can get away with a $500 laptop if needed. I will explain.

|Level|Explaination|
|---|---|
|Good ($500)|A computer capable of web browsing and reading books. Seriously. The trade off is you will need to pay for web accessible labs versus building a small virtualized environment.|
|Better ($1100ish)|A laptop capable of building a small lab of 2-3 Virtual Machines. Something like an i7, 16 Gigs or RAM and 500 Gigs storage.|
|Best|The sky is the limit.  Something capable of cracking passwords decently (read a mid tier GPU), i9, 32 Gigs, and 1 TB storage.|

**Note**: A GPU is mentioned for password cracking.  You absolutely DO NOT NEED ONE to learn or level up cyber security.  Keep in mind this document is about learning and labs you encounter will be geared towards this anyhow.  You get the same training value in cracking a simple password with your CPU as you do with letting a GPU pound on a hash for 2 weeks.

# The Five Pillars (Functional Areas) of Cyber Security

1. General Computing
2. Computer Networking
3. Programming and Scripting
4. Windows
5. Linux

## Fundamentals Breakdown
The following are key skill sets within each pillar.  It is not an exhaustive list.

|General Computing|Networking|Programming and Scripting|Windows|Linux|

|Pillar aka Functional Area|Skills|
|---|---|
|**General Computing**|Hardware Components: <li>CPU<li>RAM<li>SSD/HDD<li>Science:<br>Threads<li>Processes<li>Process Trees|
|**Networking**|<li>OSI Model<li>TCP/IP Model<li>TCP vs UDP<li>Packet Analysis<li>Packet Capture<li>Routing<li>DNS<li>ARP|
|**Programming and Scripting**|<li>Python<li>Powershell<li>BASH<li>Bonus: C++ or C#|
|**Windows**|<li>Registry (5 Hives)<li>Volume Shadow Copies<li>UAC<li>Memory Paging<li>.msi vs .exe<li>DLLs<li>RIDs<li>SIDs<li>Tokens<li>Network Profiles<li>Server vs. Workstation<li>Commands: <li>Netstat<li>whoami<li>ping<li>ipconfig<li>Powershell Remoting<li>Tools: Sysinternals<li>Process Hacker.|
|**Linux**|<li>Directory Hierarchy<li>sudo accounts<li>/etc/shadow and /etc/passwd<li>ssh<li>telnet<li>ftp<li>Software Repositories<li>Be Familiar with Distributions: Kali, Debian, Ubuntu, CentOS, RedHat<li>Commands: w, find, whoami, which, who, ss, watch, ssh, lsof, ssh-add, top, htop, sudo, nano and vim.|

Yes.  That is a lot.  First, to be good in this industry you will want to be *familiar* with each of these things and beyond.  You will not learn it all over night nor should you try.  Just refer back to this often as a guide.  Be patient. Enjoy the journey.

## Desired Endstate of Each Pillar

The following are goals to shoot for in each area.  If you can meet each of these you will be a competent professional ready to shine at interviews and be an asset to any team you join.

|Pillar aka Functional Area|Skills|
|---|---|
|**General Computing**|Explain the difference between something being stored in memory vs. something stored on disk. Explain the basics of process injection. Explain the difference between killing a thread and killing a process.|
|**Networking**|Using all 7 layers of the OSI model explain how a piece of information flows from your computer to google.com and back when you type `ping google.com`.|
|**Programming and Scripting**|Be able to write a basic script to automate a simple task; and be able to read and understand the overall idea of what someone else’s script is attempting to do.|
|**Windows**|Be able to explain the function of the registry, the UAC, and tokens. Be able to maneuver the OS with command line only and look for network connections and their related processes.|
|**Linux**|Be able to explain sudo, shadow and passwd files, user groups and proper installation and maintenance of software (repos).Be able to maneuver the OS with command line only and look for network connections and their related processes.|

*Remember you have to know how things work to exploit them.  You have to know what right looks like to find the gaps in security.*

# Resources:  How Do We Get 'There'?

## General Approach

- Start free and cheap to see if you like it.  You may find it isn't for you.
- While studying the five functional areas ensure you are getting hands on keyboard and not just your nose in a book.  Do both!  Also - sprinkle in security lessons along with your general studies.  Also, try and rotate through the five continuously so you are leveling up in them all somewhat evenly.  Of course, you can do it in a serial fashion (in order one through five) if you want.  However, these skills are perishable. This means if you go through in order and haven't touched networking in 5 months (or 2 books ago) it is going to be rusty and you will have to relearn it!!!
- Try and have fun!
- Keep an eye out for things you think you may be passionate about!  You will want to specialize later on.

## Recommended Security Focused Resources to go with General Studies

### Hack and Detect: Leveraging the Cyber Kill Chain for Practical Hacking and its Detection via Network Forensics

![Hack and Detect](https://images-na.ssl-images-amazon.com/images/I/51CyN7q7LaL._SX403_BO1,204,203,200_.jpg)

The book to start with: [Hack and Detect](https://www.amazon.com/Learning-Practicing-Leveraging-Practical-Detection/dp/1731254458) ! by Nik Alleyne.  This book can be purchased or viewed free with a Kindle Unlimited account.  This book can't be recommended enough for beginners and experienced folks alike.  It is amazing in its presentation of both offense and defense methodologies with break downs and explanations of each and every command. **This is a great book to sprinkle in along with the 5 pillars studies. Consider it the quick start guide into security.**

### The Cyber Mentor

![The Cyber Mentor](https://yt3.ggpht.com/a/AGF-l7_-iGuCNgJT5TzZNBVoO4V6tCmHv6KOrRMNIA=s288-c-k-c0xffffffff-no-rj-mo)

[The Cyber Mentor](https://www.thecybermentor.com/beginner-linux-for-ethical-hackers) hands down is one of the first people you should start watching as you build your skill sets.  He focuses on Penetration Testing.  He, along with the community he has created in discord etc., will be a great place to find motivation, knowledge and support. Even if you want to go blue side / foreniscs etc. you will need an understanding of how people pentrating networks etc. move through the network and he does a superb job of teaching and explaining.

## General Studies Resources

These resources will have materials for all or multiple pillars.

- [Safari Books Online](https://www.safaribooksonline.com/topics) Free for military members and families
- [Humble Bundle Books](https://www.humblebundle.com/books) They often (every few weeks) have cheap (12 dollars) bundles of books
- [packtpub daily free book give away](https://www.packtpub.com/free-learning) Free IT and Security books given away daily! Some really good ones on occassion.
- [IT Pro TV](https://www.itpro.tv/) First on the list to cost some money.  Hunt for some coupons.  They are well worth it.  THey have current, and constantly updated, video series on everything in the five pillars and beyond.  Additionally, they offer virtual labs you can remote into with step by step guides, test question banks and more.  Its an amazing resource.
- [Twitter](https://www.twitter.com) Later there will be a list of people to follow but essentially you can get started with #infosec and #dfir and start a daily ingest of what is going on in the community.  Immerse yourself!


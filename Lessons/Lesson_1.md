-- *Slide* --

# Roll up to the Research Cloud mystery tour!

your tour guide is ...

-- *Slide End* --

(First: Do a personal introduction. Who am I, and why am qualified to teach this course?)

-- *Slide* --

-- *Slide* --

## This is a... ?

<div align="left">
▢ wash hands with soap, <br/>
▢ clean the patient’s skin with chlorhexidine antiseptic, <br/>
▢ put sterile drapes over the entire patient, <br/>
▢ put on a sterile mask, hat, gown, and gloves, <br/>
▢ put a sterile dressing over the catheter site once the line is in
</div>

-- *Slide End* --

**Question:** Does anyone know what this is?

-- *Slide* --

## A line infection checklist

<div align="left">
▢ wash hands with soap, <br/>
▢ clean the patient’s skin with chlorhexidine antiseptic, <br/>
▢ put sterile drapes over the entire patient, <br/>
▢ put on a sterile mask, hat, gown, and gloves, <br/>
▢ put a sterile dressing over the catheter site once the line is in
</div>

-- *Slide End* --

**Answer:** In 2001 a critical-care specialist at John Hopkins Hospital designed a checklist to prevent line 
infections. This is it!

Line infection steps have been known and taught for years. But frustratingly line infections still
happen. So the specialist gave this checklist to nurses and then asked them to observe the doctors for a 
month as they put lines into patients, and record how often they completed each step. 

In more than a third of patients, they skipped at least one of the steps.

The specialist then asked the nurses stop the doctors whenever a step was skipped.

The ten-day line-infection rate went from eleven per cent to zero. 

So why are you being shown a line infection checklist on a session about the research cloud?

This story inspired a software company to introduce a checklist for deploying applications into production.

The rate of problems encountered during deployment fell to zero.

So with that in mind we've prepared some checklists for you use to launch your free PC's on the Research Cloud. 

    Now stop, and ask the audience to pair up. 
    
    Then let them know that their pair is the people person they will turn to first for help if they
    have any problems with the lesson. They are only to put up red sticky notes if both people are stuck. 

-- *Slide* --

## Sticky note usage

* <span style="color:red">&#9632;</span> = Help me!
* <span style="color:green">&#9632;</span> = I'm ready to move on...

-- *Slide End* --

-- *Slide* --

## Launch your instance!

Use following checklist to launch an instance!

http://tinyurl.com/launch-pdf

* <span style="color:red">&#9632;</span> = Help me!
* <span style="color:green">&#9632;</span> = I'm ready to move on...

-- *Slide End* --

-- *Slide* --

## Trial Projects

-- *Slide End* --

The first time you log on to the Research Cloud dashboard, you get given a **free** trial project, with three-months 
worth of cpu time if you run the largest computer you are allowed to on it all the time. 

So you've just launched a platform to publish your kitten research to the world using your trial project.

Easy, wasn't it?

A project on the Research Cloud is just a way to group people together and to set constraints on what operations 
they can do on the Research Cloud. You can belong to more than one project. 

**NB** Demonstrate the project drop down to show that this is where you switch between projects. Call it the "project
drop down. Note that if this is your first time on the cloud you should only have one project. 

If you only use the smallest computer for short periods of time on the Research Cloud, and **terminate** them
religiously after each run, your trial project will last far longer. 

When your trial project has expired you can still log in to the dashboard to view and request 
a project allocation on the research cloud. You can even request to extend the duration of your
existing trial project.

Regardless of your path,  your trial project should give you the time to learn the Research Cloud ropes!

-- *Slide* --

## What's your trial project lifetime?

1. for ever and ever after
1. three months from today
1. depends on how much I use it... 

-- *Slide End* --

**Answer: C** But it will be B if run your free computer(s) flat out!

So always **terminate** your free computers once you've finished working with them. That way you can avoid the
asking for allocation extensions paperwork.

-- *Slide* --

## Terminate your free computer!

Can you work out how to terminate your free computer? 
Test your discovery by terminating the one you've just started.

* <span style="color:red">&#9632;</span> = Help me!
* <span style="color:green">&#9632;</span> = I'm ready to move on...

-- *Slide End* --

-- *Slide* --

## Why do you care about this?

-- *Slide End* --

Two researchers at a well known University, who and which shall remain nameless to protect the innocent, needed to 
do some fairly complex statistical analysis. So out of their grant money they bought two powerful computers, at a 
cost of $10 000 per machine to run[ MatLab](http://au.mathworks.com/products/matlab/?nocookie=true) on. 

But on the first run, they found that the machines couldn’t work with their data sets. The machines were underpowered! 
They were forced to iteratively spend money on upgrading those machines, until finally, one was able to perform the 
required analysis. It had taken them 12 months from the date of purchase to get to this point.

If, instead of purchasing hardware, they had turned to the cloud, just has you have now done, 
they would have been able to have had their initial machine running within minutes. 

If it was underpowered, they would have been able to upgrade it to a larger machine, again within a matter of minutes. 
They probably wouldn’t even have had to re-install the software.  

The really good news for researchers is that everyone with an AAF login can experience this game changer for themselves, 
at no cost: through the national Research Cloud (NeCTAR) project.

If Research Cloud had been around with their current funding model in place when those two researchers were setting up 
their project that’s $20 000 of grant money that could have been used elsewhere!

-- *Slide* --

### Currently, how much does it cost a researcher to use the Research Cloud?

1. Gazillions!
1. Squillions!
1. Billions!
1. Some unknown $$!
1. It’s currently free **at the point of service**

-- *Slide End* --

---

**Answer E**

---

And all of this is backed by a research facing organization that is not driven by profit.

But before you go rushing to the Research Cloud, you have to understand that the cloud
is a not quite the same as dedicated computer on your desktop! 

What we are going to do today is to give you enough information to get your own machines up and running on the 
Research Cloud, and importantly, where to go to learn the gotcha’s.

-- *Slide* --

## Security Groups

-- *Slide End* --


One of the things you needed to do in launching your free PC was to select a security group called 'http'.

Let's see if I can explain this step in a bit more detail.

A security group is a set of rules used to create a firewall for your computer in the cloud. 

-- *Slide* --

## What's a firewall?

1. A wall used to prevent the spread of fire
1. An attractive wall made from fire
1. Something that selects what network traffic that can pass
1. That what's built on top of an ice foundation
1. A popular barbecue cooking style

-- *Slide End* --

**Answer A and C**

Naturally, on the the Research Cloud a security group selects what network traffic that can pass.

    Try to draw something like the following on a white board as you talk...

    +-----------+    Network              +--------------+
    |           |                         |              |
    |           |  +--+  +--+  +--+  +-+  |              |
    | Server    +--+22+--+22+--+30+--+1+->+     Client   |
    |           |  +--+  +--+  +--+  +-+  |              |
    |           |                         |              |
    +-----------+                         +--------------+

How firewalls work is that network messages destined for a computer are broken up into packets. Once a packet
reaches a computer how does the computer know which application the packet is intended for? 

Well, the operating system allocates a different number to each running application. Then all network packets that
carry that number are sent to that application. This number is called a port number.

By default the firewall defined by a security group allows all outgoing network packets to pass, 
but blocks all incoming network packets. But you can open "ports" in the security group, hence allowing
inbound network packets with a matching port number through to the application on the instance.

    If you get lots of blank looks, the following twisted metaphor might help:
    
    Imagine that Australia was a computer: and that containers on ships heading to Australia were the network packets.
    And stretching the metaphor even more, that cities were applications. 
    
    If you can get your head around that tortured metaphor, then its easy. Each container has a port number painted on it.
    Then when the ship docks, customs will only allow those containers with the correct port number off of it.
    
    So what if each network packet also had an associated number indicating the destination application? Then the security
    group, acting as a customs officer, could reject all the packets that were not acceptable for a given application!
    
    Well, strange to say, each packet on the network gets given a port number, indicating the application it is intended
    to go to. And well known applications get well known port numbers. So web servers use port 80, for example.
    
    So simply put a security group allows you to define the port numbers that packets from the outside world must have if 
    they are going to be allowed to reach your cloud computer. 
    
    Any packets with a different port number don’t even make it to your machine. They are just thrown overboard!

Your trial project comes with several pre-configured security groups. But if you request a project via an allocation
you get no security group pre-configured for you. And what if you want to run an application that doesn't fit into
the predefined ones? Simple. 

You just have to define your own security group. And so that's what you'll do now. 
You are going to create a single security group that allows traffic to reach two applications.

And of course we've created a checklist to guide you. This ones a little more formal.

-- *Slide* --

### Create a Security Group with the help of the security group checklist:

http://tinyurl.com/creating-a-security-group

* <span style="color:red">&#9632;</span> = Help me!
* <span style="color:green">&#9632;</span> = I'm ready to move on...

-- *Slide End* --

**NB** The same security group can be applied to many computers in your project.

**NB:** You can edit a security group at any time.  And the changes will immediately apply to all running virtual 
machines that have that security group applied.

**NB:** This also means that if you share security groups amongst computers, you have to be careful: 
if you change rules for one server, you might inadvertently break another.

-- *Slide* --

**I change the rules in a security group by removing port 80 (http). Mysteriously a web server on another VM in the 
project stops "working". Could it be because:**

1. The security group was shared with the other machine?
1. The web server inexplicably broke?
1. The other machine itself failed?
1. NeCTAR are experiencing a network problem?
1. All of the above... ☹

-- *Slide End* --

Walk through each option, describing how it could affect the instance you are trying to reach.

**Answer: E.** Yes, it’s true. The research cloud can experience network issues from time to time. 

- - - 

**30 minutes to here**
 
- - -

## The Terminal 

-- *Slide* --

**Your free PC on the cloud has no keyboard, monitor or mouse. Do you have any hope of installing or removing
software on it?**

* <span style="color:red">&#9632;</span> = No, doom and gloom!
* <span style="color:green">&#9632;</span> = Somehow, somewhere, there is hope!

-- *Slide End* --

**Answer:** The Greens have it: there's always hope!

    Try to draw something like the following on a white board as you talk...
    +-----------------------+                  +------------------------+
    |     Local PC          |                  |     Remote PC          |
    |                       |                  |                        |
    |   +----------+        |                  |   +------------+       |
    |   |  Terminal|        |     ssh          |   |  Terminal  |       |
    |   |          +-----------------------------> |            |       |
    |   +----------+        |                  |   +------------+       |
    +-----------------------+                  +------------------------+

In the old days, because computing was so expensive, many people would share a single computer by means of terminals. 
A terminal was a keyboard and a screen, and many terminals could be attached to a single computer.
 
These terminals supported a basic text based interface that allowed you to do work on the computer it was attached to.

You'll be unsurprised to learn that with the passage of time, people wrote programs that emulated these terminals. So 
one computer could act as the terminal for another computer - or even itself!

So you can run a terminal application on your computer to do work on your own computer. You might recognize it as the
"Command Line"

Its very simple to run: and if you take the time to learn about it, all your friends will think you are a computer
guru!

But the main advantage for us is that your local terminal program can also be used to run a terminal on 
another computer. 

-- *Slide* --

## This is our magic

```bash
ssh
```

`ssh` stands for **s**ecure **sh**ell. 

-- *Slide End* --

    Try to draw the following on a white board as you talk...

It connects a terminal on one machine to another target machine, thus allowing 
you to use the text based interface on the target machine. It kind of teleports 
the target machine terminal to yours…

You can think of `ssh` as your cloud login command.

Which is why you've been seeing the `ssh` references in the security groups.

`ssh` uses public key cryptography to connect with the target machine. 

Which needs key pairs to work. 

-- *Slide* --

# Key Pairs

-- *Slide End* --

"What's a key pair?" I hear you not ask.

    Could the following also be demonstrated through a box and a lock?
    Or a paint video?

Ok way back when, in the olden days, say when Greece ruled the known universe, and say you were a wealthy merchant 
named Pem, lets agree that I borrowed a lot of money from you and then relocated to a remote city.

How would I know that the man in front of me claiming to be your emissary, now here to collect your cash for you, was 
the correct person?

And the answer used by some was ingenious. We’d take a clay seal and break it in half. I’d take half, you’d keep half. 
Your emissary would hand me the half of the seal that you’d given me and if it matched mine I’d hand the cash over. 
Obviously there is quite a lot of trust in the system. And you’d want to keep your half of the seal private: 
under lock and key. Me? Meh, not so much.

Keys are a very similar concept. They have two halves. Anything you encrypt with one half can be decrypted by anyone 
with the other half.

There's a special page on the research cloud dashboard that helps you to create key pairs. 
NeCTAR will keep one, the public key, and you will download the private key, the other half of the pair, 
to your local machine.

When NeCTAR fire up a machine for you, they can inject the public key into your machine. 
Anyone with the private key will be able to communicate with and control that machine. 
Like the clay seals of yesteryear, you want to keep your private key in a secure location. 

And again, we've create a checklist to help you create a keypair.

-- *Slide* --

### Create a Keypair with the help of the key pair checklist:

http://tinyurl.com/creating-a-keypair

* <span style="color:red">&#9632;</span> = Help me!
* <span style="color:green">&#9632;</span> = I'm ready to move on...

-- *Slide End* --

Ok: so now you have created a key pair and a security group. 

Let's use them to fire up a new free pc on the Research cloud.

But before we do that there's another part of the Research Cloud that we should know about.

-- *Slide* --

## Find the images tab on the dashboard.

(Project -> Compute -> Images Tab)

* <span style="color:red">&#9632;</span> = What? There's no such tab!
* <span style="color:green">&#9632;</span> = I'm ready to move on...

-- *Slide End* --

**Concept alert:** What we have here is simply a listing of files, each being a copy of a hard drives contents. Each 
file is termed an "image".

How the Research Cloud works is that you select a file that is a copy of the contents of a hard drive when you 
launch your machine. That file is copied across to wherever your machine is going to be run and becomes the 
basis of your new machine's hard drive.

**Demonstrate:** Do a whiteboard drawing of this.

Across the top of the list of images are four filters that are reasonably self explanatory.

1. Project - the images that are visible only to your project. 
2. NeCTAR official - the images that Research Cloud share with the world. These are simply images of operating 
   systems.  Whilst on this list NeCTAR is keeping them current. 
3. Shared with me - the images that other users have opted to share with you. 
   Sharing images with others requires the use of command line tools, so it's a more advanced topic that you will
   have to leave till you are more familiar with the research cloud.
4. Public - the list of images that others have shared with the world. These mostly already have applications
   installed on them, ready to run.

As new users to the Research Cloud it is unlikely that you’ll have either project or shared images. Those come 
with time. 

And it's from here that we are going to launch our computer this time.

-- *Slide* --

### Use this new checklist to launch an instance:

http://tinyurl.com/starting-an-instance

* <span style="color:red">&#9632;</span> = Help me!
* <span style="color:green">&#9632;</span> = I'm ready to move on...
 
-- *Slide End* --

BTW, this checklist is a far more comprehensive one than the last. Now you not only selected a security group.
You also set the keypair that you are going to use to ssh into your computer on the cloud.

-- *Slide* --

### Was the IP number of your first computer in the cloud the same as the IP number of your second?

* <span style="color:red">&#9632;</span> = No
* <span style="color:green">&#9632;</span> = Yes

-- *Slide End* --

Here both answers can be correct!

NeCTAR have a pool of IP numbers. Every time you spin up a computer, an IP number is taken out of the pool and
assigned to the computer. Every time you terminate a computer the IP number is returned to the pool. So you may
get lucky and get the same IP number. But the chances are you will get a different IP number with every run.

-- *Slide* --

## Hmm...

You fire up your machine. Days later, you realise that you’ve lost your private key. Will you ever be able to 
access and control your machine from that point onward?

* <span style="color:red">&#9632;</span> = No, not without a world of pain!
* <span style="color:green">&#9632;</span> = Easily!

-- *Slide End* --

**A:** No, the chances are extremely high that you've lost your machine for good.

- - - 

**45 minutes to here**

**STAND** Ask everyone to stand and stretch. You're at the halfway point! Whilst they stand give a recap:

You've now fired up a computer on the Research Cloud twice! And created a security group and a keypair.
That's not bad going. Think of the $20K those two researchers could have saved if they had been here today!
 
- - -

Now, with the magic of `ssh` we are going to open our administrator console on our computer in the cloud.

This is the basic form our `ssh` command will take:

-- *Slide* --

## ssh

```bash
ssh  -i <key> <user>@<address>
```

Eg: Along the lines of:

```bash
ssh -i tut_dev.pem ubuntu@144.6.225.224
```

-- *Slide End* --

So here:

* the `key` is the path to and the key file itself
* the `user` is the name of the user account on the remote machine that we are connecting as.  
  Different operating systems have different default user accounts.
* the `address` is the IP address of the Virtual Machine that we read off of the dashboard.


-- *Slide* --

### Find and run the terminal program, or command line, on your computer.

OSX users can do a Spotlight Search for 'terminal'. 

Babun users simply click on the Babun desktop icon.

* <span style="color:red">&#9632;</span> = Help me!
* <span style="color:green">&#9632;</span> = I'm ready to move on...
 
-- *Slide End* --


-- *Slide* --

### Connect to your remote instance via ssh. e.g.:

```bash
ssh -i tut_dev.pem ubuntu@144.6.225.224
```

### PS: Windows users...

To find your key file, 
prefix `/cygdrive/c/` to the directory 
that you saved your key file in...

-- *Slide End* --

If everyone could try to connect to their server using the ssh command, that would be wonderful.

-- *Slide* --

## When you are asked:

```bash
The authenticity of host '144.6.225.224 (144.6.225.224)' can't be established.
RSA key fingerprint is d8:14:f5:85:5f:52:cb:f2:53:56:9d:b3:0c:1e:a3:1f.
Are you sure you want to continue connecting (yes/no)?
```

simply type "yes".

* <span style="color:red">&#9632;</span> = I've hit an error message!
* <span style="color:green">&#9632;</span> = I'm ready to move on...

-- *Slide End* --

BTW, I'm hoping that you all fail - with an error message! But Windows users won't
 
-- *Slide* --

## Is this your error message?

```bash
@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
@         WARNING: UNPROTECTED PRIVATE KEY FILE!          @
@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
Permissions 0777 for '.ssh/tut_dev.pem' are too open.
It is required that your private key files are NOT accessible by others.
This private key will be ignored.
bad permissions: ignore key: .ssh/nectar_dev.pem
ubuntu@144.6.225.224's password: 
```
* <span style="color:red">&#9632;</span> = Yes: that's very like my error!
* <span style="color:green">&#9632;</span> = I'm ready to move on
* Hold up both sticky notes if you are in any other state...
 
-- *Slide End* --

What's going on here? Anyone want to hazard an explanation?

The error message is very descriptive. ```ssh``` is rejecting your key file because anyone who has access to your
machine can read it. And so can use it!
 
You need to tighten up the permissions on this file so that only you can access it.

Hit control-c to exit the password prompt.

This is where the change file mode command, `chmod` comes to the rescue!


-- *Slide* --

## Change Mode

The `chmod` command (**ch**ange file **mod**e)

```bash
chmod u=rw,go-rwx <path to key> 
```

Modify the permissions on your key file so that only you can read or write it.

* <span style="color:red">&#9632;</span> = Help me!
* <span style="color:green">&#9632;</span> = I'm ready to move on...

-- *Slide End* --

Here the command is allowing me (the current **u**ser) to be able to **r**ead and **w**rite the file, and to exclude 
any **g**roups and **o**thers from being able to **r**ead, **w**rite or try to run (e**x**ecute) it.

Retry the ssh command.

Hopefully, you are now met with something along following lines

-- *Slide* --

## Does this look familiar?

```bash
Welcome to Ubuntu 14.04.2 LTS (GNU/Linux 3.13.0-36-generic x86_64)

 * Documentation:  https://help.ubuntu.com/
Last login: Mon Mar 30 01:27:13 2015 from hqrouter.vpac.org
ubuntu@drupal:~$ 
```

* <span style="color:red">&#9632;</span> = No - Help!
* <span style="color:green">&#9632;</span> = Yes, I'm OK...

-- *Slide End* --

-- *Slide* --

## The next piece of magic

```bash
apt-get
```

-- *Slide End* --


`apt-get` is the front end for a program called a package manager. Its rather like the appstore on your phone, and
allows you to add, remove, and upgrade applications. So we now going to update all the applications on your
PC. This means that all the fixes and security releases since the image was created all those months ago
will be applied. 

-- *Slide* --

## Try to execute the command:

```bash
apt-get update
```

-- *Slide End* --

-- *Slide* --

## Help!

Again, something has gone wrong! You should be met with the message:

```bash
E: Could not open lock file /var/lib/apt/lists/lock - open (13: Permission denied)
E: Unable to lock directory /var/lib/apt/lists/
E: Could not open lock file /var/lib/dpkg/lock - open (13: Permission denied)
E: Unable to lock the administration directory (/var/lib/dpkg/), are you root?
```

* <span style="color:red">&#9632;</span> = Help me!
* <span style="color:green">&#9632;</span> = Yes, this is what I'm seeing...

-- *Slide End* --

You are seeing this error because you are trying to perform system administration, and the ubuntu user you signed in 
as is not the super user normally allowed to do system administration.

But don't panic!

-- *Slide* --

## SUDO

The `sudo` command (**s**uper **u**ser **do**) comes to your help. 

It allows the ubuntu user to run commands with the security privileges of the super user.

-- *Slide End* --

Think of `sudo` as being like a safety catch. When you find yourself using it, double check what you are about to
do!

-- *Slide* --

Try to execute the command again, this time with `sudo`:

```bash
sudo apt-get update
```

-- *Slide End* --

You should now see a whole lot of gets scrolling by, as the operating system updates its lists of installed and 
available software.

-- *Slide* --

## Then execute the command:

```bash
sudo apt-get upgrade
```

If your system has software on it that needs an upgrade you will be met by a request to perform the upgrade. Something
like:

```bash
After this operation, 4,096 B of additional disk space will be used.
Do you want to continue? [Y/n]
```
-- *Slide End* --

In this case, reply, 'Y'.

Hold up a Green sticky note when you've done this.
And a Red sticky note if you need help.

-- *Slide* --

<img src="//imgs.xkcd.com/comics/sandwich.png" title="Proper User Policy apparently means Simon Says." alt="Sandwich">

-- *Slide End* --

To see how easy it is to use the package manager, install the fortune application.

-- *Slide* --

## Install fortune

```bash
sudo apt-get install fortune-mod
```

* <span style="color:red">&#9632;</span> = Help me!
* <span style="color:green">&#9632;</span> = I'm ready to move on...

-- *Slide End* --

-- *Slide* --

## Run fortune

```bash
fortune
```

* <span style="color:red">&#9632;</span> = Help me!
* <span style="color:green">&#9632;</span> = I'm ready to move on...

-- *Slide End* --

So what you've just done is used `apt-get`, the front end to the package manager to update the system
and then to add an application. Feel the power!

Now you are finished working on your virtual machine, do the following:

-- *Slide* --

### End your ssh session

Type 

```bash
exit
```

You should see the following:

```bash
logout
Connection to <some_ip_number> closed
```

-- *Slide End* --

You have now closed the ssh connection to the remote machine. The teleportation magic is over!

Hold up a Green sticky note if you saw 'exit'.
And a Red sticky note if you did not.

-- *Slide* --

### Remove the ssh rule from the security group

Find the security group in the dashboard and remove the ssh rule.

Now try to ssh into your virtual machine again.

What happens?

-- *Slide End* --

Hold up a Green sticky note if you have managed to teleport into your remote machine..
And a Red sticky note if you haven't.

I'm hoping to see a sea of Red!

-- *Slide* --

### Add an ssh rule to the security group

Find the security group and re-add a rule that allows ssh.

Try to ssh into your virtual machine again.

What happens?

-- *Slide End* --

Hold up a Green sticky note if you have managed to teleport into your remote machine..
And a Red sticky note if you haven't.

I'm hoping to see a sea of Green!

The takeaway: Security groups can stop you from accessing your server if they aren't configured properly. 

It is a good idea to remove the ssh rule from the security group when you don't kneed it. This stops hackers from 
trying to access your machine.

So, we've just connected to our remote computer in the cloud using a program called ssh. On that remote computer
we have updated the software using a command line interface - an interface that is simply used by just typing in
words!

-- *Slide* --

## Terminate your free computer!

Check to see if you have any computers running (Compute-Instances).

If so, terminate them.

* <span style="color:red">&#9632;</span> = Help me!
* <span style="color:green">&#9632;</span> = I'm ready to move on...

-- *Slide End* --


-- *Slide* --

### Why did we terminate our computers?

1. To conserve our trial tenancy
1. To conserve our trial tenancy
1. To conserve our trial tenancy
1. To conserve our trial tenancy
1. All of the above

-- *Slide End* --

**Answer:** The E's have it!

-- *Slide* --

# The object store

Your supercharged USB stick

-- *Slide End* --

There's another powerful reason to use the Research Cloud: access to storage which is kept locally in Australia and 
available on the high speed [AARNET](https://www.aarnet.edu.au/about-us) backbone. There are different forms of
storage available: but we are only going to look at the Object Store.

The *Object Store* is an ideal replacement for the usb sticks that some people tend to carry 
around with them: You can upload and download files to it from any browser: and you can keep those files private,
or share those files with the world if you want.

Some people even publish whole websites from the object store!
 
On top of that, any file that you give it is backed up in triplicate, and each of the the copies is monitored for 
degradation.

Any bit rot, and the faulty file is replaced with a good copy. 

-- *Slide* --

### On the NeCTAR dashboard what's the Object Store's child tab called?

1. Directories
1. Loading
1. Containers
1. Boxes
1. Objects

-- *Slide End* --

Please hold up a Red sticky note if you need help finding it
Otherwise, hold up your answer...

**Answer:** C: Containers.

There is some terminology that you need to know.

Files are called objects. Unsurprisingly, since it's called the object store.
 
And objects go into containers.

And this tab is where you create containers, and then put files (or objects) into the containers.

It is a very, very simple interface. So simple it's actually clunky IMHO. 

Now for a challenge. There is no checklist!

-- *Slide* --

## Save an image to the object store

Can you create a container named **resbaz 2016**
in the Object Store and upload a picture to it? 

**NB:** preserve the file extension as you name the object.

Once your done, can you delete it all?

-- *Slide End* --

Please hold up a Red sticky note if you need help
and a Green one once you are done.

-- *Slide* --

## Share an image

<div align="left">
▢ Create a container (make it public)<br/>
▢ Upload a picture into it <br/>
▢ Click on the resultant public link <br/>
▢ Append '/' and the object name to the browser address <br/>
▢ Do you see the image in your browser? <br/>
</div>

-- *Slide End* --

Please hold up a Red sticky note if you need help
and a Green one once you are done.

You have just worked out how to build a url in your browser to access items in a container. 
If the container is public you can share these addresses and others will be able to access those 
files.

-- *Slide* --

### You mark a container as being public. Which of the following are affected:

1. Just the first file in the container
1. None of the files in the container
1. The mittens of celestial kittens
1. All of the files in the container
1. The last file in the container

?

-- *Slide End* --

**Answer:** D: all of the files in the container. So you need to use this feature with care!

- - - 

15 Object Store is 10 -15 minutes.
 
- - -

-- *Slide* --

## The settings drop down

-- *Slide End* --

The drop down on the right is the settings drop down. It’s not exactly the most intuitive of drop downs IMHO.

If you select it, you’ll see that there are three options: "Settings", "Help" and "Sign Out".

-- *Slide* --

## The Help Menu

Select "help" on the settings drop down.

* <span style="color:red">&#9632;</span> = I'm still looking at the dashboard.
* <span style="color:green">&#9632;</span> = Another web page has opened!

-- *Slide End* --
       
Hopefully a new tab has opened, taking you to the homepage of the Research Cloud support site. 

The support site has loads of useful documentation. It has beginners guides, online training,
and knowledge bases.

Scroll down to see the quick links to all this goodness.

There's also a handy link that if followed tells you how to contact Support.

-- *Slide* --

### Can you find the support email address?

Is it:

1. support@nectar.org.au
1. support@rc.nectar.org.au
1. help@nectar.org.au 
1. the_big_boss@nectar.org.au
1. support@amazon.com

-- *Slide End* --

**Answer: A**

The support site is well worth exploring. But we are not going to do it now.
Remember, you now know where to go when you want to find helpful documentation.

-- *Slide* --

### Can you find the NeCTAR training site?

Is it:

1. https://dashboard.rc.nectar.org.au
1. https://support.nectar.org.au
1. http://www.nectar.org.au/ 
1. http://training.nectar.org.au/
1. http://status.rc.nectar.org.au/

-- *Slide End* --

**Answer:**

Those are all useful NeCTAR website addresses to know. Especially the status site.
But the answer is D, http://training.nectar.org.au/

This is where you can go once you return to your homes, and look to increase your understanding of
the Research cloud, the home of your free computer and usb stick!

-- *Slide* --

## Close the support tab of the browser and return to the dashboard.

* <span style="color:red">&#9632;</span> = I've lost the dashboard!
* <span style="color:green">&#9632;</span> = I'm good to go!

-- *Slide End* --

Between the two drop downs NeCTAR have placed an item titled "Support Ticket". This is
where you should first turn if you need help.

-- *Slide* --

### Click on the "Support Ticket" link of the top bar of the dashboard.

* <span style="color:red">&#9632;</span> = I can't see it!
* <span style="color:green">&#9632;</span> = I've clicked!

-- *Slide End* --

The dialogue you've brought up allows you to directly submit a help request. 

But it has a search option on the right! 

This allows you to try to find the answer to your problem yourself before you reach out by completing the form.

-- *Slide* --

### Search the knowledge base for "allocation"

What does an approved allocation request become?

1. a tenancy
1. a project
1. a collaboration
1. an empire
1. a chore

-- *Slide End* --

**Answer: B**

Once you've done a search, if you still need help, just complete the fields in the dialog and 
submit your support request.

The one "gotcha" is the **default email address is the one shown in the dashboard settings drop down**. 

If you want responses to go to a different address, change it!

To close the dialogue without sending anything just click on the dashboard behind it.

**Activity:** Get people to close the dialog and return to the dashboard.

-- *Slide* --

### Can you all find the Allocations tab?

* <span style="color:red">&#9632;</span> = No...
* <span style="color:green">&#9632;</span> = Yes!

-- *Slide End* --

*Allocations* is an important tab: Remember, once you’ve exhausted your trial project, this is where you come. 
It’s basically an online form that allows you to apply for a project with enough resources to support your research.  

-- *Slide* --

### Is there an option to convert your trial project on the allocation form?

* <span style="color:red">&#9632;</span> = No!
* <span style="color:green">&#9632;</span> = Yes, I can see it.

-- *Slide End* --

Again, the greens have it.

You can also request to have your  project/tenant extended. 
You do this by selecting the "Convert project trial" option when filling in the allocation request form.


-- *Slide* --

# Homework...

http://tinyurl.com/ResBaz-Links

-- *Slide End* --

We've just introduced the Research Cloud. In order to make use of it effectively do work through the NeCTAR training.

The page referenced here gives links to the NeCTAR training material that covers what we've done today.

-- *Slide* --

You can think of the Dashboard we've just explored as the drivers seat for an entire Data Centre: <br />
The Research Cloud. <br />
BUT it is a car you can crash! <br />
And we *want* you to crash it and restart it regularly...<br />
Don't be afraid: **\#failfast**!

## Thank you

-- *Slide End* --
-- *Slide* --

# Roll up to the Research Cloud mystery tour!

your tour guide is ...

-- *Slide End* --

(First: Do a personal introduction. Who am I, and why am qualified to teach this course?)

-- *Slide* --

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

**Question:** Does anyone know what this is?

**Answer:** In 2001 a critical-care specialist at John Hopkins Hospital designed a checklist to prevent line 
infections. This is it!

So why are you being shown a line infection checklist on a session about the research cloud?

Well, the line infection steps have been known and taught for years. But frustratingly line infections still
happen. So the specialist gave this checklist to nurses and then asked them to observe the doctors for a 
month as they put lines into patients, and record how often they completed each step. 

In more than a third of patients, they skipped at least one of the steps.

The specialist then asked the nurses stop the doctors whenever a step was skipped.

The ten-day line-infection rate went from eleven per cent to zero. 

This story inspired a software company to introduce a checklist for deploying applications into production.

The rate of problems encountered during deployment fell to zero.

So with that in mind we've prepared some checklists for you use to launch your free PC's on the Research Cloud. 

    Now stop, and ask the audience to introduce themselves to the person on either side of them (if they don't
    know that person). Then let them know that these are the people that they will turn to first for help if they
    have any problems with the lesson. They are only to put up red cards if neither person on either side can't 
    help them. So if a read card goes up, you are expecting to see a row of red cards!

-- *Slide* --

## Launch your instance!

Use following checklist to launch an instance!

http://tinyurl.com/launch-pdf

-- *Slide End* --

Please hold up a Red sticky note if you need help
and a Green one once you are done.

-- *Slide* --

## Trial Projects

-- *Slide End* --

The first time you log on to the Research Cloud dashboard, you get given a **free** trial project, with three-months 
worth of time if you run the largest computer you are allowed to on it all the time. 

So you've just launched a platform to publish your kitten research to the world using your trial project.

A project is really just a way to group people together and to set constraints on what operations they can do on 
the Research Cloud.

If you only use your smallest computer for short periods of time, and **terminate** them religiously after 
each run, your trial project will last far longer. 

And when your trial project has expired, you can still log in to the dashboard to view and request 
allocations. You can even fill in an allocation request to extend your existing trial project.

Regardless of your path,  your trial project should give you the time to learn the Research Cloud ropes!

-- *Slide* --

## Question

What's your trial project lifetime?

1. for ever and ever after
1. three months from today
1. depends on how much I use it... 

-- *Slide End* --

**Answer: C**

So always **terminate** your free computers once you've finished working with them. That way you can avoid the
asking for allocation extensions paperwork.

-- *Slide* --

## Terminate your free computer!

Can you work out how to terminate your free computer? 
Test your discovery by terminating the one you've just started.

-- *Slide End* --

Please hold up a Red sticky note if you need help
and a Green one once you are done.

-- *Slide* --

## Why do you care about this?

-- *Slide End* --

Two researchers at a well known University, who and which shall remain nameless to protect the innocent, needed to 
do some fairly complex statistical analysis. So out of their grant money they bought two powerful computers, at a 
cost of $10 000 per machine to run[ MatLab](http://au.mathworks.com/products/matlab/?nocookie=true) on. 

But on the first run, they found that the machines couldn’t work with their data sets. The machines were underpowered! 
They were forced to iteratively spend money on upgrading those machines, until finally, one was able to perform the 
required analysis. It had taken them 12 months from the date of purchase to get to this point.

If, instead of purchasing hardware, they had turned to the cloud, they would have been able to have had their initial 
machine running within minutes. 

If it was underpowered, they would have been able to upgrade it to a larger machine, again within a matter of minutes. 
They probably wouldn’t even have had to re-install the software.  

The really good news for researchers is that everyone with an AAF login can experience this game changer for themselves, 
at no cost: through the national Research Cloud (NeCTAR) project.

If Research Cloud had been around with their current funding model in place when those two researchers were setting up 
their project that’s $20 000 of grant money that could have been used elsewhere!

-- *Slide* --

## Question

Currently, how much does it cost a researcher to use the Research Cloud?

1. Gazillions!
1. Squillions!
1. Billions!
1. Some unknown $$!
1. It’s currently free **at the point of service**

-- *Slide End* --

---

**Answer E**

---

There's another powerful reason to use the Research Cloud: access to storage which is kept locally in Australia and 
available on the high speed [AARNET](https://www.aarnet.edu.au/about-us) backbone. Think of it as a USB stick on
steroids!

And all of this is backed by a research facing organization that is not driven by profit.

But before you go rushing to the Research Cloud, there are some important gotchas that you have to understand. 
The cloud environment is a not quite the same as dedicated computer on your desktop! 

What I hope to do is to give you enough information to get your own machines up and running on the Research Cloud, 
and where to go to learn the gotcha’s.

## Security Groups

One of the things you needed to do in launching your free PC was to select a security group called 'http'.

Let's see if I can explain this in a bit more detail.

Network messages destined for a computer are broken up into packets. Once a packet reaches a computer how does the
computer know which application the packet is intended for? 

Well, the operating system allocates a different number to each running application. Then all network packets that
carry that number are sent to that application. This number is called a port number.

A security group is a firewall that allows all outgoing network packets to pass, but blocks all incoming network 
packets by default. But you can open "ports" in the security group, hence allowing inbound network packets with a 
matching port number through to the application on the instance.

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
    they are going to be allowed to reach your VM. 
    
    Any packets with a different port number don’t even make it to your machine. They are just thrown overboard!

Your trial project comes with several pre-configured security groups. But if you request a project via an allocation
you get no security group preconfigured for you. And what if you want to run an application that doesn't fit into
the predefined ranges? Simple. 

You just have to define your own. And so that's what you'll do now.

And for course we've created a checklist to guide you. This ones a little more formal.

-- *Slide* --

## Security Groups

Create a Security Group with the help of the security group checklist

http://tinyurl.com/creating-a-security-group

*Tip:* Preface the security group name with an "sg_" so that you know that
its a security group when you see the name...

-- *Slide End* --

Please hold up a Red sticky note if you need help
and a Green one once you are done.

**NB:** You can edit a security group at any time.  And the changes will immediately apply to all running virtual 
machines using that security group.

**NB:** This also means that if you share security groups amongst VM’s, you have to be careful: if you change rules for 
one server, you might inadvertently break another.

-- *Slide* --

## Question

I change the rules in a security group by removing port 80 (http). Mysteriously a web server on another VM in the 
project stops "working". Could it be because:

1. The security group was shared with the other machine?
1. The web server inexplicably broke?
1. The other machine itself failed?
1. NeCTAR are experiencing a network problem?
1. All of the above... ☹

-- *Slide End* --

Walk through each option, describing how it could affect the instance you are trying to reach.

**Answer: E.** Yes, it’s true. The research cloud can experience network issues from time to time. 

**NB:** Under some circumstances, you might find that you already have security groups defined for your project: or that
the default security group has ports/applications set up for it. So it is wise to review your projects security groups
and to understand what is provided.

-- *Slide* --

## Count of less than 30 security groups

Did anyone find out why this is in the checklist?

-- *Slide End* --

It's in the list because NeCTAR limit you to a maximum of 30. Which means that you have to share them around if
you have lots of instances!

-- *Slide* --

## HTTP vs HTTPS

Can anyone tell us about these two?

-- *Slide End* --

HTTP is Hypertext Transfer Protocol. All you need to know is that it is the way in which web pages are requested
from the server and transferred back to your computer. HTTPS simply appends "Secure" to the end of HTTP. It gives you
the guarantee that the communications between you and the server are encrypted. So HTTP means anyone between you and
the server can see what pages you are looking at, and their contents. HTTPS means that they only will know what site
you are visiting.

-- *Slide* --

## What is SSH?

Anyone? Please?

-- *Slide End* --

Secure Shell. We'll cover it in the next lesson. Patience!

-- *Slide* --

## And CIDR?

(And no, it's not a drink!)

-- *Slide End* --

Classless Internet Domain Routing, a snazzy way of specifying internet address ran

# Keypairs


"What's a key pair?" I hear you not ask.

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

On this tab you create key pairs. NeCTAR will keep one, the public key, and you will download the private key, the 
other half, to your local machine.

When NeCTAR fire up a machine for you, they inject the public key into your machine. Anyone with the private key will 
be able to communicate with and control that machine. Like the clay seals of yesteryear, you want to keep your private
key in a secure location. 

Now I'm going to generate the keypair that I'm going to use to access the instance to manage it.

**Q:** You fire up your machine. Days later, you realise that you’ve lost your private key. Will you ever be able to 
access and control your machine from that point onward?

Please hold up a Red sticky note if the answer is "No" 
and a Green one if the answer is "Yes".

**A:** No, the chances are extremely high that you've lost your machine for good.



https://www.youtube.com/watch?v=YEBfamv-_do
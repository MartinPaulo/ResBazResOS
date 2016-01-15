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

When your trial project has expired you can still log in to the dashboard to view and request 
a project allocation on the research cloud. You can even request to extend the duration of your
existing trial project.

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

But before you go rushing to the Research Cloud, you have to understand that the cloud
is a not quite the same as dedicated computer on your desktop! 

What we are going to do today is to give you enough information to get your own machines up and running on the 
Research Cloud, and importanly, where to go to learn the gotcha’s.

## Security Groups

One of the things you needed to do in launching your free PC was to select a security group called 'http'.

Let's see if I can explain this step in a bit more detail.

A security group is a set of rules used to create a firewall for your computer in the cloud. 

-- *Slide* --

## What's a firewall?

1. A wall used to prevent the spread of fire
1. An attractive wall made from fire
1. Something that blocks or allows network traffic
1. What's built on top of an ice foundation

-- *Slide End* --

**Answer A and C**

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

You just have to define your own. And so that's what you'll do now. You are going to create a single security group
that allows traffic to reach two applications.

And of course we've created a checklist to guide you. This ones a little more formal.

-- *Slide* --

## Security Groups

Create a Security Group with the help of the security group checklist

http://tinyurl.com/creating-a-security-group

*Tip:* Preface the security group name with an "sg_" so that you know that
its a security group when you see the name...

-- *Slide End* --

Please hold up a Red sticky note if you need help
and a Green one once you are done.

**NB** The same security group can be applied to many computers in your project.

**NB:** You can edit a security group at any time.  And the changes will immediately apply to all running virtual 
machines that have that security group applied.

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

Secure Shell. We'll cover it shortly. Patience!

-- *Slide* --

## And CIDR?

(And no, it's not a drink!)

-- *Slide End* --

Classless Internet Domain Routing, a snazzy way of specifying a range of internet addresses in one fell swoop.

## The Terminal 

-- *Slide* --

Your free PC on the cloud has no keyboard, monitor or mouse. Do you have any hope of installing or removing
software on it?

Hold up a Red sticky note if you say "No".
and a Green one if you think that, somehow, somewhere, there is hope for her.

-- *Slide End* --

**A** The Greens have it: there's always hope!

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

When NeCTAR fire up a machine for you, they inject the public key into your machine. 
Anyone with the private key will be able to communicate with and control that machine. 
Like the clay seals of yesteryear, you want to keep your private key in a secure location. 

And again, we've create a checklist to help you create a keypair.

-- *Slide* --

## Key Pairs

Create a Keypair with the help of the key pair checklist

http://tinyurl.com/creating-a-keypair

*Tip:* Preface the security group name with an "kp_" so that you know that
its part of a keypair when you see the name...

-- *Slide End* --

Please hold up a Red sticky note if you need help
and a Green one once you are done.

Ok: so now you have created a key pair and a security group. Let's use them to fire up a new free pc on the 
Research cloud:

-- *Slide* --

## Launch an instance

Use the launch an instance checklist to launch an instance.

http://tinyurl.com/starting-an-instance
 
-- *Slide End* --

Please hold up a Red sticky note if you need help
and a Green one once you are done.

-- *Slide* --

You fire up your machine. Days later, you realise that you’ve lost your private key. Will you ever be able to 
access and control your machine from that point onward?

Please hold up a Red sticky note if the answer is "No" 
and a Green one if the answer is "Yes".

-- *Slide End* --

**A:** No, the chances are extremely high that you've lost your machine for good.

- - -

SSH into the instance: should we see if we can use a web browser?

- - -


-- *Slide* --

# The object store

-- *Slide End* --

The *Object Store* is an ideal replacement for the usb sticks that some people tend to carry 
around with them: any file that you give it is backed up in at least triplicate. You can upload and download 
files from any browser: and you can share the files with the world.
 
On top of that, any file that you give it is backed up in triplicate, and each of the the copies is monitored for 
degradation.

Any bit rot, and the faulty file is replaced with a good copy. 

You can upload and download files via your browser: and you can share them with the world. 
Some people publish whole websites from the object store!

-- *Slide* --

## The object store

On the NeCTAR dashboard what's its child tab called?

1. Directories
1. Loading
1. Containers
1. Boxes 

-- *Slide End* --

Please hold up a Red sticky note if you need help finding it
Otherwise, hold up your answer...

**A:** C: Containers.

There is some terminology that you need to know.

Files are called objects. Unsurprisingly, since it's called the objectore.
 
And objects go into containers.

And this tab is where you create containers, and then put files (or objects) into the containers.

It is a very, very simple interface. So simple it's actualy clunky IMHO. 



>  (demonstrate making the container public, and viewing the image in a browser)

Now for a challenge.

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
▢ Create a container <br/>
▢ Upload a picture into it <br/>
▢ Can you make it public? <br/>
▢ Click on the resultant public link <br/>
▢ Append '/' and the object name to the browser address <br/>
▢ Do you see the image on your browser? <br/>
</div>

-- *Slide End* --

Please hold up a Red sticky note if you need help
and a Green one once you are done.

You now have a public handle that you can share with the world!

-- *Slide* --

## Settings drop down

-- *Slide End* --

The drop down on the right is the settings drop down. It’s not exactly the most intuitive of drop downs IMHO.

If you select it, you’ll see that there are three options: "Settings", "Help" and "Sign Out".

### The Help Menu

**Activity:** Get everyone to select "help" on the settings drop down.

**Q:** Are you all looking at the dashboard - or at something else?

**A:** Hold up a Red sticky note if you are still looking at the dashboard!
       
A new tab has opened, taking you to the homepage of the Research Cloud support site. 

The support site has loads of useful documentation. It has beginners guides, online training,
and knowledge bases.

Scroll down to see the quick links to all this goodness.

There's also a handy link that if followed tells you how to contact Support.

-- *Slide* --

## Question

Can you find the support email address?

Is it:

1. support@rc.nectar.org.au
1. help_me@rc.nectar.org.au
1. do_not_reply@rc.nectar.org.au 
1. the_big_boss@rc.nectar.org.au

-- *Slide End* --

**Answer: A**

The support site is well worth exploring. But we are not going to do it now.
Remember, you now know where to go when you want to find helpful documentation.

**Activity:** Close the support tab of the browser.

**A:** Hold up a Red sticky note if you are not looking at the dashboard!

Between the two drop downs NeCTAR have placed a new item titled "Support Ticket". This is
where you should go if you need help.

**Activity:** Get everyone to click on the "Support Ticket" link of the top bar of the dashboard.

This is an important link if you want to reach out and get help!

The dialogue brought up has a search option. This allows you to try to find the answer to your problem
yourself before you reach out by completing the form.

-- *Slide* --

## Question

Try searching the knowledge base for "allocation".

What does an approved allocation request become?

1. a tenancy
1. a project
1. a collaboration
1. an empire
1. a task

-- *Slide End* --

**Answer: B**

Once you've done a search, if you still need help, just complete the fields in the dialog and 
submit your support request.

The one "gotcha" is the **default email address is the one shown in the dashboard settings drop down**. 

If you want responses to go to a different address, change it!

To close the dialogue without sending anything just click on the dashboard behind it.

**Activity:** Get people to close the dialog and return to the dashboard.

-- *Slide* --

You can think of the Dashboard we've just explored as the cockpit/drivers seat for an entire Data Centre - <br /> 
BUT it is a car/plane you can crash!!! <br />
And we *want* you to crash it and restart it regularly...<br />
\#failfast!

-- *Slide End* --

https://www.youtube.com/watch?v=YEBfamv-_do
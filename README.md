# ResBaz'16 research cloud lesson

This course aims to give researchers an introduction to the NeCTAR cloud in a 90 minute session.

The material in it is drawn from the [ResBaz ResOS lessons](https://github.com/resbaz/nectar-cloud-lessons) 

## Motivator

It’s been hyped: but the Cloud does offer serious value in terms of cost and instant availability to researchers.
However, it’s a complex tool and if you don’t know and understand its constraints trying to make use of it can end
in painful tears. This course introduces you to the the tools and the underlying concepts of the NeCTAR cloud -
thus reducing your risk and saving you time and trouble in your journey to the cloud. And given the scale and low price 
of the research cloud you will, most likely, be making that journey.

## Git

If you check this repository out be aware that it uses Git submodules to manage the reveal.js dependency.
To also checkout reveal.js, you will have to either:

    # fetch it all in one hit
    git clone --recursive https://github.com/MartinPaulo/ResBazResOS.git

Or:

    # take it step by step
    git clone https://github.com/MartinPaulo/ResBazResOS.git
    git submodule init
    git submodule update

## Folders

The directories that make up this project are as follows:

* [Lessons](Lessons/) - The lesson(s);
* [Planning](Planning/lesson_plan.md) - The plan used to create the course;
* [Resources](Resources/) - Resources for this particular run of the training.

## Delivering the lessons

The lessons assume that participants have both red and green coloured sticky notes and cards lettered from "A" through
to "E" (in the style of Software Carpentry). These are used to answer questions and to show distress if the students
aren't keeping up or need help.

## Instructors notes

### In general

Each person being taught needs to be given 

* a red sticky note;
* a green sticky note;
* A set of answer cards, lettered 'A', 'B', 'C', 'D' and 'E' respectively.

The image used for the lessons is named `res_os_drupal7`. Check that it is still around and works
as expected before the lesson. If you need to rebuild it, there are instructions in the ResBas ResOS repository
[Resources/CreatingTheImageForTheWorkshop.md](https://github.com/resbaz/nectar-cloud-lessons/blob/master/Resources/CreatingTheImageForTheWorkshop.md).

### When giving the lessons:

Try to engage the audience. You can do this by asking questions of them. Or ask them to provide explanations of
what has just been done.

### Todo

#### Must do

1. [ ] Work through what the prerequisites are and how to deal with them.
1. [ ] Make sure all the required props are ready.
1. [ ] Add creative commons licence to Basic checklist.
1. [ ] Add "can copy and paste" to the post creation tab of the proper launch VM script

#### Nice to have

1. [ ] Can we have some sort of shell in place via DIT4C that will allow ssh without people having to install
       anything?
1. [ ] We should showcase Intersect's [Launchpod](https://launchpod.intersect.org.au/)? 

## Notes

    Tim: I haven't done anything yet, so why am I learning about allocations?

    Fiona: Can there be some more rationale - what is this going to let me do? 
    Refer back to the applications/ benefits more often
    Bernard: No rules appeared when I created a new security group
    
This seems to be rather random, and depends on the user. We need to dig further and find out what NeCTAR are doing here.

    Tim: I wasn't able to use my pt account to create a new instance because it had already exceeded its quota.

We are just going to have to get people like this to pair up with others: the only other way to handle this is
to create a special tenancy for the lesson, and then to add people like this to it...

Alternatives to CyWin

http://cmder.net/
http://mobaxterm.mobatek.net/
http://www.chiark.greenend.org.uk/~sgtatham/putty/

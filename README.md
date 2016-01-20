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
* [Resources](Resources/) - Resources for this particular run of the training. Note that some of the
  resources referenced are in the [ResBas ResOS repository](https://github.com/resbaz/nectar-cloud-lessons/)

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

### Prerequisites

* Each student will need a laptop with wifi access.
* The room must allow students to connect to the Internet via wifi. 
* Do we need to deal with Chromebooks? [Crosh](http://www.howtogeek.com/170648/10-commands-included-in-chrome-oss-hidden-crosh-shell/)
  Or [Chrome Shell](https://chrome.google.com/webstore/detail/secure-shell/pnhechapfaindjhompbnflcldabbghjo)
* Each student on the course must have an AAF logon.
* The Windows users will need to install [Babun](Resources/Babun.md) (5 minutes. Perhaps they can do this on the day?)
* Each person must have an allocation on the Research Cloud that they can use.

For those that have expired trial projects we can:

* get to pair up with others
* have a special tenancy for the lesson, and then them to it on the fly. 
  This is not a great solution as people in the tenancy will step on each others toes.
* have someone on hand to extend their trial tenancies on the spot?

If we could get participants AAF credentials before hand, we could:

* pre-create a special allocation for each person on the course that dies the day after the course.
* run a query to check if they are part of any project, and the status of their project.

## Notes

Fiona: "Can there be some more rationale - what is this going to let me do? Refer back to the applications/benefits
more often"

We could showcase Intersect's [Launchpod](https://launchpod.intersect.org.au/)? 

However I can't use it because of Intersect defect 
[INC0012566](https://intersect.service-now.com/ess/Incident+Information.do?sysparm_document_key=incident,f61198d06fc15600cb82c6168d3ee4c8)
(my aaf email is different to my NeCTAR user id). So if we do show it off someone else needs to do the work.

Should we use the paint video to explain keys? https://www.youtube.com/watch?v=YEBfamv-_do

### Todo

#### Must do

1. [ ] Work through the prerequisites and work out how to deal with them.







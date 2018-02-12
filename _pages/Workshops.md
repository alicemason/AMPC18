---
 layout: archive
 permalink: /_pages/Workshops/
 title: "Workshops"
 header:
   overlay_image: "/assets/images/water.jpg"
 author_profile: false  
---

On the 13th February we will host two pre-conference workshops.

## Workshop A: Professional Development Symposium (Morning)

Panel Discussion on Gender and STEM - St Catherine's college 10am-12noon

This career development workshop aims to promote gender equality and diversity in mathematical psychology. Follow this link to read more about the workshop and [register](http://www.ias.uwa.edu.au/masterclass/STEMresearch). 

Professor Amy Criss will be joined in a panel discussion by Associate Professor Amy Perfors (University of Melbourne) and Associate Professor Chris Donkin (UNSW). Discussion will be facilitated by Dr Alice Mason (UWA) who is chair of the Gender Diversity Committee in the School of Psychological Science.  This masterclass is open to attendees of any gender. 

Prof Criss is Head of Discipline (Psychology) at Syracuse, a world-leading expert in the computational modelling of human memory. Prof Criss has been [substantially involved](http://memolab.syr.edu/Pride.html) in efforts to enhance diversity in undergraduate students, and was President of the Society for Mathematical Psychology. Prof Criss involvement is supported by UWA's Institute of Advanced Studies.

If you have any questions please contact Alice Mason (alice.mason@uwa.edu.au).

## Public Lecture

Prof. Criss will also be giving a public lecture 6-7pm on the 13th entitled: “How remembering causes forgetting”.
You can find out more details and book a seat [here] (http://www.ias.uwa.edu.au/lectures/criss)

## Workshop B: Workshop on State-trace Analysis (Afternoon)

Presenters: John Dunn, Mike Kalish, Rachel Stephens

The aim of this workshop is to provide a brief introduction to the application of state-trace analysis (STA) to psychological data based on the book,

Dunn, J.C. & Kalish, M. L. (in press). *State-trace analysis*. Springer.

The following aspects will be covered (time permitting):

1.       Brief introduction to the logic of STA
2.       Fitting the monotonic model
3.       Analysis of continuous data
4.       Analysis of discrete data

Participants will use the custom STACMR software package developed by the authors. This will require that either Matlab or R be installed (both are supported), as well as java. Any version of java on or after version 1.7 is good. If java is not installed, it can be downloaded from [http://www.oracle.com/technetwork/java/javase/downloads/jre8-downloads-2133155.html](http://www.oracle.com/technetwork/java/javase/downloads/jre8-downloads-2133155.html).

In addition, participants should download the following files before the workshop:

* [State-trace analysis.pdf (a copy of the book)](/AMPC18/assets/statetrace/sta.pdf)
* [STACMR-matlab.zip (if using Matlab)](/AMPC18/assets/statetrace/STACMR-matlab.zip)
* [STACMR-R.zip (if using R)](/AMPC18/assets/statetrace/STACMR-R.zip)

Please note: You will need to install JRE (Java Runtime Environment). You can do this from (java.com). 

Windows:

There is a compatibility issue with R. Specifically, if your version of R is 32-bit then you need to install 32-bit JRE. Likewise, if your version of R is 64-bit you need to install 64-bit JRE.

To find which version of R you have, type version in R and look for w64 or w32 against "platform".

To locate the correct version of java, go to https://java.com/en/download/faq/java_win64bit.xml and follow the links.

Mac:

Go to the follow web page and do what it says – if you already have java installed, you can probably do fewer of them.  But do them all anyway.
(https://github.com/MTFA/CohortEx/wiki/Run-rJava-with-RStudio-under-OSX-10.10,-10.11-(El-Capitan)-or-10.12-(Sierra))

Then do this in R:
>> Sys.setenv(JAVA_HOME = '/Library/Java//Home') 
>> Sys.setenv(LD_LIBRARY_PATH = '$LD_LIBRARY_PATH:$JAVA_HOME/lib')

Now launch R-studio


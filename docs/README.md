# R-Workshop

[![Gather](https://img.shields.io/badge/gather.town-join-008900?style=flat&labelColor=black)](https://gather.town/app/RL6StuU0Rtlvtqp9/R-workshop)

### University of Basel

by Lisa Reiber

[lisallreiber.github.io/R-Workshop/](https://lisallreiber.github.io/R-Workshop/) \<-- The One True URL that links to everything!

:spiral_calendar: February 11 and 12, 2021   
:alarm_clock: 09:00 - 17:00 \| 09:00 - 13:00  
:hotel: Gather Town  

------------------------------------------------------------------------

## Pre-workshop Prep

TL;DR (friendly version below):
* Make sure you have a stable internet connection and a second display to work with
* install the following things (R\|RStudio\|Git\|RStudioCloud): Go [here](https://github.com/lisallreiber/R-Workshop/blob/master/00_prep.R) for details or [here](https://happygitwithr.com/workshops.html#pre-workshop-set-up) for help.
* There will be (a reminder to make sure you prepare) coffee 


11th February is coming closer, and I am excited to have you. The workshop will give you a hands-on version of a reproducible website that communicates data availability with tables and visualization (available [here](https://lisallreiber.github.io/GeneAnalysis/p1_0101_describe_plots.html)).  
However, we need you to make a few preparations so that we can start right away. Please make sure you have a stable internet connection and a second display to work with. It will make your life a lot easier if you can interact with us one one screen and work with R in another. Also make sure you install all the required pieces of software. We will be using RStudioCloud for the exercises during the workshop, but if something crashes or if you want to keep working with the things you learned in the workshop I would recommend installing the software prior to the workshop. To do so successfully requires some time and admin rights on your computer. If you're ready, go to and follow the steps: <https://github.com/lisallreiber/R-Workshop/blob/master/00_prep.R> If you get stuck, this website will probably [help](https://happygitwithr.com/workshops.html#pre-workshop-set-up).  
Please use your Github account to set up a free [RStudio Cloud](https://rstudio.cloud/plans/free) account as well. We will use RStudio Cloud for hand-on exercises during the workshop. It is a nice way to prevent us from spending hours on fixing bugs due to missing packages etc.

If you arrive early --- but please not before 8.30 am --- I can help with any technical problems that
you have encountered.


## Schedule

### Thursday

09:00 - 10:30 [1_1: Introduction / RStudio Workflows](day1_1)  
10:30 - 11:00 Break  
11:00 - 12:30 [1_2: R Markdown Intro](day1_2)  
12:30 - 13:30 Lunch  
13:30 - 15:00 [1_3: Meta-Viz with ggplot2](day1_3)  
15:00 - 15:30 Break  
15:30 - 17:00 [1_4: R Markdown: website features](day1_4)

### Friday
09:00 - 10:30 [2_1: Git + GithubPages](day2_1)  
10:30 - 11:00 Break  
11:00 - 12:30 [2_2: Putting all pieces together](day2_2)  
12:30 - 13:00 [2_3: Wrap-up](day2_3)  

## Overview  
This is a 1.5-day hands on workshop designed for beginner and experienced R and RStudio users who want to learn about working reproducibly in R. We'll work on project-oriented workflows, keeping text, code and outputs together (R Markdown), making data availability visualizations (ggplot2) and setting up a website to share all kinds of information (Git/GitHub).  
In terms of your R skills, expect to come away with new knowledge of how to write and code with R Markdown, a better grasp of some tidyverse functions and how to share your analyses directly from Rstudio to your reproducible website.

## Mission  
During the workshop we will visit the different building blocks from which reproducible websites like [this](https://lisallreiber.github.io/GeneAnalysis/p1_0101_describe_plots.html) are made of. If everything goes well, you will succeed in producing a website with visualization of meta information via your own Github account.

## Instructors  
-   Lisa Reiber \| GitHub [lisallreiber](https://github.com/lisallreiber) \| Twitter [lisa_reiber](https://twitter.com/lisa_reiber)


## Themes  
-   Project-oriented mentality, organization, predictability, portability
-   Visualizing and Sharing Meta Data
-   Using R Markdown to create a reproducible analysis and websites
-   Materials for getting unstuck and helping yourself
-   Further materials to dig deeper into the workshop topics in the future
 

## Feedback and communication  
<https://gather.town/app/RL6StuU0Rtlvtqp9/R-workshop> is our virtual meeting room at Gather.town. We will use the workshop area for all-group input sessions and the group-table areas for working in small groups. Don't worry if you are not familiar with Gather.town yet, we will explore it a together at the beginning of the workshop.

[Issues](https://github.com/lisallreiber/R-Workshop/issues) \<-- all are encouraged to open issues as we go. This is actually tremendously helpful to me! Examples of issue-worthy thoughts:

-   Glitches in the instructions or materials that I need to fix, for current workshop or future
-   Missing content that I point to
-   Great questions or sidebar discussions that I should consider formalizing and recording
-   Questions that are too specific or technical to answer in real-time

## Resources  
Here you can find a list of resources specifically to the topics we cover in the workshop. 


##### R & RStudio  
- [RStudio IDE Intro Video](https://rstudio.com/products/rstudio/?wvideo=520zbd3tij#rstudio-server)
- [Cute Introduction to R](https://rforcats.net/) (blog post ~ 7min)
- [WTF - What the forgot to teach you about R](https://rstats.wtf/) (bookdown site with lots of R-hacks)
- [Holy Tidyverse Manual: R4DS](https://r4ds.had.co.nz/)
- [Collection of RStudio Conference Talks](https://rstudio.com/resources/rstudioglobal-2021/)
- [Short Tutorials on different topics (RStudio Education)](https://rstudio.cloud/learn/primers)


##### R Markdown  
- [Reference Guide](https://rstudio.com/wp-content/uploads/2015/03/rmarkdown-reference.pdf)
- [Syntax Explorer](https://daringfireball.net/projects/markdown/dingus)
- [Inspiration: Gallery](https://rmarkdown.rstudio.com/gallery.html)
- [The Definite Guide](https://bookdown.org/yihui/rmarkdown/) (bookdown site)
- [Chunk Options](https://yihui.name/knitr/options/)
- [YAML Options Overview](https://zsmith27.github.io/rmarkdown_crash-course/lesson-4-yaml-headers.html)
- [Parameterized Reports](https://zsmith27.github.io/rmarkdown_crash-course/lesson-7-parameterized-reports.html)
- [Overview of all R Markdown formats](https://rmarkdown.rstudio.com/formats.html)
- [Rendering .R scripts with the rmarkdown package](https://rmarkdown.rstudio.com/articles_report_from_r_script.html)

##### Data Viz
- [TidyTuesday Live Coding from David Robinson](https://www.youtube.com/watch?v=WxKSauhOY4g)
- [Data-to-viz website with code templates for all kinds of visualizations](https://www.data-to-viz.com/)
- [Inspirational Data-Viz Blog by Cédric Scherer](https://www.cedricscherer.com/)


##### Git & Github  
- [Happy Git & Github for the useR](http://happygitwithr.com/) (bookdown site, hilarious)
- [List of Git Tutorials and Documentation](https://git-scm.com/doc/ext)
- [Git: The Simple Guide](https://rogerdudler.github.io/git-guide/index.html)
- [What is a fork?](https://docs.github.com/en/github/getting-started-with-github/fork-a-repo)
- [How to create a new repository?  ](https://docs.github.com/en/github/getting-started-with-github/create-a-repo)
- [How to create a GithubPages Website?](https://docs.github.com/en/github/working-with-github-pages/creating-a-github-pages-site)


##### Cheatsheets  
- [RStudio IDE](https://rstudio.com/wp-content/uploads/2016/01/rstudio-IDE-cheatsheet.pdf)
- [R-Markdown](https://raw.githubusercontent.com/rstudio/cheatsheets/master/rmarkdown-2.0.pdf)


##### Other  
- [How to get Icons for presentations](https://www.iconsdb.com)
- [Help me help you. Creating reproducible examples: Talk by Jenny Brian](https://rstudio.com/resources/webinars/help-me-help-you-creating-reproducible-examples/)
- [WORCS R Package for reproducible workflows](https://github.com/cjvanlissa/worcs)


## Links that are handy to us  
-   GitHub repo: <https://github.com/lisallreiber/R-Workshop>
-   GitHub Pages site, served from that repo: <https://lisallreiber.github.io/R-Workshop/>
-   Gather.town link: <https://gather.town/app/RL6StuU0Rtlvtqp9/R-workshop>

## Credits  
Some of the workshop materials are modifications of the following resources:

- [Kara Woo, Jenny Bryan, and Jim Hester's Rstudio::conf(2020) talk](https://github.com/rstudio-conf-2020/what-they-forgot)
- [RStudio Webinar](https://rstudio.com/resources/webinars/rstudio-cloud-in-the-classroom/)
- [Olivier Gimenez](https://oliviergimenez.github.io) [R Markdown Talk](https://oliviergimenez.github.io/intro_rmarkdown/)
- [Ulrik Lyngs](https://ulriklyngs.com) [R Markdown Workshops](https://ulyngs.github.io/rmarkdown-workshop-2019/slides/Day1.html)
- [Aaron Peikert's Repro Workshop](https://github.com/aaronpeikert?tab=repositories)



------------------------------------------------------------------------

![](https://i.creativecommons.org/l/by/4.0/88x31.png) This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).

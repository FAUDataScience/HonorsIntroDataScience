# Honors Intro Data Science & lab
This repository will host the syllabus and course materials for the Wilkes Honors College (WHC) *Intro to Data Science* course in Spring 2018, taught by Professors Kevin Lanning and Warren McGovern, and the lab *Intro to Data Science with R* taught by Dr. Lanning. (For the time being, it includes only a very rough course outline - a syllabus will come later).

## Who is this course for?
Hochster (in [Hicks & Irizarry, 2017](https://arxiv.org/ftp/arxiv/papers/1612/1612.07140.pdf)) describes two broad types of data scientists: Type A (Analysis) data scientists, whose skills are like those of an applied **statistician**, and Type B (Building) data scientists, whose skills lie in problem solving or coding, using the skills of the **computer scientist**.  Our course is like those at the universities of [North Carolina](https://idc9.github.io/stor390/), [British Columbia](https://github.com/STAT545-UBC/STAT545-UBC.github.io), [Maryland](http://www.hcbravo.org/IntroDataSci/calendar/), [Wisconsin](http://pages.stat.wisc.edu/~yandell/R_for_data_sciences/syllabus.html), [Stanford](https://github.com/dcl-2017-04/curriculum), [BYU](https://byuistats.github.io/M335/syllabus.html), [Harvard](http://datasciencelabs.github.io/), [Pennsylvania](https://github.com/MUSA-620-Spring-2017/Course-Materials), and [UC Berkeley](https://github.com/FAUDataScience/stat259) (and will likely draw from all of these) in that it is closer to a Type A than a Type B treatment, one which is closer to Statistics than to Computer Science. But there's more.

### Type C data science

Hochster's view of data science arguably omits a critical component of the field.  Data science is driven not just by statistics and computer science, but also by "domain expertise:"

<img src = "https://4.bp.blogspot.com/-0cbXveb1J_0/V-FtjJZ4rqI/AAAAAAAAMHM/bS32Pio2a1IFOyp5T86S0jiyB-3KAN1iwCEw/s1600/download%2B%25281%2529.png" width = "300px" />

The iconic [Venn diagram model of data science](https://www.google.com/search?q=venn+diagram+model+of+data+science&newwindow=1&safe=active&rlz=1C1CHBF_enUS762US763&tbm=isch&tbo=u&source=univ&sa=X&ved=0ahUKEwiM_abBtY7XAhXDQCYKHdgyB58QsAQIOg&biw=1378) suggests what we can call a "Type C data science." It begins with "domain expertise" in your **concentration** in the arts, humanities, social and/or natural sciences, it both informs and can be informed by new methods and tools of data analysis, and it includes such things as **communication** (including writing and the design and display of quantitative data), **collaboration** (making use of the tools of team science), and **citizenship** (serving the public good, overcoming the digital divide, furthering social justice, increasing public health, diminishing human suffering, and making the world a more beautiful place).  It's shaped, too, by an acute awareness of the **creepiness** of living increasingly in a measured, observed world.

**The WHC Intro to Data Science course will be a Type C course, or more accurately, a CAB course - equal parts statistics and domain knowledge, with just enough computing to be proficient to use (but not yet build) the software tools at our disposal.**  We aren't unique here - there are courses which integrate conall similar goals (which we may again draw from) at [Chicago](https://github.com/UC-MACSS/persp-analysis), [Georgia Tech](https://github.com/jacobeisenstein/gt-css-class), [UC Santa Barbara](https://github.com/raviolli77/dataScience-UCSBProjectGroup-Syllabus), [Princeton](http://www.princeton.edu/~mjs3/soc596_f2016/), [UC Berkeley](https://github.com/rochelleterman/PS239T), at [Berlin's Hertie School of Governance](https://github.com/HertieDataScience/SyllabusAndLectures), and in [Columbia's School of Journalism](https://github.com/tommeagher/data1-fall2015).

## What will be in the class?

**R**

In my rough survey of introductory data science courses, I saw a pretty even split between those which begin with Python and those which begin with the statistical programming language R. This difference corresponds, loosely, to the split noted above: Computer science based approaches to data science are frequently grounded in Python, while stats based approaches are generally grounded in R. Our course, like those for most of the syllabi and courses linked above, will be based in R.

**Reproducible science**

The course will provide an introduction to some of the methods and tools of reproducible science. We will consider the replication crisis in the natural and social sciences, and then consider three distinct approaches which serve as partial solutions to the crisis.  The first of these is training in a notebook-based approach to writing analyses, reports and projects (using R markdown). The second is using public repositories (such as the [Open Science Framework](https://osf.io/) and [GitHub](https://github.com/)) to provide snapshots of projects over time. Finally, the third is to consider the place of significance testing in the age of Big Data, and to provide training in the use of descriptive, exploratory techniques of data analysis.

**Good visualizations**

Part of Type C data science is communication, and this includes not just writing up results, but also designing data displays that incisively convey the key ideas or features in a flood of data. We'll examine and develop data visualizations such as plots, networks and text clouds. More advanced topics may include maps, interactive displays, and animations.

**~~All~~ *Some of* the data**

It's been [argued](https://www.udemy.com/datascience/learn/v4/t/lecture/3473822?start=379) that in the last dozen years, humans have produced more than 60 times as much information as existed in the entire previous history of humankind. (It sounds like hyperbole, but even if it's off by an order of magnitude it's still amazing).  There are plenty of data sources for us to examine, and we'll consider existing datasets from disciplines ranging from literature to economics to public health, with sizes ranging from a few dozen to millions of data points.  We will also clean and create new datasets.

**~~All~~ *Some of* the meaning**

Data matter, can save, enhance, or destroy human lives. (This is a crummy sentence: My pedantic insistence on treating the term "data" as plural rather than singular likely distracted you from the substance of my message. I'll leave it here as a reminder that we can all become better writers). Back to my point: In this class, we'll explore approaches to analyzing the meaning of data in areas including the analyses of simple texts and data journalism.

**~~All~~ *Some of* the skills**

The skills required to extract meaning from data include an understanding of classical statistical principles (e.g., probability theory and sampling theory), core statistical techniques (regression), and the extension of these core principles and basic techniques to problems in natural language processing, the analysis of social networks, and machine learning and classification.

**~~All~~ *Some of* the tools**

In addition to R, we'll use a range of other tools: We'll communicate on the Slack platform. We'll write using markdown editors such as [Typora](https://typora.io/). We'll certainly use spreadsheets such as Excel or Google Sheets. We *may* use additional tools for visualizing data such as Gephi and Tableau. 

**Hands-on computing**

We had initially anticipated that the lectures would include discussion, and that the computing part of the class would occur just in the lab.  But, in the course of examining syllabi at other schools, it became apparent to me that **there will be computing throughout the course**, not just in the lab.

**What will be in the lab?**

The labs will have two features.  First, they will allow for a project-based approach, focused on the collaborative analysis of problems of your own choosing. Second, these projects will include a deeper dive into some of the topics and problems above.  Here are a few examples of how the treatment in the lecture and the lab are likely to differ:

|                  Topic                   |                 Lecture                  |             Lab: Deeper dive             |
| :--------------------------------------: | :--------------------------------------: | :--------------------------------------: |
|               Introduction               | Stephens-Davidowitz book; Google trends  | Examining one or more scholarly papers in data journalism |
|               Getting data               |               Extant data                |    Using APIs to scrape social media     |
| Exploratory data analysis / Data visualization |           Static data displays           | Interactive plots (r Shiny), animated  displays?, Tableau? |
|             Sampling theory              |        Test vs training datasets         |         k-fold cross-validation          |
|      Regression and classification       |       Supervised machine learning        | Robust techniques / regularized regression  Unsupervised prediction;  comparison  of different approaches (Random Forests, bagging, …) |
|    Graph theory and network analysis     | Introduction to centrality, community structure, contagion | Network robustness, different approaches to centrality & community structure |
|             Analyzing texts              |               Word clouds                |        Natural language analysis         |

### So should you sign up for the class?

I think that this course will have something for every Wilkes Honors College student. The WHC was built and funded by the state of Florida to train tomorrow's leaders. That's you. The skills and perspective that you will gain in this course will help you in graduate and professional schools, will help you in your careers, and will help you in your goal of making a better world. And it will help you train the next generation of data scientists, too.

**Should you take the lab as well as the lecture?**

Yes. But it (the lab) is not required, not a formal corequisite.

**How do I sign up?**

If you are interested in taking the class (either with or without the lab), complete the Google form [here](https://goo.gl/forms/kXGAOTShcOLPwjPH2). Note that enrollment in the class and lab will be limited to 30.

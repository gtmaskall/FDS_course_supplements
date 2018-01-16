# Getting started

Here I'll try to provide resources under section headings that relate
to the Springboard curriculum units. Not all curriculum units will have
sections here. For example, "Getting started with the workshop" is
rather specific to Springboard. However, I can add some general
"getting started" resources. Much of these come from JHU's excellent
data science specialization course on Coursera.

## Introductions

The Springboard curriculum has an emphasis on introducing data science.
Here I'll add a couple of resources that introduce some data science
tools and advice on getting started studying.

[The data scientist's toolbox](
https://www.coursera.org/learn/data-scientists-tools/lecture/4mR4L/the-data-scientists-toolbox)
is a 5 minute video that introduces RStudio, .R files, and .Rmd files.
Pause it on slide 2! Read the bulleted list. Then read it again. When you've finished
reading it for the twentieth time, write it out. Return to this list periodically as
you work on your capstone project. Have you started to answer the question? Are you
progressing through the list? Don't feel you can't move on to the next step if
there's work left to do, but equally if you find yourself getting too far ahead of
unfinished business then you probably want to go back and revisit previous steps;
is your question still appropriate, do you still expect your data to be able to
yield an answer, do you need to do more data cleaning or exploratory data analysis?

And just to remind you, here is JHU's aforementioned list for:

### What do data scientists do?

* Define the question
* Define the ideal data set
* Determine what data you can access
* Obtain the data
* Clean the data
* Exploratory data analysis
* Statistical prediction/modeling
* Interpret results
* Challenge results
* Synthesize/write up results
* Create reproducible code
* Distribute results to other people

Can you see how the list maps across to the Springboard curriculum?
Notice how we get you thinking about your **capstone project** right at the start.
Then the curriculum teaches you about **cleaning data**. You should be fairly happy
your data is not obviously broken in certain ways at this point! Then you can
proceed to doing some **exploratory data analysis**. Can you see any interesting trends?
Any informative histograms of continuous variables? Bar charts of discrete ones?
Tables? Any useful summary statistics such
as an average? At the end of this stage, you should have some firm things you want to
test or confirm and a solid grasp of the exact project question you intend to nail.
So then we cover some **probability and statistics**. Note, whether your project interest
is a predictive one or a statistical inference one, you may well want to skip ahead
to the start of unit 7, "**An introduction to machine learning**", which covers linear and
logistic regression. You can use a linear model either for prediction or for inference!
By now you should feel ready to tell your **data story** and you're close to being able to
complete. But we haven't finished the above list yet! Don't forget the important last
steps of interpreting and challenging your results. What do the coefficients or p-values
etc tell you? Was it what you expected? Does it makes sense? Then you bring this all
together into your report along with your reproducible code in your repository and
distribute it!

[Getting help](https://www.coursera.org/learn/data-scientists-tools/lecture/KPkZz/getting-help)
is an 8 minute video with much sound advice that maps well to the Springboard course.
And don't forget the [Springboard community](https://foundationsdscommunity.springboard.com/)!
Hint: if posting an R question to the community, have you watched the above video,
particularly slide 11? ;-)

[Finding answers](https://www.coursera.org/learn/data-scientists-tools/lecture/6zxii/finding-answers)
is a 4 minute video that follow on from the previous one and also contains very good advice.
It's interesting to note how the names used to refer to data science can vary with application area.
It's very telling that a great course on data science is taught by people calling themselves
biostatisticians! You may already know that R tends to be the popular data science language
in the biological sciences and statistics.

## Start thinking about your capstone project

I'd already put together some guidance on finding your capstone project
[here](https://github.com/gtmaskall/Springboard_FDS_project_datasets)
and I hope it's useful. By all means use some of the specific datasets
listed there, but primarily I hope it gives you an idea of the sort
of characteristics to look for in your capstone project dataset.

If you already have a topic in mind, do you have the data? The question?
Students often start from a blank slate. Usually, you would start with
the question. Typically your boss or your client will want to know
something they didn't before. But in this context it can be tough to get
started. Have a look around at some datasets. Does that spark any curiosity
in you and generate any questions? It's okay if your questions aren't
appropriate to the data you just found. Can you find some data more appropriate?
This can give you a more targeted search.

## Programming in R

There are many resources available for learning R.

Probably the best advice I can give is to draw your attention to the following
steps:

1. Installing and getting started with RStudio
2. Installing and getting started with Git and Github
3. Getting started with R Markdown.

I heartily recommend you pause at this point and do not proceed any further until
you've got yourself established with these steps. Having these steps ticked off and
being comfortable with them will simplify both yours and your mentor's lives
considerably in the future, and will be valuable tools for your own future if you've
got a solid grasp of them.

Of the three, installing and getting started with RStudio is probably the easiest;
visit the [RStudio website](https://www.rstudio.com/) and click on the Download link
for RStudio and do the relevant stuff for your platform and follow the usual prompts
etc etc and you'll have RStudio up and running. NB I deliberately used a link to the
main RStudio page in the hope you notice the Shiny and R Packages sections. Remember them,
bookmark this page, and return to it in the future. Great stuff here!

The third step, getting started with R Markdown is probably the most neglected of the steps.
What is this R Markdown thing anyway? I'll come back to this. For now, step two,
installing and getting started with Git and Github has to be unarguably the biggest and
most common sticking point for students.

## Getting set up

### Introduction

I would say this section is a crucial one that is well worth paying very close attention to.
This section does not readily appear in the Springboard curriculum as such and, I
think consequently, can be where some students get stuck. You see here we transition
from getting some exposure to the R language to starting to get our hands dirty doing
stuff with data. But if you haven't got all your tools set up at this point you can
find yourself with an exercise to submit on github and then something related to your
project to submit and you're unsure quite what to do with the now embarrassingly chaotic
mix of exercise files and capstone project files all in the same directory that doesn't
want to talk to github and what *is* this stupid github thing anyway?

Firstly, a strong recommendation. Good practice really. You know what a directory is on
your computer. Keep analyses in logically distinct directories. This is basic organizational
skill. By all means lump your exercises in a single one (call it "exercises" or something);
that seems logical. But definitely keep a separate directory for your capstone project. You'll
thank yourself for this when you're trying to marshall your project scripts together without
tripping over unrelated exercise files. Your mentor will thank you as well when they
come to review your project work and don't have to disentangle it from old scripts.

### Git

To recap, by this point I expect that broadly you've completed unit 1 for an introduction to
data science and the workshop, and unit 2 for an introduction to programming in R. You'll also
have downloaded and installed RStudio, whether you took my hint to do this earlier so you can
play along with the videos or you've only just done it. Either way, now is the time to get
some version control set up. *I strongly recommend you do not proceed much further in the
curriculum before doing this*.

[Introduction to Git](
https://www.coursera.org/learn/data-scientists-tools/lecture/qmyW6/introduction-to-git)
is a 5 minute video that covers downloading and installing Git and getting started.

### GitHub

You've now installed Git and you know you use it to track changes to files on your computer.
You know you tell Git you want to track a file (git add) and go ahead and remember/log that
version (git commit).
Cool. Well GitHub is just a place on the Internet where your stuff in Git can be shared. 
Conceptually, all the work is done with Git. It's "Git in the Cloud".
GitHub is just a website. The *only* really new concepts for you at this point
are linking your local git repository to one on GitHub and, then, pushing/pulling
changes from/to your local git repository to/from that linked repository on GitHub.

[Introduction to GitHub](
https://www.coursera.org/learn/data-scientists-tools/lecture/SqWSK/introduction-to-github)
is a 4 minute video that gives you an overview of GitHub. 

[Creating a GitHub repository](
https://www.coursera.org/learn/data-scientists-tools/lecture/TBct9/creating-a-github-repository)
is a 5 minute video on probably the hardest topic for a newbie: creating a repository. 
The recap on slide 2 of the distinction between Git and GitHub is nice as this can be a
genuine cause of confusion. It talks about creating a repo from scratch and forking an
existing one. I like that they start by creating a repo on GitHub and then create a local
copy of it on your computer. This is quite a smooth way of doing it to end up with a Git
repo on your computer that is linked to the relevant repo on GitHub.

At this point you should be just about ready to set yourself up. If you only have an
R project directory (no Git initialised), you can follow the steps of creating the GitHub
repo and then running the `git init` followed by the `git remote add` in your R project directory.
RStudio should then know this project is version controlled using Git and give you a new
Git pane for adding and committing changes. If you're totally starting a new project from
scratch and don't have any files at all yet, you can even start by creating a GitHub repository,
then going to RStudio and selecting the menu option to create a new project from version
control. You'll be prompted to give it a URL (the same as you'd use in the `git remote add`
command above), a project name, and a location on your computer. Once done, you'll have a new
RStudio project that is all ready and set up with Git and GitHub. All you need to do is create
files, add them to Git, commit and push!

[Basic Git Commands](
https://www.coursera.org/learn/data-scientists-tools/lecture/BTILd/basic-git-commands)
is very useful 5 minute video. It starts on slide 2 with a schematic of Git workflow.
Don't be daunted by this! It's a useful summary of how your workspace relates to all
these various stages in Git and GitHub. I will say not to worry about branches just now
though.

[Basic Markdown](
https://www.coursera.org/learn/data-scientists-tools/lecture/rMJyQ/basic-markdown)
is a short 2 minute video on markdown. Yes markdown, not R markdown. I very much 
recommend you make use of markdown (.md) files. They're a great way to easily create
formatted documents. Just like this one! You can think of R markdown files as extensions
that also allow you to include R code and its output. 

## Making use of it all

Okay. You're now ready to start putting this to good use. In this optional exercise you're
going to fork a GitHub repository and edit it to tell us a little about yourself.
The template repo I've started can be found
[here](https://github.com/gtmaskall/Springboard_introduction).
You should now be able to fork this repository to make your own copy on GitHub. You can either
edit on GitHub, or take a local copy on your computer. Edit it to make it your own; the sections
and contents are just suggestions to get you thinking. This is all "bonus material", but with the
serious purpose of giving you a great start being up and running with Git and GitHub.


#R Web Tutorials (UCLA)

Here is a sketch of what we are going to do with http://www.ats.ucla.edu/stat/r/

##Infrastructure

All source code of the website (currently for R only) is going to be maintained on GitHub; all files are written in markdown instead of raw HTML since markdown is way way easier to write.

We use the knitr package to compile the source code to output dynamically. The output is still markdown but the R source has been evaluated. We convert the markdown output files to HTML by pandoc. The final output can be actually pretty flexible, see https://github.com/yihui/knitr-book for example.

##What do we do

###Redesign the theme

First we try to come up with a better HTML/CSS theme hopefully with the help of http://twitter.github.com/bootstrap/ or http://bootswatch.com/

###Revise code

Occasionally we need to update R code in the site, e.g. source("c:/stat/intro_function.txt", echo=T) in http://www.ats.ucla.edu/stat/r/library/intro_function.htm is bad; should be source("http://www.ats.ucla.edu/stat/r/library/intro_function.txt", echo=TRUE)

##Additional stuff

Run the website better:

* Google Analytics; we must know the exact statistics behind the traffic
* social buttons like Twitter/Google+/Facebook...

##Revenue

Being free is good, but if there are chances to make it even better, why not use them?

* due to the heavy traffic, we strongly recommend a small amount of Google ads in the pages, so that this website can run on its own; it is not necessarily a bad thing to make money in this case

##The team

We have volunteers from http://cos.name.

- @Gwill
- @lixiaomao
- @luyinbo
- @yihui

I will be the coordinator and give instructions when necessary.

##Schedule

We do not start building the website immediately; we ask the volunteers to practice first. We do tasks in units of months.

###Preparing web knowledge

1. learn HTML; it is simple because there are only a limited number of tags; you must be able to write HTML pages on your own;

2. learn CSS; know how to control the appearance of HTML elements via style definitions (use Google Chrome to learn it);

3. learn markdown; it is even simpler, but you do not need to remember the syntax at the moment;

###Build your own website

You have to try your own dog food before you make it for others, so build your own website first.

1. register on github; know how to set up GIT

2. learn how Jekyll works and start simple blogging with markdown files

3. design your own style (CSS)

###Learn knitr

1. learn how knitr works with markdown files

###Redesign the R tutorial website

1. pull down a single page, and design CSS

2. set up the workflow about how to work with multiple pages in a batch job with knitr

###Labor work

Convert existing HTML pages to markdown... and we are done.

##Goals

We help because we think this website is useful and we want to give something back. Besides that, we have other goals:

1. volunteers are primarily Chinese (grads or undergrads), so it is good chance to practice English;

2. know more about R and statistics;

3. learn modern web techniques and master tools for reproducible research, which will benefit a lot in the future in terms of writing statistical reports;
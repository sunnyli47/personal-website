---
title: How to Create a Website
author: Sunny Li
date: '2020-03-30'
slug: how-to-create-a-website
categories:
  - Tech
  - Experiences
tags:
  - Hugo
description: My web journey with Blogdown, Hugo and Github
image: "how-to-create-a-website-bg.jpeg"
math: ~
license: ~
hidden: no
comments: yes
---

***The complete title for this blog is "How to Create a Website Using Blogdown, Hugo and Github as a Beginner"***

**-- Please scroll to the bottom to see the update~ --**

After indirectly discovering [Yihui's website](https://yihui.org/), ("indirectly" as it was first discovered by my mom), I’ve decided to create one myself. Then, having been working ~~tirelessly~~ for about several days, and going through tons of mental breakdowns 

> "why is it still not working?!?!” “why is this page not coming up???” “why...why...why…?”

and self-doubts (“can I even do this?” “Am I even capable of doing it?”), I finally launched my first website on March 27th, 2020! 

### Random Thoughts

It might be a piece of cake for others but it was a crazy journey for me. As someone who had ZERO experience on R/HTML, I felt like I’ve stumbled on a completely new and appealing world that’s hidden under the layer of our world. Scrolling through different web pages have long been integrated into my life but I had no clue how it is actually working. With that little confidence from a tiny bit of cs knowledge I gained from college, with the grit gained from all the previous dreadful but rewarding cs projects, and with the pure curiosity to a whole new world~, I decided to give it a try. And I did it! which I am so proud of myself.

### Actual Useful Content

Many people would most likely first start off by reading the official guide [Creating Websites with R Markdown](https://bookdown.org/yihui/blogdown/) by Yihui Xie. However, for those complete newbies like me, I would personally recommend searching for other more detailed and step-to-step tutorials online as the official guide assumes some prior basic knowledge that readers possess but I didn’t at that time (i.e. what is a repository on github). The tutorial I ended up eventually using, [Amber Thomas’s tutorial](https://amber.rbind.io/2016/12/19/website/), provides a lot of helpful essential background info that I needed on Github, Hugo and Blogdown. It is also beginner friendly in terms of its step-by-step instruction, which I found is easy to follow and understand. However, I was still stuck on a few steps and spent a large amount of time to debug. Thus, here are some quick notes that I think might be helpful to you and make the whole building process smoother and quicker:

- Under the section “Initializing GitHub pages to work with Hugo and Blogdown”, before the step 5
> Your default branch is now ‘sources’. In your command line interface (terminal or git bash) navigate to your github working directory (for me, it’s
animoplex.github.io), and type `git checkout sources`.

You have to update the local depository by calling the command `git fetch`. Otherwise the terminal would give an error message about the command `git checkout sources`.

- If your website is working improperly after being deployed on Netlify, it might be because you didn’t set your Hugo version in the setting of Netlify. Netlify’s default hugo version is much older and might not work properly.

- Not sure if this is necessary, but in two .sh files, I also changed `Source = hugo` to `Source = sources`.

### Another Method

After I finished launching my website, I checked out Yihui's book again and found many of the concepts make more sense to me as now I have a little better understanding of R studio and HTML. It also proves my previous point that this book is well-suited for a more advanced level. In addition, Yihui did talk about a better approach to update the web page. I haven't had time to look into that yet but I'll update the progress as soon as I tried it.

Good luck on building a world of your own XD

**OCT,2020 EDIT:** hello ~ it's Sunny from the present, OCT 13th, 2020. I am not sure what "another method" I was exactly talking about back in March but I did find a much easier way to create a website! In fact, this method was so easy and effortless that I was mad about myself "wasting"" all those time I spent on it. (hey, at least you got kinda familiar with linux and vim!) However, it is still AWESOME to know because it is completely beginner friendly! I can finally recommend this to my other friends who are worried about typing all those dauting command lines on terminal ;)) 

Anyway, what I did this time was to let RStudio handle all the add, commit, push jobs (a.k.a version control) that I previously have done in terminal. And no, this is not a new feature and I am pretty sure it exists when I created my first website back in March. I do not know how I somehow missed it.

Here is a [Alison Hill's tutorial](https://alison.rbind.io/post/2017-06-12-up-and-running-with-blogdown/#caveats-disclaimers-etc.) that I found being extremely helpful.



---
layout: post
title:  "Another year over"
author: Matt Rooney
date:   2018-12-19 17:21:20 +0000
categories: WIP
---

Hello there. I haven't seen you in a while! 

Maybe that's because I haven't been posting very frequently. My cadence of three posts per year needs improving. 
I had a look over the goals that I had set for this year and best believe I absolutely did not complete them. So rather than 
go through each one and give excuses as to why I didn't, I'll talk about what happened this year and maybe it will be apparent as to 
why I didn't complete any of them (my girlfriend just said it's because I'm lazy - what does she know!).

### I just want to help

The start of 2018 is quite fuzzy, nothing really stands out. I created this github pages site and had great plans to add many articles
and show how knowledgeable I am but alas, it didn't happen. Early in the year I spent some time understanding the swift core library.
I downloaded the foundation library and my first impression was "Wow so many unit tests". It made me realise how important unit tests 
are when you have millions of people directly and indirectly using your software. I then went off to fix the world and look for my first Jira ticket. 
I found this [one](https://bugs.swift.org/browse/SR-6530?focusedCommentId=32076&page=com.atlassian.jira.plugin.system.issuetabpanels:comment-tabpanel#comment-32076). 
I tried to reproduce it and... I couldn't, so I made a comment to say that and off I went expecting it to be closed and the whole of apple would sing my praises because
I saved them time and money. 

Instead I was told 
> You are likely using the bridged Foundation and not the swift-corelibs-foundation.

At this point I thought, it's a saturday, what the hell am I doing. So I closed my laptop and did something outside instead. Which in retrospect is a an important thing
to realise. You need to enjoy your life and you can't always be working.

### New job, who dis?

I had been looking for a new job in the latter part of 2017 but hadn't been able to land one. So I began to look around again moving into easter of 2018.
A colleague of mine messaged me about a role in Deloitte Digital. He told me about different projects coming down the line which required iOS developers which is 
where I wanted to focus. I took the opportunity in April and here I am. It wasn't all plain sailing though. My first project was not an iOS role. It was spring/Java
and frontend work. I also had to use a windows machine :mask:. Although perspective is very important and if you think your situation is bad then it will be.
Instead I decided to think of all the positives. I learned a lot about frontend development. Initially I had to make changes to a code base which had no framework or
conventions. Every javascript file looked different in terms of structure. It was as if 5 developers put their headphones on and started working on different parts of the site with no PRs, code reviews or gifs for communication.
Then I got to work on a react app with another developer and that my friends was like heaven. Conventions everywhere. Even though react was fun, I was still getting ansi with using a windows machine
and having to deal with things like no ssh access to servers. I like to automate things and not being able to access the servers meant I couldn't do much in terms of CI/CD.

### London, here I come

So after four months of javascript, I finally got the calling for an iOS role in London. This meant that I needed to travel each week, flying out Monday morning and
back Thursday evening. It was actually not that bad. I'm not far from Dublin airport and the flight takes about an hour or so. It could have been worse. The project in 
London is extremely exciting. It's a green field project where we are building everything from scratch using the latest tech all on google cloud.
We are using flow to organise our work which means walls covered in post-it notes. I'm working with other iOS devs who are pure iOS and are experts in their field which
I am really grateful for, they have thought me a lot!

### Maybe I did complete a goal

During the summer, I started working on a side [project](https://makeu.app/) with a colleague. It's a social media app called [make.u](https://itunes.apple.com/ie/app/make-u/id1441179129?mt=8). 
It's for people interested in makeup and beauty (it was my colleague's wife's idea :stuck_out_tongue_closed_eyes:). We built the app in react native and the backend in grails. 
I've always been an iOS native guy but it was fun to try out a cross platform library and see if its comparable to native. I'm not convinced. I still prefer native. It also gave me experience with AWS. 
I setup our infrastructure including EC2 instances, MYSQL instances, S3 buckets and route 53 DNS configuration. We're still working on getting more users which means
we have to build our content and do more marketing. I've started using apple's search ads to bring in users and that has helped but we're struggling to increase retention.

### Looking forward

After christmas I'll be travelling back to London which I 'm looking forward to. I really like the project and hope to make a bigger impact outside of my iOS work.
I've started studying for a google cloud architect certificate and since we are using GCP on the project, hopefully I can get involved and gain some more
hands on experience. 

So what are my goals for this year? I still think that I need to improve my public speaking especially for 2020 since I have a best man speech to do then.
I believe joining Deloitte will help me to improve my public speaking since it's an essential skill to have within tech consulting. As for
open source...I'm not sure...I have some ideas around server side swift on GCP so maybe that will spawn some proposals to swift lang.
In any case I'll do my utmost to be the best 'me' I can be in 2019.

Until next time! Slan!
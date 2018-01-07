---
layout: post
title:  "Get Schwifty"
author: Matt Rooney
date:   2018-01-06 21:20:51 +0000
categories: iOS
---

At Infocare we have started using swift 4 in our iOS application Soteria. We felt that swift is stable enough for us to start using and so far it has been amazing. 

I have been programming in objective-c since I joined Infocare nearly four years ago and it is so refreshing to use such a modern and convenient language that is swift.

Our product is entirely written in objective-c and at first it was scary, taking the chance of using swift for our new Medication List feature. We wondered would swift and objective-c play nicely together, would switching to swift cause delays in our development. We swiftly found out (pun intended) after some research and development that apple have made it incredibly easy to work with both languages using bridging headers. There are also some great resources to learn swift from apple's own documentation and the usual Ray Wenderlich articles. The best way I have found to pick up the language is to just open up a playground in Xcode and start trying things out.

Not only is swift a great language to program in because of it's simple syntax and excellent standard library (especially functional methods on collections e.g. map, reduce, filter) but at it's core it is inherently safe. This is of paramount concern for us working in the healthcare industry. We must ensure that our application does not crash at critical times. Optionals are a great language feature which allows for compile time null checking and helps developers to write safe code.

I suggest to any mobile devs who might be indecisive in taking the jump into swift to not say "ah lets just do it in objective-c" but instead, get schwifty...ASAP! You won't regret it! Take a new feature as a trial and write it in swift. You don't have to rewrite your whole application and this way you can ease into the language.

I'm looking forward to writing more features in swift and forgetting about objective-c's infinite square brackets, dated semi-colons and header files...although I may miss them from time to time :).
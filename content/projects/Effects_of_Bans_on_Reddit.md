---
title: "Effects of Banning Content on the Structure of Online Hate Communities"
date: 2018-05-19T23:25:35-04:00
draft: true
---

## Does banning stuff work?

Even though the internet is renowned for being a cesspool of hate, a lot of media platforms (Facebook, Twitter, Reddit, Discord) have been cracking down on this kind of content by banning people or communities associated with certain movements. But there's one big unanswered question: Is it working?

In some cases, these communities backlash and have a hydra-like effect: cut off one hand and two more spring up in its place. When Reddit banned r/FatPeopleHate in mid-2015, a number of new subreddits dedicated to the content appeared, and users of the subreddit also reportedly spilled the content into other subreddits. [Other specific examples here]. From the perspective of social systems, this is interesting because it shows that a lot of dynamics are at play. If people are motivated enough to backlash this way, do they just let go of their desire for this content? Where do they go? 

There's very little formal research about the effects of administrative action on social media, or about their effects on online social networks. A previous (and popular) study found that there was less hatespeech across Reddit after a hate subreddit was banned. It's not clear from that study how the banning translated to the social dynamics that resulted in the backlash seen by reporters and bystanders. 

## Networks of Communities

I wanted to study the community dynamics using network science as part of a class project on Network Science. I looked at the case when Reddit banned r/altright which was banned in early 2017 for allegedly breaking Reddit's terms of service by spreading personal information about people. 

Reddit data is publicly available on pushshift.io, a repository collected live. We took the posts from users who posted in r/altright in the months before r/altright was banned, and we looked at the effect of the ban on the community. 

We created networks of users that interacted with each other on reddit. After the ban, there were around 30% <strong>fewer</strong> people in the network.

A lot of the structures in the network stayed the same, but a lot more people changed than expected. 
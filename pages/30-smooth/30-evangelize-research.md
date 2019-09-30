---
layout: content
title: Evangelize Breakthrough Research on Coding UX
image: tiered-landscape-cool-1292416-pxh.jpg
# image: cool-tunnel-147085-pxh.jpg
---
The following are [some examples](https://www.youtube.com/watch?v=mkzHIhKaUX4) of what researchers in University of Washington's [Code & Cognition Lab](https://medium.com/bits-and-behavior) have cooked up to make coding more accessible to all: 

- __Learning by Solving Debugging Puzzles__. [Mike Lee](https://informatics.njit.edu/faculty/mjlee) created [Gidget](https://www.helpgidget.org/), an interactive tutor for learning the programming language Python by solving debugging puzzles. In a study of 1,000 adult learners, he found that
  -  People who used Gidget picked up Python twice as fast as a well-regarded online Python tutorial and learned twice as much Python as participants who learned by doing.
  - Gidget "changed attitudes about the difficulty of learning to code from negative to positive in 20 minutes" -- an incredibly important finding for efforts to make coding accessible.
- __Learning by Tracing on Paper__. [Benji Xie](http://benjixie.com/) believed learners often have a "brittle" knowledge of a programming language's semantics, so they just guess what will happen when their program runs -- a surefire strategy for producing frustration and failure.  He developed an innovative strategy that involves students figuring out on paper how their program will execute.  His study showed that with less than 15 minutes of training in this technique, students did 15% better on computer class lab problems and 7% better on midterms -- and no one who used the strategy failed the midterm, in contrast to 25% of the control group. 
- __Speed Up Learning JavaScript__. [Greg Nelson](http://www.greglnelson.info/) created [PLTutor](http://pythontutor.com/), an online interactive textbook designed to cover all of the basics of standard JavaScript in 3 hours. For each core idea in JavaScript, PLTutor explains why & when you'd want to use that idea, then lets you step through code using the idea so you can see how the code executes and what impact it has. His study demonstrated that compared to a well-regarded online class, participants who used PLTutor had 60% higher learning gains.

The Code and Cognition Lab has even more dazzling work in the pipeline. In a [2018 talk](https://www.youtube.com/watch?v=mkzHIhKaUX4), Professor [Amy Ko](http://faculty.washington.edu/ajko/) says they are now working on a project to create a scalable online tutor that “provides infinite personalized practice by applying program synthesis and our theories of programming knowledge." Their goal: students would be able to master the basics of a 10 week intro computer science course in just 10 hours.

There are many more research shops around the globe, many of which have produced equally impressive work.

And if you're a developer or a coding trainer, you've probably never heard of any of them.

In fact, it's possible to spend an entire career as a coding professional, reading articles and blog posts in your area of specialization, going to tech conferences, and talking with your colleagues, without ever bumping the world of research on making coding easier to learn.  

It's not that some researchers aren't working with people out in the field. For example, Gidget influenced some of code.org's work. But the broader connections between academia and practitioners rarely exist. Too often this research is like a tree that falls in a forest and nobody but researchers hear it. If we're going to truly democratize emerging tech, that's got to change. 

The following are some strategies researchers might try if they want their research to make some noise.

NOTE:  this chapter gets into the (geeky) weeds, so if you aren't a techie or don't work in tech, you may want to skip to the next section on [creating institutional support for coding UX](40-institutional-support).

## 1) Embrace Tech Groups

More researchers need to start working closely with groups within the tech world. For example: 
- __Pythonistas__.  The Python programming language is often used for teaching beginners because it is one of the easier languages to learn, and there are many people in the community of "Pythonistas" who are passionate about spreading Python. If researchers could build a bridge to these people, they might find a very receptive audience for the results of the research. They also might find people who would be interested in helping them with their research.  
- __JavaScript Evangelists__.  The world of JavaScript has undergone several transformations in the past decade or so. If researchers were an active part of that subcommunity, they might find strategic moments where they could help shape its direction. And there plenty of websites for web designers and developers, such as Smashing Magazine and CodePen, where researchers could find influential voices in the JavaScript community who are receptive to research on making coding easier -- after all, they're already strong advocates for website UX. 
- __Tech Organizations for Women and People of Color__.  The past decade has also seen the rise of a wide range of tech groups aimed at making coding and other tech more accessible to women and people of color. Researchers who shared the same passions could undoubtedly find people receptive to their work, some of whom would also be interested in collaborating.

## 2) Focus More Research on Libraries/Frameworks

One of the most striking features of academic coding UX research is that it is primarily focused on languages -- either on modifying existing languages or on creating new ones. But these days, libraries, APIs, and frameworks that are built on top of programming languages are as or even more important to accessibility than the underlying language. For example:

- If someone says they are using Python for machine learning, odds are they aren't spending much time directly working with plain-vanilla Python.  The bulk of their work is using Python libraries with names like Tensorflow or Pytorch, and they may also be using a Python library called pandas to "clean up" their data so it's ready for analysis.
- If someone is developing VR/AR, they probably aren't spending much time with plain-vanilla C# or JavaScript, they're mostly using a C# framework called Unity or a JavaScript library called A-Frame.
If researchers focused more of their time on influencing libraries and frameworks, they might have a bigger impact.

### A) It's Easier to Change Frameworks/Libraries

- Getting Python coders to agree to a fundamental change to their language or to switch to a new language that's designed to be easier to learn? That's a pretty tall order. Changes in a language, for example, can end up breaking a staggering number of scripts and software products. Convincing them to switch from one Python data visualization library or machine learning library to the library researchers have helped make much more accessible? That's a much easier sell. 
- It's also common for developers to switch libraries/framework as better ones become available, so there are more opportunities for researchers to get their ideas out. And if their UX ideas help propel the use of an up-and-coming library, other library/framework designers are more likely to adopt these ideas.

### B) It's Easier to Build an Easy-to-Use Library on Top of another Library 

- If users are already using an emerging tech library, it's often pretty straightforward to build another library on top. For example, fast.ai's library that underlies their terrific course on deep learning is built on top of the Python library Pytorch.  This strategy can be a great way to either eliminate the hard parts of the underlying library or shield users from its weirder bits when they are first getting started. 
- This strategy lends itself to an iterative, organic approach, trying out a researcher's ideas and getting quick feedback -- or even working with members of the community to critique libraries as they are learning them and to provide suggestions for improving them. 
- Researchers who build an easier to use library on top of an existing library also have an almost built in audience for their work, which improves the odds they'll have an impact.

## 3) Make a Communications Plan

When medical researchers publish their findings in a journal, either their team or their institution has at least an implicit communications plan. Sometimes it involves a sophisticated press strategy, including having PR staff attempting to get the researchers booked on TV and radio. At the very least they put out a press release.  

But in the field of UX coding research, this appears to happen only rarely. Not surprisingly, the results of most UX coding research never reaches the audiences who need to know about it if it is going to have a real impact.

UX coding researchers don't need communications strategies as sophisticated as medical researchers; they aren't trying to reach a general audience. But even a little communications work could go a long way -- especially if researchers build relationships with tech groups.

## 4) Learn from Extension Services

Most UX coding researchers work in universities and colleges. And in many of those universities and colleges, there are staff who have a solid track record of making information more accessible: Extension Services. Coding and agriculture face different audiences and challenges. But there are surely valuable lessons UX coding researchers could learn from the decades of experience of their agricultural counterparts. 

## The Tech World Must Play Its Part

If researchers' work is going to have a significant impact, ultimately it's up to them to make it happen. But those of us who aren't researchers can also play a part by seeking out their research. Large tech companies can play a particularly important role, as they have the resources to find interesting research and figure out how to implement it. 

And if university and college researchers begin to build a more vibrant relationship with the world outside academia, demonstrating the practical worth of their research to a wider audience, large tech companies could help fund research that might have a strategic impact. 

For example, it's [relatively difficult to get research funding on making machine learning easier to learn](https://medium.com/bits-and-behavior/we-need-to-learn-how-to-teach-machine-learning-acc78bac3ff8). Given that most big tech companies are pouring huge amounts of money into machine learning/AI, it's in their self-interest to either fund this research themselves or lobby to get it funded.

 
<br/> Next: [Create Institutional Support For Coding UX](40-institutional-support)
<br/> Last: [Create a Continuum of Skill](20-continuum-skill.html)
<br/>Up: [Smooth the Learning Curve](00-index.html)

---
layout: content
title: Why We Need to Smooth the Learning Curve
image: rocky-landscape-637015-pxh.jpg
---
Consider the path that brought you to this report. Perhaps you found a link to it on Twitter or Facebook. Or you discovered it through a search you did on Google. Or you found it through a WordPress.com blog. However you got to it, there's a good chance that the technologies that routed you to the words in front of you were shaped by experts in a methodology that helps them figure out what makes a target audience tick and then design a website or app so it's easy for that audience to use. That methodology is user experience design, also known as UX.

In the worlds of web and mobile, UX has had a deep and profound impact on how designers work. You can take courses in UX design, go to conferences about it, even get a job doing it. If a corporation, nonprofit, or government is serious about reaching their audience, they've got staff or consultants who live and breathe UX. As you know from surfing the web, not every site uses UX design. But for anybody serious about building a great front-end, UX is a critical tool in their arsenal.

But for the programming languages and frameworks developers use to build these front-ends, it's a different story. The people who design these languages and frameworks rarely apply UX techniques to make it easier for your average person to be a developer.  You don't need to spend much time reading code [that looks like this](https://codelabs.developers.google.com/codelabs/ar-with-webxr/#5):

```
  if (hits.length) {
    const hit = hits[0];
    const hitMatrix = new THREE.Matrix4().fromArray(hit.hitMatrix);
    this.model.position.setFromMatrixPosition(hitMatrix);
    DemoUtils.lookAtOnY(this.model, this.camera);
    this.scene.add(this.model);
  }
```

to know that UX focused on everyday adults did not grace this house.

There is one major exception: programming languages and environments designed for young kids. There's a mountain of research on how to make it easier for young children to learn to code. Some of the resulting languages/tools, such as Scratch, are quite impressive.

But for the languages and frameworks adults need to know to get a job, the UX revolution might as well not exist.

Today, most efforts at making emerging tech accessible focus on training people to use coding tech as it is. In short, they try to move people closer to the tech. Despite a lot of hard work by very dedicated people, this strategy isn't enough to close the gap. Learning to code is still too hard and too clunky to have any chance of becoming a major opportunity for many people in every community. To truly democratize emerging tech, we also need to work the other side of the equation: move the tech closer to the people.
 
## What Is UX and How Do You Do It?

### What is UX? 

Although there are many ways to define UX, one of the [simplest and best definitions](https://www.nngroup.com/articles/definition-user-experience/) comes from the Nielsen Norman Group, whose founders were UX pioneers:

> The first requirement for an exemplary user experience is to meet the exact needs of the customer, without fuss or bother. Next comes simplicity and elegance that produce products that are a joy to own, a joy to use. 

A core feature of UX is the concept of usability. Here's How the Nielsen Norman Group [defines it](https://www.nngroup.com/articles/usability-101-introduction-to-usability/):

> Usability is a quality attribute that assesses how easy user interfaces are to use....  Usability is defined by 5 quality components:
> 
> -  __Learnability__: How easy is it for users to accomplish basic tasks the first time they encounter the design?
> - __Efficiency__: Once users have learned the design, how quickly can they perform tasks?
> - __Memorability__: When users return to the design after a period of not using it, how easily can they reestablish proficiency?
> - __Errors__: How many errors do users make, how severe are these errors, and how easily can they recover from the errors?
> - __Satisfaction__: How pleasant is it to use the design?

### Doing UX Doesn't Have To Be Complicated

Bringing UX to coding might sound like a lot of work, but it doesn't have to be. For example, here's how the Nielsen Norman Group describes how to use one of the most popular techniques, user testing, to fit a user interface to a particular audience's needs:

> - Get hold of some representative users...
> - Ask the users to perform representative tasks with the design.
> - Observe what the users do, where they succeed, and where they have difficulties with the user interface.
> ...
> 
> To identify a design's most important usability problems, __testing 5 users is typically enough. Rather than run a big, expensive study__, it's a better use of resources to __run many small tests__ and revise the design between each one so you can fix the usability flaws as you identify them. Iterative design is the best way to increase the quality of user experience. The more versions and interface ideas you test with users, the better (emphasis added).

UX can be a complex, labor-intensive practice. But even a small amount smartly done can make a big difference.

 
<br/>Next: [Embrace Community-Oriented Coding UX](10-culture-community-coding-UX.html)
<br/>Up: [Smooth the Learning Curve](00-index.html)

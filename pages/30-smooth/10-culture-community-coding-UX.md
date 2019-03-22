---
layout: content
title: Create a Culture of Community-Oriented Coding UX
# image:
---
Consider the path that brought you to this report. Perhaps you found a link to it on Twitter or Facebook. Or you discovered it through a search you did on Google. Or you found it through a WordPress.com blog. However you got to it, there's a good chance that the technologies that routed you to the words in front of you were shaped by experts in a methodology that helps them figure out what makes a target audience tick and then design a website or app so it's easy for that audience to use. That methodology is user experience design, also known as UX.

In the worlds of web and mobile, UX has had a deep and profound impact on how designers work. You can take courses in UX design, go to conferences about it, even get a job doing it. If a corporation, nonprofit, or government is serious about reaching their audience, they've got staff or consultants who live and breathe UX. As you know from surfing the web, not every site uses UX design. But for anybody serious about building a great front-end, UX is a critical tool in their arsenal.

But when it comes to the programming languages and frameworks developers use to build these front-ends? The people who design these languages and frameworks rarely apply UX techniques to make it easier for your average person to use them. You don't need to spend much time reading code [that looks like this](https://codelabs.developers.google.com/codelabs/ar-with-webxr/#5):

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

But for the languages and frameworks adults need to know to get a job? The UX revolution might as well not exist.

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
> To identify a design's most important usability problems, __testing 5 users is typically enough. Rather than run a big, expensive study__, it's a better use of resources to __run many small tests__ and revise the design between each one so you can fix the usability flaws as you identify them. Iterative design is the best way to increase the quality of user experience. The more versions and interface ideas you test with users, the better (emphasis added).

UX can be a complex, labor-intensive practice. But even a small amount smartly done can make a big difference.
 
## Why Coding Tool Makers Don't Realize Their Tech Is Inaccessible
Today, the UX of coding libraries, frameworks, etc. is usually tested by seeing if the tool makes sense to a tech company's coders and other people with a similar background. So it's no surprise that these coders don't realize their tools are unnecessarily intimidating or inaccessible to people who aren't like them. 

For example, one of the major development platforms for creating virtual reality and augmented reality is the Unity gaming engine. The company that built Unity has developed a large number of tutorials to help people master Unity development.  In their first tutorial for beginners, here's the [first script](https://www.nngroup.com/articles/usability-101-introduction-to-usability/) you write:

```
public class PlayerController : MonoBehaviour {
    public float speed;
    private Rigidbody rb;

    void Start ()      {
        rb = GetComponent<Rigidbody>();
    }

    void FixedUpdate ()    {
        float moveHorizontal = Input.GetAxis ("Horizontal");
        float moveVertical = Input.GetAxis ("Vertical");
        Vector3 movement = new Vector3 (moveHorizontal, 0.0f, moveVertical);
        rb.AddForce (movement * speed);
    }
}
```

Several smart, thoughtful people from the tech world who were interviewed for this report didn't recognize that scripts like this might intimidate many beginners and might pose a significant obstacle.

This is completely understandable. Unity has fostered a wonderful, thriving user community, that includes plenty of beginners who've picked up the basics of the Unity framework. If you're part of this community, scripts like the one above might not seem like a big deal.   

Similarly, the developers of many programming libraries and frameworks are skilled at listening to their existing users and then evolving their tools so they get better and better at serving these user's needs. What they've accomplished using this strategy is often quite impressive.

But these approaches have a serious flaw: self-selection bias.  Despite good intentions, these developers aren't addressing the needs of people who aren't using their tool -- especially people who find their tool too intimidating. If the tech world wants to truly democratize emerging tech, we're going to need to think beyond the user experience of the people we are already reaching.

Tech company CEOs say they want to empower not just people like themselves but everyone. That means empowering truck drivers and waitresses, hairdressers and janitors, ex-miners and nursing home aides. If they're serious about doing that, they need to "level up" and focus on these audiences.
## Community-Oriented UX:  Coding UX's "Special Sauce"


If a tech company randomly picked five people off the street who weren't geeks and did a little UX testing of their coding platform, they'd be way ahead of the game. At this point, any efforts to move beyond their usual audience would yield useful results.

But if tech companies want to truly democratize emerging tech, they should try a more ambitious strategy:  building relationships with community groups, especially those who are already providing technical trainings.

One of the reasons why millions of US farmers were able to master modern farming is because Extension Services created a feedback loop between researchers and farming communities. If an agricultural researcher had devised a new approach for reducing problems with a particularly pesky beetle or a better strategy for planting wheat, an Extension Services agent would show it to farmers in their county. They'd get feedback from the farmers about what worked and what didn't, which would get passed back to researchers. 

There's no reason that the tech industry couldn't begin to create similar relationships with community groups around coding UX. These community groups could provide a great environment for not only conducting formal UX studies but also providing ongoing real-world feedback that benefited both communities and the tech industry.

In doing so, it could offer communities additional benefits:

- __Small Businesses Community Co-Ops For Coding UX Services__. Community groups could create small businesses or co-ops that provide the tech industry one-stop shopping for UX testing services. In doing so, they would also create relationships that might lead to future business opportunities.
- __Early Access to Cutting-Edge Hardware__. As part of the UX studies, tech companies would give some members of marginalized communities early access to emerging tech hardware that they otherwise couldn't afford. And that in turn could give people in these communities a chance to get involved in emerging tech in an early stage where mastering the tech before it's widespread can open up new opportunities.
- __From Tool Users to Tool Makers__.  Community-oriented coding UX could shift the perspective of coding beginners. Rather than seeing themselves as people who just use tools, they would also be involved in making them. Community groups could even explore modifying their trainings so that part of the learning process is learning how to evaluate and envision improving the coding experience for the next generation of coders in their community. 

## Help Communities, Help Your Bottom Line

Tech company CEOs are passionate about democratizing their technology because they care about society. But if they do it right, this approach will also help their company's bottom line.

Emerging tech's accessibility isn't just an issue for marginalized communities. Corporations and large nonprofits also struggle with how hard it is to develop solutions using emerging tech. Corporations can often paper over the problem by throwing money at it, spending scary amounts of money on consultants and/or hiring techies to do work that regular staff ought to be able to handle if the tech was properly designed. But if it's easier for people in South Central or Harlan County to master emerging tech, it'll also be easier for corporate staff to master it. 

And that could be a major competitive advantage for any companies competing in a new tech market. In the battle to see which companies will win the biggest slices of an emerging tech pie, smoothing the learning curve could dramatically speed up the adoption of their tools.

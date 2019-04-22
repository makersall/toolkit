---
layout: content
title: Create a Culture of Community-Oriented Coding UX
image: tiered-landscape-people-1450141-pxh.jpg
---
## Why Coding Tool Makers Don't Realize Their Tech Is Inaccessible
Today, the UX of coding libraries, frameworks, etc. is usually tested by seeing if the tool makes sense to a tech company's coders and other people with a similar background. So it's no surprise that these coders don't realize their tools are unnecessarily intimidating or inaccessible to people who aren't like them. 

For example, one of the major development platforms for creating virtual reality and augmented reality is the Unity gaming engine. The company that built Unity has developed a large number of tutorials to help people master Unity development.  In their first tutorial for beginners, here's the [first script](https://unity3d.com/learn/tutorials/projects/roll-ball-tutorial/moving-player) you write:

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

The people at Unity who developed this script, who are undoubtedly passionate about democratizing Unity's tech, didn't recognize that scripts like this might intimidate many beginners and might pose a significant obstacle.

This is completely understandable. Unity has fostered a wonderful, thriving user community, that includes plenty of beginners who've picked up the basics of the Unity framework. If you're part of this community, scripts like the one above might not seem like a big deal.   

Similarly, the developers of many programming libraries and frameworks are skilled at listening to their existing users and then evolving their tools so they get better and better at serving these user's needs. What they've accomplished using this strategy is often quite impressive.

But these approaches have a serious flaw: self-selection bias.  Despite good intentions, these developers aren't addressing the needs of people who aren't using their tool -- especially people who find their tool too intimidating. If the tech world wants to truly democratize emerging tech, we're going to need to think beyond the user experience of the people we are already reaching.

Tech company CEOs say they want to empower not just people like themselves but everyone. That means empowering truck drivers and waitresses, hairdressers and janitors, ex-miners and nursing home aides. If they're serious about doing that, they need to "level up" and focus on these audiences.
## Community-Oriented UX:  Coding UX's "Special Sauce"


If a tech company randomly picked five people off the street who weren't geeks and did a little UX testing of their coding platform, they'd be way ahead of the game. At this point, any efforts to move beyond their usual audience would yield useful results.

But if tech companies want to truly democratize emerging tech, they should try a more ambitious strategy:  building relationships with community groups, especially those who are already providing technical training.

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

<br/> Next: [Create a Continuum of Skill](20-continuum-skill.html)
<br/>Last: [Why We Need to Smooth the Learning Curve](05-why.html)
<br/>Up: [Smooth the Learning Curve](00-index.html)

---
layout: summary
title: Smooth the Learning Curve
# image:
chapters:
  - name: Create a Culture of Community-Oriented Coding UX
    link: '10-culture-community-coding-UX.html'
    image: 'painted-hands-1332840-pxh.jpg'
  - name: Create a Continuum of Skill
    link: '20-continuum-skill.html'
    image: 'paint-brushes-1366198-pxh.jpg'

---
## Test


{% for chapter in page.chapters %}
<article><img src="{{'/assets/images/' | append:  chapter.image | relative_url }}"  style= "width: 200px; height: auto;">
<a href="{{ chapter.link }}">{{chapter.name}}</a>
</article>
{%- endfor -%}

<br/>And that was a test

## Original

- Create A Culture Of [Community-Oriented Coding UX](10-culture-community-coding-UX.html)
- Create a [Continuum of Skill](20-continuum-skill.html)
- Evangelize [Breakthrough Research](30-evangelize-research.html) on Coding UX
- Create [Institutional Support](40-institutional-support) For Coding UX

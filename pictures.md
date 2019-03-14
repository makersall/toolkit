---
layout: page
title: Pixes
permalink: /pix/
pictures:
  - home
  - https://pxhere.com/en/photo/1366198
  - https://pxhere.com/en/photo/1323248
  - funky
  - https://pxhere.com/en/photo/1006993
  - https://pxhere.com/en/photo/1002524
  - https://pxhere.com/en/photo/1002518
  - paintsupplies
  - https://pxhere.com/en/photo/961049
  - https://pxhere.com/en/photo/927637
  - https://pxhere.com/en/photo/638450
  - https://pxhere.com/en/photo/1043734
  - painted
  - https://pxhere.com/en/photo/143678
  - https://pxhere.com/en/photo/777250
  - other
  
  
---

test start

 {% for item in page.pictures %}
  - [ {{ item }}]({{ item }})
      {% endfor %}
   
and scene!

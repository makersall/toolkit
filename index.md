---
layout: home
---

[Introduction](/pages/intro/intro.html)

[Pictures](pix/) we might use for the toolkit

Time to get started

 {%- assign default_paths = site.pages | map: "path" -%}
{%- assign page_paths = site.header_pages | default: default_paths -%}


This is a test.

{{site.navigation_links}}

The site URL is:<br/>

{{site.url}}

<br/>
Is what the site URL is

<div class="trigger">
{%- for path in page_paths -%}
{%- assign my_page = site.pages | where: "path", path | first -%}
{{ my_page.url}}<br/>
{{ my_page.url  | absolute_url}}<br/>

<!-- <a class="page-link" href="{{ my_page.url | relative_url }}">{{ my_page.title | escape }}</a> -->
{%- endfor -%}
</div>
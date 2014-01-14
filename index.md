---
layout: page
title: Josh Herr's Open Notebook
tagline: Notes for myself and (maybe) others
---
{% include JB/setup %}

This is a place for me to sync notes I have taken -- mainly for myself but some of these notes may be of use to others.  

Please see the following places for more information on me:

Website: [Joshua R. Herr](http://joshuaherr.com)

Blog: [Cyme & Cystidium](http://cymeandcystidium.com)

Twitter: [number_three](https://twitter.com/number_three)

Some things I am involved with:

[GitHub](https://github.com/jrherr)

[Google Scholar](http://scholar.google.com/citations?user=ZDnMer4AAAAJ&hl=en)

[Biostar](http://www.biostars.org/u/1704/)

[Software Carpentry](http://software-carpentry.org/pages/team.html)

## Notes:

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>



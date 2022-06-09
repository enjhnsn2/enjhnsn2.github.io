---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<a href="#publications">Jump to publications.</a>

I am a third year PhD student at University of California San Diego advised by <a href="https://cseweb.ucsd.edu//~dstefan/">Deian Stefan</a>
 and <a href="https://cseweb.ucsd.edu/~savage/"> Stefan Savage</a>. I am broadly interested in applying program analysis to improve the security of software systems. In particular, I am interested in software sandboxing, binary analysis, and automated reverse engineering.

{% include base_path %}



<a id="publications"></a> 
<h2>Publications</h2> 

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}



<a id="unpublished"></a> 
<h2>Unpublished Work</h2>

{% for post in site.unpublished reversed %}
  {% include archive-single.html %}
{% endfor %}



<a id="awards"></a> 
<h2>Awards</h2>

{% for post in site.awards reversed %}
  {% include archive-single.html %}
{% endfor %}




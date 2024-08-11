---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<a id="aboutme"></a> 

I am a fourth year PhD student at University of California San Diego advised by <a href="https://cseweb.ucsd.edu//~dstefan/">Deian Stefan</a>
 and <a href="https://cseweb.ucsd.edu/~savage/"> Stefan Savage</a>. My research focuses on software sandboxing, verified programming, and WebAssembly security. 

I completed my undergraduate degree in Computer Engineering at University of Illinois Urbana-Champaign.


{% include base_path %}



<a id="publications"></a> 
<h2>Publications</h2> 

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}






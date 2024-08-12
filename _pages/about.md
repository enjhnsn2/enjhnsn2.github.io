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

I am a sixth year PhD student at University of California San Diego advised by <a href="https://cseweb.ucsd.edu//~dstefan/">Deian Stefan</a>
 and <a href="https://cseweb.ucsd.edu/~savage/"> Stefan Savage</a>. My research focuses on solving hard security problems in real-world systems using lightweight, practical verification[<a href="https://par.nsf.gov/servlets/purl/10442363">1</a>,<a href="https://par.nsf.gov/servlets/purl/10228509">2</a>,<a href="https://dl.acm.org/doi/pdf/10.1145/3498688">3</a>]. I also spend time working on hardware security[<a href="https://dl.acm.org/doi/pdf/10.1145/3582016.3582023">4</a>,<a href="https://par.nsf.gov/servlets/purl/10399090">5</a>,<a href="https://www.computer.org/csdl/journal/ec/2024/01/10144599/1NJjnXinZrW">6</a>], compiler security[<a href="https://www.usenix.org/system/files/sec21-narayan.pdf">7</a>,<a href="https://dl.acm.org/doi/pdf/10.1145/3571208">8</a>,<a href="https://par.nsf.gov/servlets/purl/10442503">9</a>], and ocasionally find bugs in airplanes[<a href="https://www.usenix.org/system/files/sec21-johnson.pdf">10</a>].  

I completed my undergraduate degree in Computer Engineering at University of Illinois Urbana-Champaign.


{% include base_path %}



<a id="publications"></a> 
<h2>Publications</h2> 

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}






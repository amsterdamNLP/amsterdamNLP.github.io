---
layout: main
---

*AmsterdamNLP is an initiative of the Language and Computation group of the ILLC at the University of Amsterdam*

# About

* More about [ILLC](//www.illc.uva.nl)
* More about [language and computation at ILLC](http://www.illc.uva.nl/Research/Programmes/laco/)

# News

<ul class="post-list">
{% for post in site.posts %}
  <li>
    {% include postsummary.html post=post %}
  </li>
{% endfor %}

</ul>


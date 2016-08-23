---
title: "pconrad's C++ site"
---

# C++ Resources for CMPSC 16, 24, 32 and CMPTGCS 1A

<div id="about" data-role="collapsible" data-collapsed="false" markdown="1">
<h2>About this site</h2>

This sites contains various resources and materials for students and educators to help with
learning Computer Science concepts through C++ programming.

The materials are primarily for use in four courses taught by [Phill Conrad](http://www.cs.ucsb.edu/~pconrad)
in the [Dept. of Computer Science](http://www.cs.ucsb.edu) at
[UC Santa Barbara](http://www.ucsb.edu), namely
[CMPSC&nbsp;16](http://www.cs.ucsb.edu/education/courses/cmpsc-16)
[CMPSC&nbsp;24](http://www.cs.ucsb.edu/education/courses/cmpsc-24)
[CMPSC&nbsp;32](http://www.cs.ucsb.edu/education/courses/cmpsc-32)
and&nbsp;[CMPTGCS&1A](https://ccs.ucsb.edu/courses/computer-programming-and-organization-1-0)

</div><!-- about -->


<div id="textbooks" data-role="collapsible" data-collapsed="false">
  <h2>Textbooks</h2>
  <p>Articles on individual chapters can be found on the pages for each textbook</p>
    <ul>
      {% assign textbooks = site.textbooks | sort: 'custom_sort_order' %}
      {% for textbook in textbooks %}
         <li><a href="{{textbook.url}}">{{ textbook.title }}</a>&mdash;{{textbook.desc}}</li>
      {% endfor %}
    </ul>
</div>

<div id="topics" data-role="collapsible" data-collapsed="false">
  <h2>Topics</h2>
  <ul>
   {% for topic in site.topics %}
     <li><a href="{{topic.url}}">{{ topic.topic }}</a>&mdash;{{topic.desc}}</li>
   {% endfor %}
  </ul>
</div>


<div id="resources" data-role="collapsible" data-collapsed="false">
  <h2>Resources</h2>
  <ul>
   {% for topic in site.resources %}
     <li><a href="{{topic.url}}">{{ topic.topic }}</a>&mdash;{{topic.desc}}</li>
   {% endfor %}
  </ul>
</div>


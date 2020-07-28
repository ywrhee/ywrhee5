---
title: 
layout: single
classes: wide
author-profile: false
permalink: /teaching/
sidebar:
  title: "Teaching"
  nav: sidebar-teaching
---
<div style="margin-top:10px;"></div> <!-- -30px -->

# University of Southern California

+ **Strategic Management**, *Instructor* (BUAD497)
  + Fall 2020 <a href="https://classes.usc.edu/term-20203/course/buad-497/" class="btn btn--info btn--small">Schedule</a>
  + Fall 2019 <a href="https://classes.usc.edu/term-20193/course/buad-497/" class="btn btn--info btn--small">Schedule</a>
  <a href="https://web-app.usc.edu/soc/syllabus/20193/15102.pdf" class="btn btn--warning btn--small">Syllabus</a><br><br>

# University of California, Berkeley

+ **Competitive Strategy**, *Teaching Assistant* (EWMBA299)
  + Fall 2016 & Fall 2015

+ **Entrepreneurship and Technology Commercialization Program**, *Guest Lecturer*<br />  
  + Fall 2016 ("Product Market Competition and Incentivizing Technological Innovation")
  + Fall 2015 ("Silicon Valley: Entrepreneurship and Worker Mobility")
  + Note: this event was organized by Hanyang University and Korean government and held at UC Berkeley campus

+ **Game Theory and Entrepreneurship**, *Guest Lecturer* ("B-BAY," Berkeley Business Academy for Youth )
  + Summer 2015<br><br>

# Seoul National University

+ **Strategy**, *Teaching Assistant* (Executive MBA)
  + Spring/Summer 2011

+ **Theories of Strategy in the Global Knowledge-based Economy**, *Teaching Assistant* (MS/PhD Core Class)
  + Spring 2011

<input id="toggle" type="checkbox" checked class="toggle">
  <label for="toggle">Teaching</label>
  <div class="expand">
      <p>Details<br>Details</p>
  </div>


<nav class="nav__list">
  <h3 class="nav__title" style="padding-left: 0;">{{ page.sidebar.title }}</h3>
  <input id="abstract1" name="accordion-toc" type="checkbox" />
  <label for="abstract1">Abstract</label>
  <ul class="nav__items">
  
      <li>
        {% if nav.url %}
          <a href="{{ nav.url | relative_url }}"><span class="nav__sub-title">{{ nav.title }}</span></a>
        {% else %}
          <span class="nav__sub-title">{{ nav.title }}</span>
        {% endif %}

  </ul>
</nav>

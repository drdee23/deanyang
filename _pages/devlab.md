---
layout: archive
title: "DevLab"
permalink: /devlab/
author_profile: true
---

<!-- ////////////// -->

 
<!-- > [devlab page]( /devlab_page_2/) /   [devlab page]( /devlab_page_3/) /    [devlab page]( /devlab_page_3/) /    -->
<div class="masthead">
  <div class="masthead__inner-wrap">
    <div class="masthead__menu">
      <nav id="" class="greedy-nav">
        <!-- <button><div class="navicon"></div></button> -->
        <ul class="visible-links">
                
{% for link in site.data.devlab-navigation.devlab-nav %}
            {% if link.url contains 'http' %}
              {% assign domain = '' %}
              {% else %}
              {% assign domain = base_path %}
            {% endif %}
            <li class="masthead__menu-item"><a href="{{ domain }}{{ link.url }}">{{ link.title }}</a></li>
          {% endfor %}
        </ul>
        <ul class="hidden-links hidden"></ul>
      </nav>
    </div>
  </div>
</div>


<!-- ///////////// -->



<!-- =============================Dev Lab home Content Below========================== -->



### Some sample Devlab home content

Like many other websites, this site uses log files to help learn about when, from where, and how often traffic flows to this site. The information in these log files include:

* Internet Protocol addresses (IP)
* Types of browser
* Internet Service Provider (ISP)
* Date and time stamp
* Referring and exit pages
* Number of clicks

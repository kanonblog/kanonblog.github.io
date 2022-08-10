---
layout: post
title: "Daily life of 2-3 class - (Ch.?) ???"
date: draft 19:58:00 +0800
background: ''
tags: 
- original-creation
- 2-3-class
---

<style>
    img{
        width: 100%;
        height: 100%;
        display:block;
        vertical-align: middle;
    }
</style>

<div class="table-content">
    <p>Content</p>
    <p>
    <ul>
    <li><a href="#set-A">Content</a></li>
    <li><a href="#set-B">Tranditional Chinese Version</a></li>
    <li><a href="#set-C">Last words</a></li>
    </ul>
    </p>
</div>

<p><div class="left-margin" id="set-A"><h2>Content</h2></div></p>
<table>

</table>
<br><br>

<p><div class="left-margin" id="set-B"><h2>Traditional Chinese Version</h2></div></p>
<p>
            {% for post in site.posts %}
                {%if post.title == "???????????"%}
                <hr>
                <div>
                <a href="{{ site.baseurl }}{{ post.url }}"><h4>{{ post.title }}</h4>
                  {% if post.subtitle %}
                  <p style="font-size:15px">{{ post.subtitle }}</p>
                  {% else %}
                  <p style="font-size:15px">{{ post.excerpt | strip_html | truncatewords: 15 }}</p>
                  {% endif %}
                </a>
                </div>
                <hr>
                {%endif%}
            {% endfor %}    
</p>
<br><br>
<p><div class="left-margin" id="set-C"><h2>Last words</h2></div></p>
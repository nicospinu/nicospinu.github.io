---
layout: page
title: GSoC
permalink: /gsoc/
description:
---
Under the mentorship of <a href="https://ravinkumar.com/">Ravin Kumar</a> and 
<a href="https://junpenglao.xyz/">Junpeng Lao</a>, I'm spending the summer of 2022 as a student at 
<a href="https://summerofcode.withgoogle.com/">Google Summer of Code (GSoC)</a>. This page is intended 
to provide a series of blog posts from <b>project management</b> to <b>technical implementations</b> and <b>examples</b> 
in <a href="https://www.pymc.io/welcome.html">PyMC</a>. The full description of the project can be read
<a href="https://summerofcode.withgoogle.com/programs/2022/projects/fRXAozWv">here</a>. Wish me luck 😃

<hr>

<br>
<ul class="post-list">
    {% for post in site.posts %}
        {% if post.tags contains 'gsoc' %}
        <li>
        <h2><a class="post-title" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></h2>
        <p class="post-meta">{{ post.date | date: '%B %-d, %Y' }}</p>
        <p>{{ post.description }}</p>
        <br/>
        <hr/>
        </li>
        {% endif %}
    {% endfor %}
</ul>

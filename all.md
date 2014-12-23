---
layout: page
title: All Content
permalink: /all/
---

<div class="home">

  <h1 class="page-heading">Pages</h1>

  <ul class="post-list">
    {% for page in site.pages %}
      <li>
          <a class="page-link" href="{{ page.url | prepend: site.baseurl }}">{{ page.title }}</a>
      </li>
    {% endfor %}
  </ul>


  <p class="rss-subscribe">subscribe <a href="{{ "/feed.xml" | prepend: site.baseurl }}">via RSS</a></p>

</div>

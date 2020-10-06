---
layout: page
title: Podcasts
permalink: /podcasts/
---

<ul>
  {% for podcast in site.podcasts %}
    <li>
      <a href="{{ podcast.url }}">{{ podcast.title }}</a>
    </li>
  {% endfor %}
</ul>

If you have a lot of podcasts, you may want to consider adding [pagination](https://www.bridgetownrb.com/docs/content/pagination)!

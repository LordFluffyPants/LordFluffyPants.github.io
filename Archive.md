---
layout: page
title: Archive 
---

This is a list of all of our previous posts; all collected and listed for your reading pleasure:
<div class="related">
  <ul class="related-posts">
    {% for post in site.posts %}
          <a href="{{ post.url }}">
            {{ post.title }}
            <small>{{ post.date | date_to_string }}</small>
          </a>
    {% endfor %}
  </ul>
</div>
---
layout: page
title: Archive 
---

This is a list of all of our previous posts; all collected and listed for your reading pleasure:

<ul class="related-posts">
    {% for post in site.posts %}
          <p>
          <a href="{{ post.url }}">
            {{ post.title }}
            </a>
            <small>{{ post.date | date_to_string }}</small>
          </p>
    {% endfor %}
</ul>

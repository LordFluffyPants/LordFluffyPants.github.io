---
layout: page
title: Archive 
---

This is a list of all the Games that we have reviewed all collected and listed for your reading pleasure:
<div class="related">
  <ul class="related-posts">
    {% for post in site.posts %}
      <li>
        <h3>
          <a href="{{ post.url }}">
            {{ post.title }}
            <small>{{ post.date | date_to_string }}</small>
          </a>
        </h3>
      </li>
    {% endfor %}
  </ul>
</div>
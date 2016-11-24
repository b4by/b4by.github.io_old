---
layout: default
---
{% for post in site.posts %}
  <div class="post-title-link">
    <p><a href="{{post.url}}">{{post.title}}</a></p>
  </div>
  <div class="post-content">
    <p>{{post.content}}</p>
  </div>
 {% endfor %}

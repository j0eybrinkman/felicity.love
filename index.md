---
layout: default
---

{% for post in site.posts %}
  <h2><a href=" {{site.baseurl}}{{ post.url }} ">{{ post.title }}</a></h2>
  <p>{{ post.date | date_to_string }}</p>
  <img src=" {{ post.featured_image | relative_url }} " alt="">
{% endfor %}

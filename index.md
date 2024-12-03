---
layout: default
---

{% for post in site.posts %}
  <div>
    <a class="date" href=" {{site.baseurl}}{{ post.url }} ">
      <!-- <h2>{{ post.title }}</h2> -->
      <p>{{ post.date | date_to_string }}</p>
      <img src=" {{ post.featured_image | relative_url }} " alt="" />
    </a> 
  </div>
  <!-- banner ad -->
  <div>
      <a target="_blank" href="linktr.ee/velvetrosestudios" onClick="adClick(); return true;"><img src="/img/ads/velvet_rose_studios/velvet_rose_december2024_ad.webp" alt=""/></a>
  </div>
  <!-- end of banner ad --> 
{% endfor %}


---
layout: page
title: 
tagline: 
---
<div class="blog-index">
  {% for post in site.posts %}
    {% assign content = post.content %}
    {% include post_detail.html %}
    <hr />
  {% endfor%}
</div>
~
~

---
layout: default
---

{% for post in site.categories.jekyll %}

<div class="blog-post">
            <h2 class="blog-post-title"><a href="{{ post.url|prepend: site.baseurl }}">{{ post.title }}</a></h2>
            <p class="blog-post-meta">{{ post.date }}</p>
            {{ post.content  }}

 </div>

{% endfor %}

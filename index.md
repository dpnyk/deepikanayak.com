---
layout: home
---

I'm a User Experience designer based out of Bangalore. I've worked on various aspects of User Experience Design, Branding and Marketing. Checkout my <a href="/work/">portfolio</a> here

## Recent blog posts

{% for post in site.posts %}
  <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
{% endfor %}
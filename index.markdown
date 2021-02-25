---
layout: default
---
<h1>Welcome to WTF is Git?!?</h1>

<h2>Meet our members:</h2>
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
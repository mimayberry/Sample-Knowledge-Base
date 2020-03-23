# Welcome to the Severson Group Knowledge Base

This is a simple demonstration of a knowledge base using GitHub. You'll find a few sample articles and links to various resources we may find useful. Please look around and let us know what you think!


<ul>
  {% for post in site.posts %}
    <li>
      <a href="/github-pages-with-jekyll{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

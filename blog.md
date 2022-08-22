<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}"><h2>{{ post.title }}</h2></a>
      {{ post.excerpt }}
      <a href="{{ post.url }}">Read more</a>
    </li>
  {% endfor %}
</ul>

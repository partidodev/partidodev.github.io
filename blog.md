{% for post in site.posts %}
<h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
<p>{{ post.date }}</p>
{{ post.content | strip_html | truncatewords: 50 }}
<p><a href="{{ post.url }}">Read more</a></p>
{% endfor %}

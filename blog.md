{% for post in site.posts %}
<a href="{{ post.url }}"><h2>{{ post.title }}</h2></a>
{{ post.excerpt }}
<a href="{{ post.url }}">Read more</a>
{% endfor %}

# Researches

<p>
{% for post in site.posts %}
	{% if post.tags contains "Research" %}
		<hr>

		<h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
		{{ post.excerpt }}

		{% if post.excerpt.size < post.content.size %}
			<big> <a href="{{ post.url }}">... More</a> </big> <br>
		{% endif %}

		Tags: <em>{{ post.tags | join: "</em> - <em>" }}</em>
	{% endif %}
{% endfor %}
</p>

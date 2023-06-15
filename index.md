---
title: Gustavowl
---
# Recent Activites {#recent-activities}
<hr>

{% assign max_count = 3 %}

## [Papers](/activities/papers.md)

{% assign count = max_count %}
<ul>
{% for post in site.posts %}
	{% if post.tags contains "Paper" and count > 0 %}
		{% if count < max_count %}
			<hr>
		{% endif %}

		{% assign count = count | minus:1 %}
		<li>
			<h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
			{{ post.excerpt }}

			{% if post.excerpt.size < post.content.size %}
				<big> <a href="{{ post.url }}">... More</a> </big> <br>
			{% endif %}

			Tags: <em>{{ post.tags | join: "</em> - <em>" }}</em>
		</li>
	{% endif %}
{% endfor %}

</ul>
[See all papers](/activities/papers.md)
<hr>

## [Projects](/activities/projects.md)
{% assign count = max_count %}
<ul>
{% for post in site.posts %}
	{% if post.tags contains "Project" and count > 0 %}
		{% if count < max_count %}
			<hr>
		{% endif %}

		{% assign count = count | minus:1 %}
		<li>
			<h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
			{{ post.excerpt }}

			{% if post.excerpt.size < post.content.size %}
				<big> <a href="{{ post.url }}">... More</a> </big> <br>
			{% endif %}

			Tags: <em>{{ post.tags | join: "</em> - <em>" }}</em>
		</li>
	{% endif %}
{% endfor %}
</ul>
[See all projects](/activities/projects.md)
<hr>

## [Talks](/activities/talks.md)

{% assign count = max_count %}
<ul>
{% for post in site.posts %}
	{% if post.tags contains "Talk" and count > 0 %}
		{% if count < max_count %}
			<hr>
		{% endif %}

		{% assign count = count | minus:1 %}
		<li>
			<h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
			{{ post.excerpt }}

			{% if post.excerpt.size < post.content.size %}
				<big> <a href="{{ post.url }}">... More</a> </big> <br>
			{% endif %}

			Tags: <em>{{ post.tags | join: "</em> - <em>" }}</em>
		</li>
	{% endif %}
{% endfor %}
</ul>
[See all talks](/activities/talks.md)

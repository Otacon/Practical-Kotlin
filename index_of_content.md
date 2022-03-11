# Indice del corso
{% for post in site.android %}
<a href="{{ site.baseurl }}{{ post.url }}">
{{ post.chapter }}.{{ post.section }} - {{ post.title }}
</a>
{% endfor %}
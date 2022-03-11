# Indice del corso
{% for post in site.android %}
<a href="{{ post.url }}">
{{ post.chapter }}.{{ post.section }} - {{ post.title }}
</a>
{% endfor %}
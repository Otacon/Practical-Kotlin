# Indice del corso
{% for post in site.android %}
{{ post.chapter }}.{{ post.section }} - {{ post.title }}
{% endfor %}
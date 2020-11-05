--- layout: default ---

{% for post in site.posts %}

[{{ post.title }}]({{%20site.baseurl%20}}{{%20post.url%20}})
============================================================

{{ post.excerpt }}

[Read More]({{%20site.baseurl%20}}{{%20post.url%20}})

{% endfor %}

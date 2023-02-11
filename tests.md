---
title: Tests
---

Testing code

{% for col in site.collections %}
    {{ col.label }}
    {% if col.docs %}
    {% assign sorted = col.docs | sort: 'title'  %}
<ul class="side-nav">
    {% for page in sorted %}
        {% unless page.published == false %}
        <li><a href="{{ site.url }}{{ page.url }}">{{ page.title }}</a>, folder={{ page.dir }}</li>
        {% endunless %}
    {% endfor %}
    <li>&nbsp;</li>
</ul>
    {% endif %} 
{% endfor %}

# Tags

{% for tag in site.tags %}
  <h3>{{ tag[0] }}</h3>
  <ul>
    {% for post in tag[1] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}


# Pages


{% assign sorted = site.documents | sort: 'title' | where_exp: "document", "document.path contains '_historique/commandants/'" %}
<ul>
  {% for p in sorted %}
    <li><a href="{{ p.url }}">{{ p.title }}</a>; props: {{ p.name }} </li>
  {% endfor %}
</ul>
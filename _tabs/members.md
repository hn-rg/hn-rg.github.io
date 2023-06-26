---
icon: fa-solid fa-person
type: sidebar
order: 1
---

## Research Group Leader
{% for a in site.tabs %}
    {% if a.type  == 'rgl' %}
[{{ a.title }}]({{ a.permalink }})
    {% endif %}
{% endfor %}

## PhDs


{% for a in site.tabs %}
    {% if a.type  == 'phd' %}
[{{ a.title }}]({{ a.permalink }})
    {% endif %}
{% endfor %}


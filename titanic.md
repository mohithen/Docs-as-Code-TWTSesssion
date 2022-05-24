---
layout: template
---
# Titanic Passenger List

{% for item in site.data.titanic %}
- {{ item.Name }}, {{item.Age}}
{% endfor %}
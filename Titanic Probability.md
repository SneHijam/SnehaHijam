---
layout: templates
---


## Titanic Probability:

{% for item in site.data.titanic %}
- {{item.Survived}}, {{item.Pclass}}, {{item.Name}}, {{item.Sex}}, {{item.Age}}, {{item.Siblings/Spouses Aboard}}, {{item.Parent/Children Aboard}}, {{item.Fare}}, 
{% endfor %}




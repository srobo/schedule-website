---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: page
---
{% for volunteer_schedule in site.schedule %}
<h3>{{volunteer_schedule[0]}}</h3>
{% for pair in volunteer_schedule[1] %}
{{pair[0]}} - {{pair[1]}}
{% endfor %}
{% endfor %}
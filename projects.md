---
title: My projects
permalink: /projects/
---
{% for project in site.projects %}
## {{ project.title }}
#### **Stack:** {{ project.technologies | join: ", " }}
#### **Repository:** [{{ project.repo }}]({{ project.repo }}){:target="_blank"}
#### Description:
{{ project.description }}
[more details →]({{ project.url }})
{% endfor %}
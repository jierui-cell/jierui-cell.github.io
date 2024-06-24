---
layout: page
title: "Projects"
permalink: /projects/
---

# Projects

{% for project in site.portfolio %}
## {{ project.title }}
**Description:** {{ project.description }}  
**Technologies used:** {{ project.technologies }}  
[Read more]({{ project.url }})
{% endfor %}

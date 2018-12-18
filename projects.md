---
layout: page
title: Projects
permalink: /pojects/
---

**Projects**

| Name of the Investigator | Title of the project  | Amount sanctioned | Funding Agency |   
| ---- | ----- | ----- |----- |
{% for project in site.data.projects -%}
| {{ project.inves }} | {{ project.protit }} | {{ project.amount }} | {{ project.agency }} |
{% endfor %}
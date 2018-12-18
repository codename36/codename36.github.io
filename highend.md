---
layout: page
title: HighEnd
permalink: /highend/
---
This document shows some of the high-end servers in different research labs at CSE, IITH. We are in the process of adding more computing systems to this fleet!

**NMS Group (NeWS Lab/Pranet Lab)**

| S.No. | Name | Specifications |
| ---- | ----- | ----- |
{% for data in site.data.nms -%}
| {{ forloop.index }} | {{ data.name }} | {{ data.spec }} |
{% endfor %}


**Data Science Group (VIGIL/DIG Labs)**

| S.No. | Name | Specifications |
| ---- | ----- | ----- |
{% for datas in site.data.science -%}
| {{ forloop.index }} | {{ datas.name }} | {{ datas.spec }} |
{% endfor %}

**Theory and Systems Group**

| S.No. | Name | Specifications |
| ---- | ----- | ----- |
{% for theory in site.data.theorys -%}
| {{ forloop.index }} | {{ theory.name }} | {{ theory.spec }} |
{% endfor %}

**Common Computer Infrastructure**

| S.No. | Name | Specifications |
| ---- | ----- | ----- |
{% for comm in site.data.common -%}
| {{ forloop.index }} | {{ comm.name }} | {{ comm.spec }} |
{% endfor %}
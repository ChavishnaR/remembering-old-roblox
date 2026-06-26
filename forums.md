---
layout: page
title: Roblox Forums
permalink: /forums/
---

## Roblox Forums

This section documents Roblox’s forum system, which functioned as a central hub for community discussion, feedback, support, and platform communication before being discontinued in 2017.

---
{% assign items = site.data.old-roblox | where_exp: "item", "item.subject contains 'Forums'" %}

{% for item in items %}

---

### {{ item.title }}

<img src="{{ '/objects/' | append: item.filename | relative_url }}" alt="{{ item.title }}" style="max-width:400px; width:100%; height:auto;">

**Date:** {{ item.date }}  
**Description:** {{ item.description }}  
**Source:** {{ item.source }}

---

{% endfor %}

---
layout: page
title: Roblox Forums
permalink: /forums/
---

## Roblox Forums

For many years, the Roblox Forums served as the platform's primary space for community discussion, feedback, technical support, and interaction between players and developers. They functioned as an important communication infrastructure where users shared ideas, reported issues, debated platform changes, and helped shape Roblox's growing community.

When the forums were discontinued in 2017, a significant part of Roblox's public history disappeared with them. Much of what remains today survives only through archived webpages, screenshots, community documentation, and preservation projects.

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

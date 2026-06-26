---
layout: page
title: Interface History
permalink: /interface/
--- 
## Roblox Interface History

This section documents the evolution of Roblox's website interface between 2005 and 2022. These artifacts show how the platform's homepage, login systems, navigation, and overall user experience changed over time as Roblox expanded from a small online building platform into a large-scale gaming ecosystem.

The collection illustrates how interface design influenced the ways users discovered games, created accounts, accessed platform features, and interacted with the Roblox community.


---

{% assign items = site.data.old-roblox | where_exp: "item", "item.subject contains 'Interface'" %}

{% for item in items %}

---

### {{ item.title }}

<img src="{{ '/objects/' | append: item.filename | relative_url }}" alt="{{ item.title }}" style="max-width:400px; width:100%; height:auto;">

**Date:** {{ item.date }}  
**Description:** {{ item.description }}  
**Source:** {{ item.source }}

---

{% endfor %}

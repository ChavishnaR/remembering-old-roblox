---
layout: page
title: Builders Club
permalink: /builders-club/
---
## Roblox Builders Club

This section documents Builders Club, Roblox's original premium membership system, which operated from 2007 until it was replaced by Roblox Premium in 2019. Builders Club offered users additional platform privileges, including daily Robux stipends, increased group limits, exclusive virtual items, and expanded creation features.

These artifacts illustrate how membership functioned as both a monetization system and a marker of status within the Roblox community.

---
{% assign items = site.data.old-roblox | where_exp: "item", "item.subject contains 'Builders Club'" %}

{% for item in items %}

---

### {{ item.title }}

<img src="{{ '/objects/' | append: item.filename | relative_url }}" alt="{{ item.title }}" style="max-width:400px; width:100%; height:auto;"> 

**Date:** {{ item.date }}  
**Description:** {{ item.description }}  
**Source:** {{ item.source }}

---

{% endfor %}

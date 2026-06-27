---
layout: page
title: Guest Accounts
permalink: /guest/
---
## Roblox Guest Accounts
Guest Accounts were one of Roblox's earliest access systems, allowing new users to explore games without creating an account. Introduced to lower barriers to entry, Guest Mode provided a limited version of the Roblox experience while restricting communication, customization, and many social features.

Although guests could not fully participate in the platform, they played an important role in introducing millions of players to Roblox and represented an early approach to balancing accessibility, identity, and user safety. Guest Accounts were permanently removed in 2017 as Roblox shifted toward mandatory account creation and stronger moderation systems.

---

{% assign items = site.data.old-roblox | where_exp: "item", "item.subject contains 'Guest'" %}

{% for item in items %}

---

### {{ item.title }}

<img src="{{ '/objects/' | append: item.filename | relative_url }}" alt="{{ item.title }}" style="max-width:400px; width:100%; height:auto;">

**Date:** {{ item.date }}  
**Description:** {{ item.description }}  
**Source:** {{ item.source }}

---

{% endfor %}

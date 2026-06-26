---
layout: page
title: Guest Accounts
permalink: /guest/
---
## Roblox Guest Accounts

This section documents Roblox Guest Mode and its role in early platform access, onboarding, and identity.

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

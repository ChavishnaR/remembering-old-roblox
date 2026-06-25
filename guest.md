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

![{{ item.title }}]({{ '/objects/' | append: item.filename | relative_url }})

**Date:** {{ item.date }}  
**Description:** {{ item.description }}  
**Source:** {{ item.source }}

---

{% endfor %}

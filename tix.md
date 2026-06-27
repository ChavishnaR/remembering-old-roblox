---
layout: page
title: Tix (Tickets Economy)
permalink: /tix/
---

## The Roblox Ticket (Tix) Economy

Tickets (Tix) were Roblox's original free virtual currency and one of the platform's earliest economic systems. Introduced in 2007 and discontinued in 2016, Tix allowed users to earn currency through daily activity and exchange it for Robux using the RoblEX exchange.

Tix shaped how players participated in Roblox by making items, customization, and parts of the platform accessible without requiring real-world purchases. Its removal marked a major shift toward a fully premium economy and fundamentally changed how value circulated throughout the platform.

---

{% assign items = site.data.old-roblox | where_exp: "item", "item.subject contains 'Tix'" %}

{% for item in items %}

### {{ item.title }}

<img src="{{ '/objects/' | append: item.filename | relative_url }}" alt="{{ item.title }}" style="max-width:400px; width:100%; height:auto;">

**Date:** {{ item.date }}

**Description:** {{ item.description }}

**Source:** {{ item.source }}

---

{% endfor %}

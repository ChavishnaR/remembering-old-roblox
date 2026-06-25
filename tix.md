---
layout: page
title: Tix (Tickets Economy)
permalink: /tix/
---

## The Roblox Ticket (Tix) Economy

Tickets (Tix) were Roblox's former free virtual currency. Introduced in 2007 and removed in 2016, Tix allowed users to earn currency through participation and exchange it for Robux through the RoblEX system. The removal of Tix marked a significant shift in Roblox's economy and monetization structure.

---

{% assign items = site.data.old-roblox | where_exp: "item", "item.subject contains 'Tix'" %}

{% for item in items %}

### {{ item.title }}

![{{ item.title }}](assets/img/{{ item.filename }})

**Date:** {{ item.date }}

**Description:** {{ item.description }}

**Source:** {{ item.source }}

---

{% endfor %}

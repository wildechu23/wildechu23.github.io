---
layout: page
title: Contact
permalink: /contact
---

{% for contact in site.author.contacts -%}
-  {{ contact.name }}: [{{ contact.handle }}]({{ contact.url }})
{% endfor %}
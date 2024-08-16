---
layout: page
title: Contact
permalink: /contact
---

If you have questions about my projects, want to collaborate on something exciting, or just want to network, feel free to reach out.

{% for contact in site.author.contacts -%}
-  {{ contact.name }}: [{{ contact.handle }}]({{ contact.url }})
{% endfor %}
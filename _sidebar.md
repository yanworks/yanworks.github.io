---
title: sidebar
---

{% for file in site.static_files %}
    {% if file.extname == ".md" and file.name != "ISSUE_TEMPLATE.md"  and file.name != "README.md"%}
*  [{{ file.name }}](#{{ file.path }})
	
    {% endif %}
{% endfor %} 
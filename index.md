---
year: 2022
author: Gayatri
layout: demo_template
---

# Session 1 - Day 1
This document was created in {{page.year}} by {{site.author_main}}.
{% for item in site.data.sample %}
- {{item.name}}, {{item.year}}
{% endfor %}

## Including a change to see how it displays.
1st session on doc-as-code TWT tribe
### Heading 1
I am using **Markdown** to reinstate what has been _taught_.
Today, I learnt:
-  How to create a repository
-  Naming the repository
-  Editing the repository

The sessions are sequential:
1. May 14 falls on Saturday
2. May 15 falls on Sunday

I would also like to try a hyperlink to [https://www.google.com/](google).
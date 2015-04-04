---
layout: page
title: Shelfmarks
permalink: /shelfmarks/
---

<ul>
    {% for book in site.books %}
    <li><a href="{{ site.baseurl }}{{ book.url }}">{{ book.shelfmark }}</a></li>
    {% endfor %}
</ul>

---
title: "Добро пожаловать на борт!"
lang: ru
ref: welcome
---

![Welcome](../images/welcome.jpg){:width="100%"}

Это то, что вы найдете в этом справочнике:

<!--
List all pages in the site which match the language of THIS page, sorted
by their "order" property, excluding THIS page.
 -->
{% assign pages=site.pages | where:"lang", page.lang | sort:"order" %}
<ul>
{% for p in pages %}
    {% if p.url != page.url %}
        <li>
            <a href="{{ p.url }}">{{ p.title }}</a><br/>
            {{ p.description }}
        </li>
    {% endif %}
{% endfor %}
</ul>
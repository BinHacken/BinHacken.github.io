---
layout: default
---

<article class="post">
    <p>
        {{ page.date | date: "%d.%m.%Y" }}
        {% if page.author %}
        von <i>{{ page.author }}</i>
        {% endif %}
    </p>

    {{ content }}

</article>

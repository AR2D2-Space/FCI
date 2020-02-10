---
layout: default
permalink: /
---

<h1>Latinoamérica 2020
</h1>

<div>
    {% for page in site.votaciones %}
    <div>
        <h3 style="display: inline-block">
            {{ page.name }}
        </h3> |
        <button style="border-radius: 5px">
            <a href="{{ page.url }}"
                style="text-decoration: none;">
                Ver más
            </a>
        </button>
    </div>
    {% endfor %}
</div>

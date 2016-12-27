---
layout: default
---

<div class="home">
    <ul class="posts">
        {% for data_tag in site.data.tags %}
        <li><a href="/tag/{{ tag.slug }}/">#{{ tag.name }}</a></li>
        {% endfor %}
    </ul>
</div>

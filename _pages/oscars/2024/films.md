---
layout: default
title: Oscars 2024 Films
permalink: "/oscars/2024/films"
comments: false
---
<pre> {{ site.data.streaming | jsonify }} </pre>
<div class="row justify-content-between">
<div class="col-md-8 pr-5">
    {% for film in site.data.oscars.2024.features %}
        <p>title: {{ film.title }}</p>
        {% if film.info.documentary %}
            <p>it's a documentary</p>
        {% endif %}
    {% endfor %}

</div>
</div>

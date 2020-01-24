---
layout: page
title: Course Materials
permalink: /materials/
---

<div style="width:100%; float: left">
    <div class="resource-pic-gallary">
        <h2>Course refrences</h2>
        {% for resource in site.materials reversed %}
        <h4>sabur bash</h4>  
        <div class="resource--image-cover-container">
            <img src="{{ resource.thumbnail | prepend: site.baseurl }}" class="resource--image-cover">
            <p><a href="{{resource.address}}">{{resource.title}}</a></p>
        </div>
        {% endfor %}
    </div>
</div>

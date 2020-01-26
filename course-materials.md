---
layout: page
title: Course Materials
permalink: /course-materials/
---

<div style="width:100%; float: left">
    <div class="resource-pic-gallary">
        {% for resource in site.course-materials reversed %} 
        <div class="resource--image-cover-container">
            <img src="{{ resource.thumbnail | prepend: site.baseurl }}" class="resource--image-cover">
            <p><a href="{{resource.address}}">{{resource.title}}</a></p>
            <br><br><br><br><br><br><br><br><br><br><br><br>
        </div>
        {% endfor %}
    </div>
</div>

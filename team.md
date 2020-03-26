---
layout: text_structure
title: L&S Team
---

<!-- loops though collections dispalys name  and link to the content of that collection-->

{% for teamMember in site.team %}
 <div class="wrapper">
    <h2><a href="{{teamMember.url}}">{{teamMember.name}}</a></h2>
    
 </div>
{% endfor %}
---
layout: post
category : elygestion
title : "nos références"
tagline: ""
tags : ["notre société","notre équipe","nos actifs gérés","actualités"]
---
{% include JB/setup %}
<div class="row"  style="color:#0d405e;">
{% for post in site.categories["references"] %}
       <div class="col-md-6 col-lg-4">
        <img src="{{ ASSET_PATH }}/references/{{post.image}}" class="img-responsive">
        <h4>{{post.title}}</h4>
    <br><br>
    </div>
{% endfor %}
</div>

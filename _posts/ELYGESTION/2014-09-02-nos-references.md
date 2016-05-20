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
        <img src="{{ ASSET_PATH }}/references/{{post.image}}" class="img-responsive" alt="{{post.title}}">
    <br><br>
    </div>
{% endfor %}
<h3 style="text-align=center, margin-top=15px"> ...et de nombreuses autres références </h3>
</div>

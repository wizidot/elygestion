---
layout: post
category : actualites
title : "actualités"
tagline: ""
tags : ["notre société","notre équipe","nos actifs gérés","actualités"]
---
{% include JB/setup %}

<div class="row">
{% for post in site.categories["actus"] %}
       <div class="col-md-6 col-lg-4">
        <a href="{{post.url}}"><img src="{{ ASSET_PATH }}/actus/{{post.image}}" class="img-responsive">
        <b>{{post.title}}</b>
    </a><br><br>
    </div>
{% endfor %}
</div>

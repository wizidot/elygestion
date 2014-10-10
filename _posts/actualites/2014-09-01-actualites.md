---
layout: post
category : actualites
title : "actualités"
tagline: ""
tags : ["notre société","notre équipe","nos actifs gérés","nos références"]
---
{% include JB/setup %}

<div class="row">
{% for post in site.categories["actus"] %}
       <div class="col-md-6 col-lg-4">
        <a href="{{BASE_PATH}}{{post.url}}"><img src="{{ ASSET_PATH }}/actus/{{post.image}}" class="img-responsive">
        <h4>{{post.title}}</h4>
    </a><br><br>
    </div>
{% endfor %}
</div>

---
layout: page
permalink: index.html
---
<head>
<link rel="stylesheet" type="text/css" href="Assets/css/Unified_Style.css">
</head>

# Lecture Notes
## 美国高中数学建模 | HiMCM

<div>
{% for post in site.tags["HiMCM"] %}
    <a href="{{site.baseurl}}{{ post.url }}">
        <div class="card">
            <div class="title_container">
                <h4>{{post.title}}</h4>
            </div>
            <div class="container">
                {{post.excerpt}}
            </div>
        </div>
    </a>
    <div style="width: 100%; height: 0.6em"></div>
{% endfor %}
</div>
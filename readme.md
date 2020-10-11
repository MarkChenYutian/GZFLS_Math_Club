---
layout: page
permalink: index.html
---
<head>
<link rel="stylesheet" type="text/css" href="Asset/css/Unified_Style.css">
</head>


## About This Site

This site is maintained by Mark Chen (*markyutianchen@gmail.com*). Currently the site is in the <mark>Testing phase</mark>[^1] and here are the features in current plan:
* Resource Sharing - e-books about Computer Science and Mathematics.
* Article Sharing - Articles about Machine Learning & Neural Network, Bitcoin & Block Chain
* Code Sharing - Implementation of algorithms in Python3 etc.

> Due to some reasons, accessing such a site built on GitHub may need VPN.

----------

## My Articles
### Neural Network and Machine Learning - *2019 Computer Science 2*

<center>
<img src="https://markchenyutian.github.io/Markchen_Blog/Asset/CS2Banner.png" height=120>
</center>

*点击卡片阅读全文*

<div>
{% for post in site.tags["Neural_Network"] %}
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

<div>
{% for post in site.tags["Machine_Learning"] %}
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

### Blockchain and Cryptocurrency - *2020 Computer Science 2*

<div>
{% for post in site.tags["Cryptocurrency"] %}
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

### Algorithm Notes

<div>
{% for post in site.tags["Algorithm"] %}
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

<div style="width: 100%; height: 0.6em"></div>
<div class="card" onclick="window.open('https://markchenyutian.github.io/Markchen_Blog/2020/10/04/USACO-Analysis-Page.html');">
  <div class="title_container">
    <h4>USACO 金组分析专栏  |  USACO Gold Division Problem Analysis</h4>
  </div>
</div>

<br>

### Others
<div>
{% for post in site.tags["Others"] %}
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

----------

## Computer Science 3 Homework & Notes

<center><img src="https://markchenyutian.github.io/Markchen_Blog/Asset/JS.png" height=100></center>
<div style="width: 100%; height: 1em"></div>

<!--The 'content_block' calss is the area for each week of Javascript-->
<div class="content_block">
<h4>Week 1 - Variable and Basic functions</h4>
<div style="width: 100%; height: 1em"></div>
<body>
<button onclick='window.open("https://markchenyutian.github.io/Markchen_Blog/2020/09/10/Homework01.html");'>
    Homework for Week 1
</button>
</body>
<div style="width: 100%; height: 1em"></div>
<p>
There are 6 primitive types in JavaScript - <code>Number, String, Boolean, Undefined, Symbol and bigint</code>.
There's only 1 reference type - Object.
All the things enclosed by <code>{}</code> are objects, including function, etc.
There are three functions that can interact with users in browser - <code>alert</code>, <code>prompt</code> and <code>confirm</code>
<div style="width: 100%; height: 0.5em"></div>
<code>alert</code> will give out a small pop-out window on the top of browser to notify user with some information
<div style="width: 100%; height: 0.5em"></div>
<code>prompt</code> will return a String that is typed by the User. If user press "cancel", it will simplly return <code>null</code>. A default String can be setup for the pop-up window.
<div style="width: 100%; height: 0.5em"></div>
<code>confirm</code> will return a Boolean, if user press "ok", return true, otherwise, return "false".
</p>
</div>

<div style="width: 100%; height: 1em"></div>

<div class="content_block">
  <h4>Week 2 - If, else, array, and function</h4>
  <div style="width: 100%; height: 0.5em"></div>
  <button onclick='window.open("https://markchenyutian.github.io/Markchen_Blog/2020/09/18/Homework02.html");'>
    Homework for Week 2
  </button>
  &emsp;
  <button onclick='window.open("https://markchenyutian.github.io/Markchen_Blog/2020/09/16/Javascript-notes-week2.html");'>
    JavaScript Week 2 Note
  </button>
</div>

<div style="width: 100%; height: 1em"></div>

<div class="content_block">
<h4>Week 3 - Loop in Javascript</h4>
  <div style="width: 100%; height: 0.5em"></div>
  <button onclick='window.open("https://markchenyutian.github.io/Markchen_Blog/2020/09/25/Homework03.html");'>
    Homework for Week 3
  </button>
  &emsp;
  <button onclick='window.open("https://markchenyutian.github.io/Markchen_Blog/2020/09/22/Javascript-notes-week3.html");'>
    Javascript Week 3 Note
  </button>
</div>
<br>

----------

[^1]: So some hyperlink may not function properly or the website will be quite ugly
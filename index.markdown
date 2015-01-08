---
title: '中国地方DB勉強会'
layout: default
---

<header class="post-header">
<h1>{{ page.title }}</h1>
隔月程度でDBに関する勉強会を中国地方で開催しています。

主催：[PostgreSQLユーザ会中国支部](http://www.postgresql.jp/branch)
</header>

<article class="post-content">

## 第七回 中国地方DB勉強会 in 松江

2015年1月31日(土)

* [第七回　中国地方DB勉強会](/events/event-007.html)
* [doorkeeper](http://dbstudychugoku.doorkeeper.jp/events/18385)

やってまいりました、松江でございます。

</article>


<footer>
<article class="post-content">

## これまでのイベント

<ul class="posts">
{% for post in site.posts reversed limit:10 %}
  <li><span>{{ post.date | date: "%Y-%m-%d" }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>

## ML

[中国地方DB勉強会ML Google Group](https://groups.google.com/forum/#!forum/dbstudychugoku)

</article>
</footer>

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

## 第九回 中国地方DB勉強会 in 米子

2015年6月6日(土) 13:00 - 18:00

* [第九回　中国地方DB勉強会](/events/event-009.html)
* [doorkeeper](https://dbstudychugoku.doorkeeper.jp/events/23735)

## MyNA・JPUG合同DB勉強会 in 東京

2015年6月26日（金） 13:30 - 18:30

* [MyNA・JPUG合同DB勉強会 in 東京](/events/event-tokyo-001.html)
* [doorkeeper](https://dbstudychugoku.doorkeeper.jp/events/25804)

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

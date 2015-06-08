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

## MyNA・JPUG合同DB勉強会 in 東京

2015年6月26日（金） 13:30 - 18:30

* [MyNA・JPUG合同DB勉強会 in 東京](/events/tokyo-001.html)
* [doorkeeper](https://dbstudychugoku.doorkeeper.jp/events/25804)

## 第10回 中国地方DB勉強会 in 岡山 ～日本AWSユーザ会・PostgreSQLユーザ会(JAWS-UG・JPUG) 合同勉強会～

2015年7月18日 (土) 10:00 - 18:30

* [第10回 中国地方DB勉強会 in 岡山 ～日本AWSユーザ会・PostgreSQLユーザ会(JAWS-UG・JPUG) 合同勉強会～](/events/event-010.html)
* [doorkeeper](https://dbstudychugoku.doorkeeper.jp/events/26563)

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

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

## 第五回　中国地方DB勉強会 in 広島

2014年9月21日

* [第五回　中国地方DB勉強会](/events/event-005.html)
* [事前申し込み - doorkeeper](http://dbstudychugoku.doorkeeper.jp/events/14008)


第5回は広島市で商用、OSS入り乱れてそれぞれのトラブルシューティングを題材にセッションを行っていただきます。
また前日に同会場で[オープンソースカンファレンス2014@広島](https://www.ospn.jp/osc2014-hiroshima)も開催されます。
NOSQLから商用DBまで現場で一番知りたい内容にアプローチします。

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

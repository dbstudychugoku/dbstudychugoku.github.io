---
title: '中国地方DB勉強会'
layout: default
---

<header class="post-header" markdown="1">
# {{ page.title }}
隔月程度でDBに関する勉強会を中国地方で開催しています。

主催：[PostgreSQLユーザ会中国支部](http://www.postgresql.jp/branch)
</header>

<article class="post-content" markdown="1">
{% include next.md %}
</article>

<footer>
<article class="post-content">

<h2>これまでのイベント</h2>

<ul class="posts">
{% for post in site.posts reversed limit:10 %}
  <li><span>{{ post.date | date: "%Y-%m-%d" }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>

<h2>ML</h2>

<a href="https://groups.google.com/forum/#!forum/dbstudychugoku">中国地方DB勉強会ML Google Group</a>

</article>
</footer>

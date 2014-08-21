---
title: '中国地方DB勉強会'
layout: default
---

隔月程度でDBに関する勉強会を中国地方で開催しています。

主催：PostgreSQLユーザ会中国支部

# 次のイベント

## 第五回　中国地方DB勉強会 in 広島

* [第五回　中国地方DB勉強会](/events/event-005.html)
* [事前申し込み - doorkeeper](http://dbstudychugoku.doorkeeper.jp/events/14008)


第5回は広島市で商用、OSS入り乱れてそれぞれのトラブルシューティングを題材にセッションを行っていただきます。
また前日に同会場で[オープンソースカンファレンス2014@広島](https://www.ospn.jp/osc2014-hiroshima)も開催されます。
NOSQLから商用DBまで現場で一番知りたい内容にアプローチします。

[中国地方DB勉強会ML Google Group](https://groups.google.com/forum/#!forum/dbstudychugoku)

# これまでのイベント

<ul class="posts">
{% for post in site.posts reversed limit:10 %}
<li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>

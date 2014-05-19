---
title: '中国地方DB勉強会'
layout: default
---

隔月程度でDBに関する勉強会を中国地方で開催しています。

主催：PostgreSQLユーザ会中国支部

# 次のイベント

## 第四回　中国地方DB勉強会 in 岡山（予定）

* [第四回　中国地方DB勉強会](http://localhost:4000/events/event-004.html)
* [事前申し込み - doorkeeper](http://dbstudychugoku.doorkeeper.jp/events/11642)


第４回は岡山市で実行計画についてのハンズオンを予定しています。
PostgreSQL、MySQLを題材にする予定です。
他のDBの希望がありましたらML等でご連絡いただけますようにお願いします。

[中国地方DB勉強会ML Google Group](https://groups.google.com/forum/#!forum/dbstudychugoku)


# これまでのイベント

<ul class="posts">
{% for post in site.posts reversed limit:10 %}
<li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>

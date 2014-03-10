---
title: '中国地方DB勉強会'
layout: default
---

隔月程度でDBに関する勉強会を中国地方で開催しています。

主催：PostgreSQLユーザ会中国支部

# 次のイベント

## [第3回　中国地方DB勉強会 in 福山](http://dbstudychugoku.doorkeeper.jp/events/9698)

第３回は福山市で午前はセミナー形式、午後からはハンズオンやディスカッションを予定しています。

### 開催日

2014/04/12 (土) 10:00 - 17:00

### 開催場所

福山市本町1番35号 [福山市市民参画センター](http://www.city.fukuyama.hiroshima.jp/soshiki/shiminsankaku/)

###  開催内容

セミナーの内容は

1. AWSのRDS for PostgreSQL&Linux上でのHA構成のデモ 講師：曽根
1. 負荷分散と仕様変更に耐えるためのDB設計の話 講師：三谷さん

を予定しています。

午後からは

1. チームに分かれてテーマに対してDB設計ハンズオン
1. みんなでKPTなどのディスカッション+DBに関わるQ&A

を予定しています。

[詳細や事前申し込みはDoorkeeper からお願いします。](http://dbstudychugoku.doorkeeper.jp/events/9698)

<a class="doorkeeper-registration-widget" href="http://dbstudychugoku.doorkeeper.jp/events/9698"> 第3回　中国地方DB勉強会 in 福山</a><script src="http://widgets.doorkeeper.jp/w/widget.js"></script>


# これまでのイベント

<ul class="posts">
{% for post in site.posts reversed limit:10 %}
<li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>

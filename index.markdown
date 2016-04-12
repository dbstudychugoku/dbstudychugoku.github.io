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

{% for post in site.posts %}
  {% capture event_date %}{{ post.path | slice: 7,10 }}{% endcapture %}
  {% capture event_previous_date %}{{ post.previous.path | slice: 7,10 }}{% endcapture %}
  {% capture this_year %}{{ event_date |date: "%Y" }}{% endcapture %}
  {% capture next_year %}{{ event_previous_date | date: "%Y" }}{% endcapture %}

  {% if forloop.first %}
    <h3>{{ this_year}}年</h3>
	<ul class="posts">
  {% endif %}
    <li><span>{{ event_date | date: "%Y-%m-%d" }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>

  {% if forloop.last %}
    </ul>
  {% else %}
    {% if this_year != next_year %}
    </ul>
    <h3>{{ next_year}}年</h3>
	<ul class="posts">
    {% endif %}
  {% endif %}
{% endfor %}
</ul>

<h2>ML</h2>

<a href="https://groups.google.com/forum/#!forum/dbstudychugoku">中国地方DB勉強会ML Google Group</a>

</article>
</footer>

---
layout: default
title: Home
---


<br><br>


안녕하세요. James' Dev Log에 오신 것을 환영합니다.

이곳은 제가 공부한 것들에 대한 기록들이 남을 블로그입니다.

이 블로그를 봐주시는 분들에게도 도움이 되었으면 하는 바람입니다.

궁금한 부분이나 피드백, 혹은 고쳐야 할 부분이 있다면 주저하지 말고 연락주세요!


<br><br><br>

Hi there! Welcome to James' Dev Log.

This is a place where I keep things that I study.

Hopefully, they could be helpful to you too!

I appreciate all types of feedbacks so don't hesitate!

<!--
<div class="posts">
  {% for post in paginator.posts %}
  <div class="post">
    <h1 class="post-title">
      <a href="{{ post.url | absolute_url }}">
        {{ post.title }}
      </a>
    </h1>

    <span class="post-date">{{ post.date | date_to_string }}</span>

    {{ post.content }}
  </div>
  {% endfor %}
</div>

<div class="pagination">
  {% if paginator.next_page %}
    <a class="pagination-item older" href="{{ paginator.next_page_path | absolute_url }}">Older</a>
  {% else %}
    <span class="pagination-item older">Older</span>
  {% endif %}
  {% if paginator.previous_page %}
    {% if paginator.page == 2 %}
      <a class="pagination-item newer" href="{{ '/' | absolute_url }}">Newer</a>
    {% else %}
      <a class="pagination-item newer" href="{{ paginator.previous_page_path | absolute_url }}">Newer</a>
    {% endif %}
  {% else %}
    <span class="pagination-item newer">Newer</span>
  {% endif %}
</div>
-->
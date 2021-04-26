---
layout: page
title: Member
permalink: /member/
---

참여자

|  이름                | github                        | email              |  
|:--- | :--- | :--- |  
{% for member in site.data.members %}
| {{ member.name }}             | <a href="https://github.com/{{ member.github }}">{{ member.github }}</a>            | <a href="mailto:{{ member.email }}">{{ member.email }}</a> |  
{% endfor %}

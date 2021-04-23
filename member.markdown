---
layout: page
title: Member
permalink: /member/
---
<table boder=0 cellspacing="5" cellpadding="0" bgcolor=silver>
<tr bgcolor=f2f2f2 HEIGHT=60><td width=100>성함</td><td width=150>Github</td><td width=250>이메일</td></tr>
{% for member in site.data.members %}
<tr><td bgcolor=white>{{ member.name }}</td>
	  <td><a href="https://github.com/{{ member.github }}">{{ member.github }}</a></td>
	  <td><a href="mailto:{{ member.email }}">{{ member.email }}</a></td></tr>
{% endfor %}
</table>
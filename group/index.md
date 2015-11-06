---
layout: page
title: Group
mainpage: true
weight: 3
permalink: /group/
---

## Steering Committee ##

[**Walter Jetz**](http://jetzlab.yale.edu/){: target="blank" }  
Yale University  
[<span class="glyphicon glyphicon-envelope" aria-hidden="true"></span> Email](mailto:walter.jetz@yale.edu)

[**Eva Spehn**](https://botanik.unibas.ch/en/staff/profile/person/spehn/){: target="blank" }  
Universität Basel   
[<span class="glyphicon glyphicon-envelope" aria-hidden="true"></span> Email](mailto:eva.spehn@scnat.ch)

[**Christopher Trisos**](https://www.sesync.org/users/ctrisos){: target="blank" }  
SESYNC / Yale    
[<span class="glyphicon glyphicon-envelope" aria-hidden="true"></span> Email](mailto:ctrisos@sesync.org)


## Participants ##

First name | Last name | Affiliation | Email
-- | -- | -- | --  {% for member in site.data.participants2015 %}
{{ member.first }} | **{{ member.last }}** | {{ member.affiliation }} | [{{ member.email }}](mailto:{{ member.email }}){% endfor %}

{% comment %}
<table>
  <tr>
    <th>First name</th>
    <th>Last name</th>
    <th>Affiliation</th>
    <th>Email</th>
  </tr>
  {% for member in site.data.participants2015 %}
  <tr>
  <td>{{ member.first }}</td>
  <td><strong>{{ member.last }}</strong></td>
  <td>{{ member.affiliation }}</td>
  <td><a href="mailto:{{ member.email }}">{{ member.email }}</a></td>
  </tr>
  {% endfor %}
</table>
{% endcomment %}

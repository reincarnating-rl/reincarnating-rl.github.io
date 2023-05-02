---
layout: page
title: Schedule
permalink: /schedule/
description: Official schedule.
nav: true
horizontal: true
---

## The workshop will take place on May 4th during ICLR 2023 in Kigali, Rwanda.

Schedule: [https://iclr.cc/virtual/2023/workshop/12833](https://iclr.cc/virtual/2023/workshop/12833)

<table style="width:100%">
        <tr>
        <th style="text-align:right; width:25%">Time (UTC)</th>
        <th style="text-align:left; width: 75%">Session</th>
        </tr>
    {% for time in site.data.schedule %}
        <tr>
        <td style="text-align:right">{{ time.start }} - {{ time.end }} </td>
        <td style="text-align:left"><strong>{{ time.categories}}</strong> {{ time.title }}<br/>{{ time.desc}}</td>
        </tr>
    {% endfor %}
</table>

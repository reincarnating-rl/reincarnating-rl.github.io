---
layout: page
title: Panels
permalink: /panels/
description: We plan to organize 2 panel discussions on the topics mentioned below.
nav: true
horizontal: false
---

{%- for panel in site.panels %}

<h1 id="{{ panel.anchor }}">{{ panel.name }}<a href='/panels#{{ panel.anchor }}'><div class="anchor"></div></a></h1>

**Moderator:** {{ panel.moderator }}

{{ panel.description }}

### Panelists

<table style="width:100%">
    {% for panelist in panel.panelists %}
  <tr>
        <td style="text-align:center; width: 25%">
          <img class="thumbnail" src="../{{ panelist.img_path }}" alt="">
        </td>
        <td style="text-align:left; width: 75%">
          <h4><a href="{{ panelist.website }}"> {{ panelist.name }}</a> - {{ panelist.affiliations }}</h4>{{panelist.bio}}
        </td>
  </tr>
    {% endfor %}
</table>

{%- endfor %}

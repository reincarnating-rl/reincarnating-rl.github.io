---
layout: page
title: Talks
permalink: /talks/
description: Invited speakers
nav: true
horizontal: false
---


{% for speaker in site.speakers %}
<table style="width:100%; margin-top: 5em">
  <tr style='border-top: 0px;'>
    <td style="width: 25%; border-top: 0px;">
      <h2 style="margin-top: -5px; margin-bottom: -5px">
      <a href='/talks#{{ speaker.anchor }}'><div class="anchor"></div></a>
        <a href="{{ speaker.website }}">{{ speaker.name }}</a>
      </h2>
    </td>
    <td style="width: 75%; border-top: 0px;"> 
      <h2 style="margin-top: -5px; margin-bottom: -5px" id="{{ speaker.anchor }}">
        {{ speaker.title}}
      </h2>
    </td>
  </tr>
  <tr style='border-top: 0px;'>
     <td style='border-top: 0px;' colspan=2>
<!--       <h5>{{ speaker.time }}, 29th April 2022 (UTC)</h5> -->
     </td>
  </tr>
  <tr>
    <td colspan=2>
      {{speaker.abstract}}
    </td>
  </tr>
  <tr>
    <td >
      <img class="thumbnail" src="../{{ speaker.img_path }}" alt="">
    </td>
    <td style="text-align:left;">
      {{speaker.bio}}
    </td>
  </tr>

</table>
{%- endfor %}

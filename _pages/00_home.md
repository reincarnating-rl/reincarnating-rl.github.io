---
layout: about
permalink: /
title: ICLR2023
description: To address the inefficiencies of tabula rasa RL and help unlock the full potential of deep RL, this workshop would focus on the alternative paradigm of leveraging prior computational work, referred to as reincarnating RL, to accelerate training across design iterations of an RL agent or when moving from one agent to another. 
nav: true
horizontal: false
---

This in-person workshop at ICLR 2023 aims to bring further attention to the emerging paradigm of reusing prior computation in RL, which we refer to as reincarnating RL, discuss potential benefits and real-world applications, discuss its current limitations and challenges, and come up with concrete problem statements and evaluation protocols for the research community to work on.

<figure>
  <center> <img src="https://reincarnating-rl.github.io/assets/img/RRL.gif" width="80%"  /> </center>
<div style='text-align: center;'><small> Tabula rasa RL vs. Reincarnating RL. While tabula rasa RL focuses on learning from scratch, RRL is based on the premise of reusing prior computational work (e.g., prior learned agents) when training new agents or improving existing agents. Source: <a href="https://ai.googleblog.com/2022/11/beyond-tabula-rasa-reincarnating.html">Google AI Blog </a>. </small> </div>
</figure>

**Why?** Reusing prior computation can further democratize RL research by allowing the broader community to tackle complex RL problems without requiring excessive computational resources. Furthermore, real-world RL use cases are common in scenarios where prior computational work is available, making reincarnating RL important to study. Additionally, reincarnating RL can enable a benchmarking paradigm where researchers continually improve and update existing trained agents, especially on problems where improving performance has real-world impact. However, except for some large-scale RL efforts with ad hoc approaches, the RL community has only recently started focusing on reincarnating RL as a research problem in its own right. 


# [Call for papers](/call-for-papers)

Submission Site: <a href="??"> TBD </a>


# [Speakers](/talks)

<table style="width:75%">
  <tr>
    {% for speaker in site.speakers limit:4 %}
        <td style="text-align:center"><img class="thumbnail" src="{{ speaker.img_path }}" alt=""></td>
    {% endfor %}
  </tr>
  <tr>
    {% for speaker in site.speakers limit:4 %}
        <td style="text-align:center"><a href="/talks#{{ speaker.anchor}}"> {{ speaker.name }}</a> <br> {{ speaker.affiliations }} </td>
    {% endfor %} 
  </tr>
  <tr>
    {% for speaker in site.speakers offset:4 %}
        <td style="text-align:center"><img class="thumbnail" src="{{ speaker.img_path }}" alt=""></td>
    {% endfor %}
  </tr>
  <tr>
    {% for speaker in site.speakers offset:4 %}
        <td style="text-align:center"><a href="/talks#{{ speaker.anchor}}"> {{ speaker.name }}</a> <br> {{ speaker.affiliations }} </td>
    {% endfor %} 
  </tr>
</table>

# [Panels](/panels)

{%- for panel in site.panels %}

## [{{ panel.name }}](/panels#{{ panel.anchor }})

<table style="width:75%">
  <tr>
    {% for panelist in panel.panelists limit:3 %}
        <td style="text-align:center"><img class="thumbnail" src="{{ panelist.img_path }}" alt=""></td>
    {% endfor %}
  </tr>
  <tr>
    {% for panelist in panel.panelists limit:3 %}
        <td style="text-align:center"><a href="{{ panelist.website }}"> {{ panelist.name }}</a> <br> {{ panelist.affiliations }} </td>
    {% endfor %} 
  </tr>
  <tr>
    {% for panelist in panel.panelists offset:3 %}
        <td style="text-align:center"><img class="thumbnail" src="{{ panelist.img_path }}" alt=""></td>
    {% endfor %}
  </tr>
  <tr>
    {% for panelist in panel.panelists offset:3 %}
        <td style="text-align:center"><a href="{{ panelist.website }}"> {{ panelist.name }}</a> <br> {{ panelist.affiliations }} </td>
    {% endfor %} 
  </tr>
</table>

{%- endfor %}

## RRL Benchmarking Track Supporters

Please see [call for papers](/call-for-papers) for more details about the special track on benchmarking reincarnating RL.

<table style="width:75%">
  <tr>
    {% for organizer in site.st_organizers limit:3 %}
        <td style="text-align:center"><img class="thumbnail" src="{{ organizer.img_path }}" alt=""></td>
    {% endfor %}
  </tr>
  <tr>
    {% for organizer in site.st_organizers limit:3 %}
        <td style="text-align:center"><a href="{{ organizer.website }}"> {{ organizer.name }}</a> <br> {{ organizer.affiliations }} </td>
    {% endfor %} 
  </tr>
  <tr>
    {% for organizer in site.st_organizers offset:3 %}
        <td style="text-align:center"><img class="thumbnail" src="{{ organizer.img_path }}" alt=""></td>
    {% endfor %}
  </tr>
  <tr>
    {% for organizer in site.st_organizers offset:3 %}
        <td style="text-align:center"><a href="{{ organizer.website }}"> {{ organizer.name }}</a> <br> {{ organizer.affiliations }} </td>
    {% endfor %} 
  </tr>
</table>


# Organizers

<table style="width:75%">
  <tr>
    {% for organizer in site.organizers limit:3 %}
        <td style="text-align:center"><img class="thumbnail" src="{{ organizer.img_path }}" alt=""></td>
    {% endfor %}
  </tr>
  <tr>
    {% for organizer in site.organizers limit:3 %}
        <td style="text-align:center"><a href="{{ organizer.website }}"> {{ organizer.name }}</a> <br> {{ organizer.affiliations }} </td>
    {% endfor %} 
  </tr>
  <tr>
    {% for organizer in site.organizers offset:3 %}
        <td style="text-align:center"><img class="thumbnail" src="{{ organizer.img_path }}" alt=""></td>
    {% endfor %}
  </tr>
  <tr>
    {% for organizer in site.organizers offset:3 %}
        <td style="text-align:center"><a href="{{ organizer.website }}"> {{ organizer.name }}</a> <br> {{ organizer.affiliations }} </td>
    {% endfor %} 
  </tr>
</table>

For any queries, please reach out to the organizers at <a href="mailto:reuserlworkshop@googlegroups.com"> reuserlworkshop@googlegroups.com  </a>.

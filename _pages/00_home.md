---
layout: about
permalink: /
title: ICLR2023
description: TODO
nav: true
horizontal: false
---

Reusing prior computation can further democratize RL research by allowing the broader community to tackle complex RL problems without requiring excessive computational resources. Furthermore, real-world RL use cases are common in scenarios where prior computational work is available, making reincarnating RL important to study. Additionally, reincarnating RL can enable a benchmarking paradigm where researchers continually improve and update existing trained agents, especially on problems where improving performance has real-world impact. However, except for some large-scale RL efforts with ad hoc approaches, the RL community has only recently started focusing on reincarnating RL as a research problem in its own right. 

This workshop aims to bring further attention to this emerging paradigm of reusing prior computation in RL, discuss potential benefits and real-world applications, discuss its current limitations and challenges, and come up with concrete problem statements and evaluation protocols for the research community to work on.

<figure>
    <center><img src="https://reincarnating-rl.github.io/assets/img/RRL.gif" style="width:70%"; /></center>
    <figcaption style='text-align: center'><small> Tabula rasa RL vs. Reincarnating RL (RRL). While tabula rasa RL focuses on learning from scratch, RRL is based on the premise of reusing prior computational work (e.g., prior learned agents) when training new agents or improving existing agents, even in the same environment. Source: <a href="[https://ai.googleblog.com/2020/04/an-optimistic-perspective-on-offline.html](https://ai.googleblog.com/2022/11/beyond-tabula-rasa-reincarnating.html)">Google AI Blog </a></small></figcaption>
</figure>


# [Call for papers](/call-for-papers)

We invite two types of papers -- opinion papers (up to 4 pages) and technical papers (up to 9 pages excluding references and appendix) about reusing prior computation in RL. In particular, we are interested in bringing together researchers and practitioners to discuss questions on theoretical, empirical and practical aspects of reusing prior computation in RL, including but not limited to:

- Developing methods for accelerating RL training depending on type or combination of prior computation available:
  -  Learned policies
  -  Offline datasets 
  -  Pretrained dynamics models
  -  Foundation models or LLMs
  -  Pretrained representations
  -  Learned Skills
- Challenges for dealing with suboptimality of prior computational work
- Democratizing large-scale RL problems by releasing prior computation and formalizing the corresponding reincarnating RL setting.
- Algorithmic decisions and challenges associated with suboptimality of prior computational work
- Evaluation protocols, frameworks and standardized benchmarks for leveraging prior computation in RL research
- Real-world / Large-scale applications of reincarnating RL
- Properties of prior computational work needed to guarantee optimality of reincarnating RL methods
- Connection to transfer learning, lifelong learning and data-driven simulation.

Submission Site: <a href="??"> ?? </a>


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

For any queries, please reach out to the organizers at <a href="mailto:ml-eval-iclr2022@googlegroups.com"> ml-eval-iclr2022@googlegroups.com </a>.

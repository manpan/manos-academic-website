---
layout: archive
title: "Team"
permalink: /team/
author_profile: true
---

The [Internet of Things and Security Research Centre](https://www.gre.ac.uk/research/groups/isec) with an annual research expenditure exceeding £1M, comprises a team of 35 faculty members, postdocs, and PhD researchers. Our research focuses on securing smart digital environments, including but not limited to smart buildings, emergency services, and health, by combining scientific excellence with real-world implementation.

Our center collaborates with industry, public sector, and academic partners to conduct cutting-edge research in various areas. Our current research areas include Communications and Self-aware systems, IoT Security, Online Harms, Cyber-Physical Security, AI for Security, Threat Modelling, Formal Methods of Security, Cyber Risk Management, Cyber Forensics, Security Economics, Emergency Management, and Privacy. Through these research areas, we aim to develop innovative solutions to address the ever-evolving challenges in securing the digital landscape.

## <span style="color:#2979ab;">Faculty</span> 

{% for member in site.data.team %}
  <hr>
  <div class="team-member">
    <img src="{{ member.image }}" alt="{{ member.name }}">
    <h3>{{ member.name }}</h3>
    <p>{{ member.role }}</p>
    <p>{{ member.bio }}</p>
    {% if member.google_scholar %}
      <a href="{{ member.google_scholar }}"><i class="ai ai-google-scholar"></i></a>
    {% endif %}
     {% if member.www %}
      <a href="{{ member.www }}">www</a>
    {% endif %}
    {% if member.linkedin %}
      <a href="{{ member.linkedin }}"><i class="fab fa-linkedin"></i></a>
    {% endif %}
    {% if member.twitter %}
      <a href="https://twitter.com/{{ member.twitter }}"><i class="fab fa-twitter"></i></a>
    {% endif %}
    {% if member.email %}
      <a href="mailto:{{ member.email }}"><i class="far fa-envelope"></i></a>
    {% endif %}
  </div>
{% endfor %}

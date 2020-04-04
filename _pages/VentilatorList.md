---
layout: archive
permalink: /VentilatorList/
title: "Ventilator Data by State"
author_profile: true
---
{{ content }}
<ul >
  {% for block in site.data.VentilatorList_ByState.VentList %}
    <a href=”{{ block.url | prepend: site.baseurl }}”>
      <li>
        <div class=”state">
          {{ block.state }}
        </div>
        <div class=”numVentilators">
          {{ block.numVentilators }}
        </div>
        <div class=”source">
          {{ block.source }}
        </div>
        <div class=”lastUpdated">
          {{ block.lastUpdated }}
        </div>
      </li>
    </a>
  {% endfor %}
</ul>

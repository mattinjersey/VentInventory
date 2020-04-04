---
layout: archive
title: "Ventilator List"
permalink: /VentilatorList/
header:
 image: "/images/Vent2.jpg"
---

<ul>
  {% for block in site.data.VentilatorList_ByState.VentList %}
      <li>
          {{ block.state }}
          {{ block.numVentilators }}
      </li>
  {% endfor %}
</ul>

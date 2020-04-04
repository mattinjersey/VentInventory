---
layout: archive
title: "Ventilator List"
permalink: /VentilatorList/
header:
 image: "/images/Vent2.jpg"
---

<ul class=”VentList">
  {% for block in site.data.VentialatorList_ByState.VentList %}
      <li>
        <div class=”state">
          {{ block.state }}
        </div>
        <div class=”numVentilators">
          {{ block.numVentilators }}
        </div>
      </li>
  {% endfor %}
</ul>

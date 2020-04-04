---
layout: archive
title: "Ventilator List"
permalink: /VentilatorList/
header:
 image: "/images/Vent2.jpg"
---

| State |  Number ventilators |
  {% for block in site.data.VentilatorList_ByState.VentList %}
      |{{ block.state }}|  {{ block.numVentilators }}|
  {% endfor %}

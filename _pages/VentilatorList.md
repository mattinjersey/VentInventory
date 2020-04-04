---
layout: archive
permalink: /VentilatorList/
title: "Ventilator Data by State"
author_profile: true
---

  {% for block in site.data.VentilatorList_ByState.VentList %}
        State:  {{ block.state }}
        numVentilators:  {{ block.numVentilators }}
        Data Source:  {{ block.source }}
        Last Updated:  {{ block.lastUpdated }}

  {% endfor %}

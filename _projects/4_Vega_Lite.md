---
name: More Advanced Vega Lite Plots
tools: [Python, HTML, vega-lite,Altair]
image: assets/pngs/cars.png
description: This is vega-lite from week 13 and 14 lectures!
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---


# Simple line plot with “for free” interactivity
## first a "simple" line plot with Altair:

<vegachart schema-url="{{ site.baseurl }}/assets/json/buildings_sqft.json" style="width: 100%"></vegachart>

## "Melting" data for more complex plots
<vegachart schema-url="{{ site.baseurl }}/assets/json/buildings_tooltip.json" style="width: 100%"></vegachart>

## Adding a dropdown interactive
<vegachart schema-url="{{ site.baseurl }}/assets/json/buildings_dropdown.json" style="width: 100%"></vegachart>


<!-- these are written in a combo of html and liquid --> 

<div class="left">
{% include elements/button.html link="https://github.com/vega/vega/blob/main/docs/data/cars.json" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/jnaiman/online_cv_public/blob/main/python_notebooks/test_generate_plots.ipynb" text="The Analysis" %}
</div>


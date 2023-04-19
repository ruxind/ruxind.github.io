---
name: Vega Lite Example Project
tools: [Python, HTML, vega-lite, Altair]
image: assets/pngs/Screenshot.png
description: Vega-lite plots using different methods!
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---


# Use Vega-lite in many ways in Jekyll
This project will show how to use vega-lite to make plot in different methods.

```
<vegachart schema-url="{{ site.baseurl }}/assets/json/cars.json" style="width: 100%"></vegachart>
```
## 1. Directly from vega-editor

<vegachart schema-url="{{ site.baseurl }}/assets/json/vega_editor_plot1.json" style="width: 100%"></vegachart>
<vegachart schema-url="{{ site.baseurl }}/assets/json/vega_editor_plot2.json" style="width: 100%"></vegachart>

## 2. Direcly from vega-editor
Include images stored in 'assets\pngs' folder with Markdown

![a vegalite plot with interactive legend](/assets/pngs/Screenshot.png)

## 3. Vega-lite from vega-specs to Json with Altair
<vegachart schema-url="{{ site.baseurl }}/assets/json/chart1.json" style="width: 100%"></vegachart>

<!-- these are written in a combo of html and liquid --> 

<div class="left">
{% include elements/button.html link="https://github.com/vega/vega/blob/main/docs/data/cars.json" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/jnaiman/online_cv_public/blob/main/python_notebooks/test_generate_plots.ipynb" text="The Analysis" %}
</div>


---
name: Homework 10
tools: [Python, HTML, vega-lite,Altair]
image: assets/pngs/homework10.png
description: This presents visualizations from homework 10.
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---


# Homework 10 visualizations
## 1. First Interactive Line Plot

<vegachart schema-url="{{ site.baseurl }}/assets/json/w10chart1.json" style="width: 100%"></vegachart>
This line plot is based on and an expansion of my first visualization in homework9. In this plot, I try to show the median and mean constructed year of every congress district. I created a line chart with two lines: one for mean and one for median. For interaction, I added a layer that can show the mean and median values of the district selected by moving mouse. This interactivity helps users to compare mean and median in the same district more easily.
## 2. Histogram from Homework 9
<vegachart schema-url="{{ site.baseurl }}/assets/json/w10chart2.json" style="width: 100%"></vegachart>
I did not add interactivity for this plot. This visualization was from week 9 plot 2, and I used Altair to transfered my Vega-lite code into Python. I used alt.Chart.from_dict function in Altair and keep the codes of building the histogram using Vega-lite. This histogram shows the median square footage of each bin of constructed year.


<!-- these are written in a combo of html and liquid --> 

<div class="left">
{% include elements/button.html link="https://raw.githubusercontent.com/UIUC-iSchool-DataViz/is445_bcubcg_fall2022/main/data/building_inventory.csv" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/ruxind/ruxind.github.io/blob/main/python_notebooks/Duan-Ruxin-Homework%2310.ipynb" text="The Analysis" %}
</div>


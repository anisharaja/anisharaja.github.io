---
name: Final Project
tools: [Python, HTML, Altair]
image: assets/pngs/final_project.png
description: This is my final project about the education statistics of various counties in the state of Georgia, such as average annual salary of teachers, administrators, and support staff.
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---


# Education Statistics of Counties in Georgia, United States

## Main Visualization
<vegachart schema-url="{{ site.baseurl }}/assets/json/final_dashboard.json" style="width: 100%"></vegachart>
<br>

## Contextual Visualization 1
<img src = "{{ site.baseurl }}/assets/pngs/administrators.png"/>

<!-- these are written in a combo of html and liquid --> 

<div class="left">
{% include elements/button.html link="https://raw.githubusercontent.com/UIUC-iSchool-DataViz/is445_bcubcg_fall2022/main/data/bfro_reports_fall2022.csv" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/anisharaja/anisharaja.github.io/blob/master/python_notebooks/raja-anisha-homework10.ipynb" text="The Analysis" %}
</div>


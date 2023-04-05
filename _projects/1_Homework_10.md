---
name: Homework 10
tools: [Python, HTML, vega-lite, Altair]
image: assets/pngs/hw10_viz1.png
description: This is a homework assignment that uses vega-lite for interactive viz!
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---


# Homework 10

## Visualization 1
<vegachart schema-url="{{ site.baseurl }}/assets/json/viz1.json" style="width: 100%"></vegachart>

For this visualization, I decided to visualize the relationship between the high temperature and the pressure for each bigfoot case. I decided to use the point mark to create this visualization, as that is how one would create a scatterplot in vega-lite, which is what I wanted to do. I wanted to create a scatterplot because I am visualizing the relationship between two quantitative variables. I also decided to make the points purple to make the points more visually appealing for the viewer. I did not use a color scheme as I felt that it was not relevant to my visualization. I did not perform any data transformations in the analysis side of things for this visualization. I decided to make this visualization more interactive by a tooltip to show the description of the bigfoot sighting associated with that data point. I felt that this makes the visualization more interesting as it provides some context for each datapoint. Since there are a lot of data points, I decided to add some zoom selection functionality to make the points easier to hover over for the tooltip to show up. 
## Visualization 2
<vegachart schema-url="{{ site.baseurl }}/assets/json/viz2.json" style="width: 100%"></vegachart>
For this visualization, I decided to visualize the amount of bigfoot cases there are by specific year. I decided to use the bar mark to create this visualization, as I want to visualize the count of something. I also decided to make the bars green to make the points more visually appealing for the viewer. I did not use a color scheme as I felt that it was not relevant to my visualization. I did extract the year portion of the date column in my analysis jupyter notebook. I decided to make this visualization more interactive by a tooltip to show the year and count for each bar, as these aspects can be hard to visualize by looking at the bar chart alone.

<!-- these are written in a combo of html and liquid --> 

<div class="left">
{% include elements/button.html link="https://raw.githubusercontent.com/UIUC-iSchool-DataViz/is445_bcubcg_fall2022/main/data/bfro_reports_fall2022.csv" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/anisharaja/anisharaja.github.io/blob/master/python_notebooks/raja-anisha-homework10.ipynb" text="The Analysis" %}
</div>


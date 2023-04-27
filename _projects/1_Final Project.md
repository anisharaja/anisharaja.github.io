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
### By: Anisha Raja
---
## Average Annual Salary of PK-12 Teachers, Support Staff, and Administrators Compared to Public School CCRPI Score in Georgia counties.

<vegachart schema-url="{{ site.baseurl }}/assets/json/final_dashboard.json" style="width: 100%"></vegachart>


#### Links
<div class="left">
{% include elements/button.html link="https://github.com/anisharaja/anisharaja.github.io/blob/master/assets/csv/county_personnel.csv" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/anisharaja/anisharaja.github.io/blob/master/python_notebooks/raja-anisha-finalproject-part2.ipynb" text="The Analysis" %}
</div>
<br>
<br>
<br>




## How Georgia pays its Teachers compared to other states
<vegachart schema-url="{{ site.baseurl }}/assets/json/state_teacher_salaries.json" style="width: 100%"></vegachart>


#### Links
<div class="left">
{% include elements/button.html link="https://github.com/anisharaja/anisharaja.github.io/blob/master/assets/csv/tabn211.60_1" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/anisharaja/anisharaja.github.io/blob/master/python_notebooks/raja-anisha-finalproject-part2.ipynb" text="The Analysis" %}
</div>
<br>
<br>
<br>






## How Georgia Pays its Administrators compared to other states
<img src = "{{ site.baseurl }}/assets/pngs/administrators.png"/>


#### Links
<div class="left">
{% include elements/button.html link="https://www.bls.gov/oes/current/oes119039.htm" text="The Data" %}
</div>

<br>
<br>

## Write-Up
My main visualization is in the form of a dashboard, which means that changes the viewer will make on the left plot will change the plot on the right. On the left side of the dashboard, there is a plot describing the relationship between the 2019 Public School CCRPI score and the average annual salary of Pre-K to Grade 12 teachers in various counties in the state of Georgia. Also on the left side, if one hovers over a circle, then there will be information about the county, the 2019 Public School CCRPI score and the average annual salary of Pre-K to Grade 12 teachers corresponding to that circle. On the right side of the dashboard, there is a chart illustrating a comparison between the average annual salaries of Administrators, Support Staff, and Pre-K to Grade 12 teachers in a particular county. Also on the right side, if one hovers over the bar, then the average annual salary associated with that bar will be displayed. The county that is illustrated on the right is based on the circle that is selected on the left. For example, if the county selected on the left is Jenkins county, then the average annual salaries of Administrators, Support Staff, and Pre-K to Grade 12 teachers of Jenkins county will be displayed on the right. If none of the circles are selected, then the labels for all of the counties will show. Once a county is selected, the dashboard should reset itself and show the data it is supposed to show. Another aspect to watch out for is that the scales for the plot on the right will change depending on the county selected.

To add some context to the main visualization, I have added some plots to show to Georgia pays its teachers and administrators compared to other states. I also made sure to only include data from the 2020-2021 school year, as that is the time period the original dataset also records. To illustrate how Georgia pays its teachers compared to other states, I created a bar graph to show the relationship of the salaries of other states in relation to each other. I then highlighted the bar representing Georgia, so that it would be clear to the viewer as to which bar I am comparing my findings to. I also added a green line at the value that represents the average annual salary from all of the states, so I can better see how Georgia pays its teachers compared to the national average. To illustrate how Georgia pays its administrators compared to other states, I used a plot that was created by the Bureau of Labor Statistics to highlight this.

Based on my findings, it seems that Georgia pays their teachers and administrators decently compared to other states. However, Georgia pays its teacher below the national average, since the height of the bar corresponding to Georgia is lower than the green line representing the average. According to the key of the graph from the Bureau of Labor Statistics, Georgia pays their administrators in the second highest range ($85,730 - $94,570). Considering these factors about Georgia from these two visualizations, Georgia could do better in paying its teachers and administrators. This is especially true when the viewer looks at how the teachers and administrators are being paid in individual counties compared to the national average.

<!-- these are written in a combo of html and liquid --> 

## Links
The links for the data and jupyter notebooks are under the visualization they correspond to.


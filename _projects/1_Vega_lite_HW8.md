---
name: MahirThakkar HW 8 
tools: [Python, HTML, vega-lite]
image: assets/pngs/cars.png
description: This is a homework that uses vega-lite for interactive viz!
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---


## Building Dataset

Let's look at the plots and analysis below


## Simple Plot on how Congressmen and the number of buildings made under them

<vegachart schema-url="{{ site.baseurl }}/assets/json/bar_chart.json" style="width: 100%"></vegachart>



I made this visualisation to simplify the license types' distribution, showing a condensed yet clear picture. My Visualization uses a bar chart encoding, where each type of license gets its own bar. Think of it like a straightforward bar chart, where each bar represents a license type, and its height shows how many licenses there are. 

The colors make it easy to tell different types apart. We've made it simpler by focusing on essential details and angling labels for a comfy read. 

This chart is like a quick guide for understanding the variety of licenses in a glance. Perfect for anyone wanting a straightforward overview without getting overwhelmed!



<div class="left">
{% include elements/button.html link="https://github.com/UIUC-iSchool-DataViz/is445_data/raw/main/licenses_fall2022.csv" text="The Data" %}
</div>



<div class="right">
{% include elements/button.html link="https://github.com/MahirThakkar/MahirThakkar.github.io/blob/main/python_notebooks/Mahir_HW8_IS445.ipynb" text="The Analysis" %}
</div>



## Interactive plot on Usage Description and Square Footage of it




<vegachart schema-url="{{ site.baseurl }}../assets/json/selected_chart.json" style="width: 100%"></vegachart>


In this visualization, I've depicted a bar chart encoding, representing License Type on the x-axis, license count on the y-axis. Think of it as a snapshot of the licenses landscape, with each bar representing a different type of license, colored encoded on its status (active, expired etc). The height of each bar indicates the count of licenses for a particular type, offering a clear visual comparison. I've chosen a combination of dropdown menus for License Type and License Status, allowing you to dynamically explore the data.

This visualization can be valuable for regulatory authorities to quickly assess and compare the distribution of active and inactive licenses across various types, aiding in targeted resource allocation and proactive management of licensing issues.

The color scheme, using distinct colors for different License Statuses, aids in easily distinguishing between active, not renewed, and other statuses. This choice enhances clarity and makes it more engaging for authorities to explore the diverse license types and statuses.




<!-- these are written in a combo of html and liquid - --> 

<div class="left">
{% include elements/button.html link="https://github.com/UIUC-iSchool-DataViz/is445_data/raw/main/licenses_fall2022.csv" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/MahirThakkar/MahirThakkar.github.io/blob/main/python_notebooks/Mahir_HW8_IS445.ipynb" text="The Analysis" %}
</div>

---
layout: page
title: "Research on Glaciers and Ice Sheets"
permalink: /research_glaciers_icesheets/
---

## Terminus variations of Greenland glaciers

Enze Zhang, PhD student

Enze’s research focuses on terminus variations of glaciers in Greenland, quantifying such variations in a high temporal resolution and understanding their controlling factors. Based on deep learning, he develops a method to extract the calving front automatically using multi-sensor remote sensing imagery (TerraSAR-X, Sentinel-1, Landsat). He also analyzes the controlling factors of the calving front variations by combining other data such as glacier velocity and bed elevation.

![](/assets/img/research/enze_ji.png){: style="width: 480px"}

*TerraSAR-X image over Jakobshaven Isbræ. The red line indicates the calving front position, delinated using a Deep Learning method.* 

<p> &nbsp; </p>

## Greenland Ice Sheet mass balance

Jiangjun (JJ) Ran, Postdoc

Jiangjun is currently investigating the Greenland ice sheet mass balance using the regional climate models (e.g., RACMO 2.3 and MAR 3.9), and data from remote sensing technologies (e.g., satellite gravimetry, InSAR, and altimetry). More specifically, he is interested in deriving the mass variations of the Greenland ice sheet from GRACE in a statistically optimal way using the “mascon” (i.e., mass concentration) approach. Furthermore, he is also trying to understand the mass anomalies in the sub-surface processes of Greenland ice sheet (e.g., meltwater retention) at short-time scales.

![](/assets/img/research/Greenland_DMT2.gif){: style="width: 1000px"}

*This animation shows the mass variations in Greenland and its neighboring areas, derived from GRACE, in terms of equivalent water height (EWH).*

<p> &nbsp; </p>


Every project has a beautiful feature showcase page.
It's easy to include images in a flexible 3-column grid format.
Make your photos 1/3, 2/3, or full width.

To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    ---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images, even citations {% cite einstein1950meaning %}.
Say you wanted to write a bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}


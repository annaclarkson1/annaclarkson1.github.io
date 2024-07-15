---
layout: page
title: A Plan to Keep Students Safe
description: An Analysis on School Shootings
img: assets/img/washington_post.jpg
importance: 1
category: school
---


This is the final project for the Data Visualization course. Working with a partner, we used a [Washington Post database](https://github.com/washingtonpost/data-school-shootings) that provided data for school shootings beginning with Columbine in April 1999 (their article is [here](https://www.washingtonpost.com/graphics/2018/local/school-shootings-database/). We analyzed and visualized the data in R. Our visualizations can be seen below, and the full project is available here.  

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/Number_of_shootings.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/Number_of_fatalities.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
        <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/Shootings_by_age.png" title="example image" class="img-fluid rounded z-depth-1" %}
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

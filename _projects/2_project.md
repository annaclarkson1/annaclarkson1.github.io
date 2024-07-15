---
layout: page
title: Weather & Traffic
description: An analysis of weather and traffic data, using APIs from TomTom and OpenWeather. The data analysis was done in SQL and R.
img: assets/img/TomTom_OpenWeather.jpg
importance: 2
category: school
---

This is the final project for our Data Engineering class. The main question was if rain affected traffic speeds or not. With a partner, we selected APIs to scrape data from, input into SQL, and analyze. We chose TomTom for traffic data and OpenWeather for weather data, and focused on a GPS coordinate along US Route 26 in Beaverton, Oregon. Using Railway, I had TomTom data scraped every four hours. We then input the JSON data from both APIs into SQL, where we cleaned it and merged the two datasets to analyze. We ultimately found that rain does not affect traffic speeds based on our data, but we had limited data and other variables impacting traffic speeds (like commutes or local events). Our visualizations can be seen below, and the presentation is available [here](https://github.com/annaclarkson1/annaclarkson1.github.io/blob/master/_projects/DATA%20503%20-%20Final%20Project.pdf). 


<div class="row">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Rain_traffic.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Speed_by_weather.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Speed_by_weather_type.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Traffic_and_wind_speed.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

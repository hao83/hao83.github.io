---
layout: post
title:  "Assignment2."
date:   2023-03-27 08:35:38 +0530
categories: jekyll update
bokeh: /assets/bokeh.html
folium: /assets/folium.html
---

## A significant drop in Drug/narcotic crime in San Francisco from 2003 to 2017.

## The data

This article is based on the dataset: <a href="https://data.sfgov.org/Public-Safety/Police-Department-Incident-Reports-Historical-2003/tmnf-yvry">Police Department Incident Reports: Historical 2003 to May 2018.</a>
This dataset has the information about the crime incidents in San Francisco from 2003 to 2017, and the scape of this dataset is more than two millions.
The information of the crime recorded includes category, exact time, location and so on. This article concerns about
the number of drug/narcotic crimes from 2003 to 2017. 

## Data analysis and visualization

* The timeseries of the number of drug/narcotic from 2003 to 2017.

This plot tracks the number of drug/narcotic in San Francisco from 2003 to 2017, it shows that the number 
of drug/narcotic has a significant drop from 2010.
![drug/narcotic from 2003 to 2017]({{site.baseurl}}/images/DRUG1.png){:width="100%"}

* Hotspots of Drug/narcotic crime

This plot tracks the number of drug/narcotic in San Francisco related to the area. This heatmaps reveals that
all the areas of San Francisco are suffering from the drug/narcotic crime, in the other words, drug/narcotic is 
a really pervasive crime in San Francisco which the police need to focus on. 

<iframe src="{{page.folium}}" width="100%" height="600px" frameborder="0">
    Sorry, your browser doesn't support iframes.
</iframe>

<iframe src="{{page.bokeh}}" width="100%" height="600px" frameborder="0">
    Sorry, your browser doesn't support iframes.
</iframe>

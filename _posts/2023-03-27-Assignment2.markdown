---
layout: post
title:  "Assignment2."
date:   2023-03-27 08:35:38 +0530
categories: jekyll update
---

## A statistical insight into crimes in San Francisco in the years 2003 to 2018.

## The data

This article is based on the dataset: <a href="https://data.sfgov.org/Public-Safety/Police-Department-Incident-Reports-Historical-2003/tmnf-yvry">Police Department Incident Reports: Historical 2003 to May 2018.</a>
This dataset has the information about the crime incidents from the San Francisco from 2003 to 2018, and the scape of this dataset is more than two millions.
The information of the crime recorded includes category, exact time, location and so on.  

## Data analysis and visualization


{% include bokeh.html %}


<iframe src="{{page.bokeh}}" width="100%" height="600px" frameborder="0">
    Sorry, your browser doesn't support iframes.
</iframe>

![sample post]({{site.baseurl}}/assets/bokeh.html)
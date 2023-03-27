---
layout: post
title:  "Assignment2."
date:   2023-03-27 08:35:38 +0530
categories: jekyll update
bokeh: /assets/bokeh.html
folium: /assets/folium.html
---

<h1> A significant drop in Drug/narcotic crime in San Francisco from 2003 to 2017.</h1>

<h2> The data </h2>

This article is based on the dataset: <a href="https://data.sfgov.org/Public-Safety/Police-Department-Incident-Reports-Historical-2003/tmnf-yvry">Police Department Incident Reports: Historical 2003 to May 2018.</a>
This dataset has the information about the crime incidents in San Francisco from 2003 to 2017, and the scape of this dataset is more than two millions.
The information of the crime recorded includes category, exact time, location and so on. This article concerns about
the number of drug/narcotic crimes from 2003 to 2017. 

<h2> Data analysis and visualization</h2>

* <b>The timeseries of the number of drug/narcotic from 2003 to 2017.</b>

This plot tracks the number of drug/narcotic in San Francisco from 2003 to 2017, it shows that the number 
of drug/narcotic has a significant drop from 2010.
![drug/narcotic from 2003 to 2017]({{site.baseurl}}/images/DRUG1.png){:width="100%"}

* <b>Hotspots of Drug/narcotic crime</b>

This plot tracks the number of drug/narcotic in San Francisco related to the area. This heatmaps reveals that
all the areas of San Francisco are suffering from the drug/narcotic crime, in the other words, drug/narcotic is 
a really pervasive crime in San Francisco which the police need to focus on. 
<br>
According to the heatmap, 'DRUG/NARCOTIC' crimes are widespread throughout San Francisco. However, there are some areas where no criminal activity is recorded, mainly in parks, gardens, and nature preserves. This suggests that these locations are less likely to be targeted by drug-related criminal activity, possibly due to their more secluded nature making it more difficult for such activities to go unnoticed. Overall, the heatmap highlights areas that may require additional attention from law enforcement to further combat drug-related crimes.

<iframe src="{{page.folium}}" width="100%" height="600px" frameborder="0">
    Sorry, your browser doesn't support iframes.
</iframe>

* <b>Compared with other type of crime.</b>

This plot is an interactive plots which allows people to compare the trend of drug/narcotic with other type of crimes in San Francisco.
Compared with other type of crimes, we can find that the drug/narcotic issues have been well solved as the trend of
drug/narcotic rates has a significant drops since 2009 while other type of crimes rates have the upward trend or remain stable.


<iframe src="{{page.bokeh1}}" width="100%" height="600px" frameborder="0">
    Sorry, your browser doesn't support iframes.
</iframe>

<h2> Conclusion </h2>
In conclusion, the data spans from 2003 to 2017, showing an overall decrease of 7,000 incidents over the given period, resulting in a 0.22 decrease in the crime rate, with a starting value of 10,000(crime rate 0.4) in 2003. After a slight dip in 2005, the data rose to 12,000(crime rate 0.44) in 2009, reaching its peak before sharply dropping to 6,500(crime rate 0.32) in 2011. The data continued to decline steadily thereafter, reaching 3,000(crime rate 0.22) in 2017. Overall, the trends in the data suggest significant changes occurred after 2009, with a sharp drop in 2011 and a steady decline in the years following. It is evident that the San Francisco Police Department has had a significant impact on reducing the occurrence of crimes related to drugs over the past 15 years.


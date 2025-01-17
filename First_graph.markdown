---
layout: page
title: Assignment 2
permalink: /page1/
---

<figure markdown="span">
    ![Header image](/Scary_trend.png)
</figure>

## Rise in forcible sexual offenses in the Bay Area

#### Introduction
Since 2003, San Francisco has been keeping a registry of all reported crimes. This allows us to look into both trends and specifics of the crime data. The dataset contains data about the crime categories as well as temporal and geographic data, all of which we will use to examine an interesting trend that San Francisco is experiencing. When looking at the overall dataset, the rise of one particular crime type caught our eye: forcible sexual offenses. At first glance, this crime type seems to consistently increase in numbers every year, so we decided to take a closer look and further examine the hypothesis that San Francisco is indeed experiencing a rise in forcible sex offenses (FSOs).
![My image](/SC_trend.png)

#### Understanding the trend
In the above figure, we clearly see how the number of FSOs is on a steady climb, at a rate much higher than the general development of reported crimes. This begs the question, what is driving this ever-increasing number? Is it because of an increasing crime rate or due to a larger focus on the crime type from both law enforcement and citizens, which leads to increased reporting? Another question is whether this is the case for the whole of San Francisco, or maybe only a subset of districts or neighborhoods. In the section below, we therefore try to examine any geographical trends in the development of FSOs in the Bay Area.

#### A look into the geography of forcible sex crimes
{% include Final_map.html %}
The map above shows the geographical distribution of FSOs for each of the years within the dataset. District borders have been highlighted, and the number of total forcible sex offenses can be viewed by clicking on the district markers. When we view the map, we see the same trend of increasing crimes as in the previous plot. Although it generally appears as if there is an increase in FSOs across all districts, there seem to be two hotspot areas (marked by red circles) with Tenderloin and its bordering districts and Mission having a much higher concentration of FSOs and what also appears to be a steeper increase in crime numbers across time. When looking into these areas, we find that these aren't the poorest, most densely populated, or ethnically diverse areas [[5]](https://sfstandard.com/2022/12/08/san-francisco-neighborhood-new-census-data-maps/){:target="_blank"}{:rel="noopener noreferrer"}, instead, when we look closer at the specific areas within the districts which are affected by FSOs, we see that these are closely related to party culture, take "Valencia street" and "Union Square," which are both part of the highlighted hotspots AND on a list of "The Best Streets for Bar Hopping in San Francisco" by SFtravel.com [[6]](sftravel.com/article/best-streets-bar-hopping-san-francisco){:target="_blank"}{:rel="noopener noreferrer"}. Another interesting trend is that there seem to be a higher number of crimes in areas surrounding train/tram lines, although this might just be due to the increased number of people passing through these areas. 

#### Crime rate of the individual districts
Although the heat map provides a good visual overview of the development of FSOs across time, it can be difficult to accurately tell how large an increase a given district has experienced and how the different years compare. The plot below therefore shows the development in FSOs of each district along with a trendline summarizing the development in FSO crimes across time. The plot is interactive, and each individual district can be turned on and off by clicking on its corresponding legend. When looking at the plot, we can first of all see that all trendline slopes are positive, confirming our impression of an upward trend in FSOs. Similarly, we also see some areas experiencing a much higher rate of increase in FSOs, with Mission having a more than 10 times higher increase rate than Richmond.
{% include inter_plot.html %}

#### Conclusion
All in all, it is safe to say that San Francisco is suffering from an increase in FSOs, and that some areas are more affected than others. Districts like Mission and Southern have both a much higher number of FSOs and have also experienced a much higher increase in FSOs across time compared to areas like Bayview and Richmond. It is hard to conclusively come up with a reason for this, although it does appear as if areas with more partying have a higher rate of FSOs. For future investigations, it could be interesting to further investigate the partying hypothesis and see if FSOs are correlated with large holiday events like New Year's Eve or other temporal patterns. Similarly, San Francisco is known for being a university town, and looking into whether any patterns related to student behavior would be present in the data would be interesting. This is especially the case as San Francisco established a task force aimed at dealing with sexual assault in relation to schools and universities in April of 2016 [[7]](https://sfgov.org/dosw/sites/default/files/Safer%20Schools%20Sexual%20Assault%20Task%20Force%20Report.pdf){:target="_blank"}{:rel="noopener noreferrer"}
. That said, the proposed hypotheses are based on our interpretation of the data, and future work should include an in-depth evaluation of the significance of our observations based on spatial statistics, along with the pursuit of other possible explanations for the identified trends.


#### Reference Links

[SF downtown image](https://cdn.britannica.com/51/178051-050-3B786A55/San-Francisco.jpg){:target="_blank"}{:rel="noopener noreferrer"}

[Article [1]](https://hoodline.com/2024/03/san-francisco-man-convicted-for-sexual-assault-of-elderly-woman-faces-up-to-10-years/){:target="_blank"}{:rel="noopener noreferrer"}

[Article [2]](https://www.cbsnews.com/sanfrancisco/news/san-francisco-man-horrific-child-sexual-assault-facing-50-years-to-life/){:target="_blank"}{:rel="noopener noreferrer"}

[Article [3]](https://sfist.com/2015/11/24/sf_state_officials_refuse_to_commen/){:target="_blank"}{:rel="noopener noreferrer"}

[Article [4]](https://www.eastbaytimes.com/2016/10/23/bay-area-colleges-keep-most-sexual-assault-reports-quiet/){:target="_blank"}{:rel="noopener noreferrer"}

[Article [5]](https://sfstandard.com/2022/12/08/san-francisco-neighborhood-new-census-data-maps/){:target="_blank"}{:rel="noopener noreferrer"}

[Article [6]](https://www.sftravel.com/article/best-streets-bar-hopping-san-francisco){:target="_blank"}{:rel="noopener noreferrer"}

[Article [7]](https://sfgov.org/dosw/sites/default/files/Safer%20Schools%20Sexual%20Assault%20Task%20Force%20Report.pdf){:target="_blank"}{:rel="noopener noreferrer"}


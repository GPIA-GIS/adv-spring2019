---
layout: project-page
title: "Where do you want bike share?"
linkname: where-do-you-want-bike-share-
author: "Hugo Torres-Fetsco"
tagline: "This map allows visitors to leverage census data and surrounding transportation infrastructure when suggesting a bike share location in NYC"
location:
    - place: New York, USA
project-link:
    - href: https://htorresfetsco.github.io/Hugo-A.GIS-WhereDoYouWantBikeShare/
tags:
    - tag: bike share
    - tag:  citibike
    - tag:  DoT
    - tag:  equity
    - tag:  transportation
thumbnail-path: img/where-do-you-want-bike-share-/h6ClfzI.png
img-folder: ../../img/where-do-you-want-bike-share-/
timestamp: 5/14/2019 3:51:40
---
It was announced in November 2018 that Citi Bike would be getting a $100 Million investment from parent company Lyft to double the current service area and more than triple its number of bikes to nearly 40,000 on NYC streets. Some of the biggest criticism of Citi Bike is that it has not expanded to low-income and predominately minority neighborhoods lacking transportation options. The planned expansion will allow for more low-income New Yorkers to be within the service area and benefit from targeted Citi Bike membership discounts (i.e. $5/mo for NYCHA residents or SNAP recipients). In addition, there will be opportunities to improve upon the previous community engagement efforts. 

**Previous DOT Community Engagement Approach:**

* In 2011 and 2012, New Yorkers could suggest bike-share stations at public workshops where participants mapped out where they wanted stations to go
* Eighteen months of meetings, demonstrations and discussion, 14 community planning workshops, and more than 10,000 online suggestions produced a vast quantity of information on where New Yorkers wanted to see Citi Bike stations
* DOT used that information to come up with a [preliminary map of 600 bike-share stations](https://nycdotbikeshare.info/sites/default/files/2017-12/Brooklyn%20CB%206_Draft%20Plan%20Presentation.pdf)

The objective of my map is to allow visitors to leverage census data and surrounding transportation infrastructure when suggesting a bike share location (a feature currently not available on the DOT bike share suggestion website).

![]({{ page.img-folder }}pDJlAX4.png)

In order to make these features available, I gathered data from NYC Open Data that included:

1) Bike Priority Areas outlined by the NYC Vision Zero initiative

![]({{ page.img-folder }}HKhBUmQ.png)

2) NYCHA developments

![]({{ page.img-folder }}OptjQo7.png)

3) NYC Bike Routes

![]({{ page.img-folder }}TZfi4os.png)

4) Subway Stations and Subway Lines

![]({{ page.img-folder }}Aujnm8O.png)

5) Census tract demographic information

![]({{ page.img-folder }}jVN5vF8.png)

In addition, I sourced Citi Bike stations from google groups and imported the excel into Carto

![]({{ page.img-folder }}rNRxuAu.png)

![]({{ page.img-folder }}0geZ267.png)

This information was then all aggregated on Carto and edited in Glitch

![]({{ page.img-folder }}LR0cezr.png)

Once the google form was ready and suggestions could be made, I embedded the suggested bike share locations from the google form onto the map and it will be updated every hour

![]({{ page.img-folder }}AagRRm7.png)

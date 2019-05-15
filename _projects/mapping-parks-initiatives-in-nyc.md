---
layout: project-page
title: "Mapping Parks Initiatives in NYC"
linkname: mapping-parks-initiatives-in-nyc
author: "Jonathan Kovacs"
tagline: "Mapping NYC Parks initiatives and progress: the Community Parks Initiative and OneNYC Resiliency Plans."
location:
    - place: New York City, USA
project-link:
    - href: https://cpi-parks.glitch.me/
tags:
    - tag: nyc parks
    - tag:  onenyc
    - tag:  cpi zones
    - tag:  sustainability
    - tag:  resiliency
    - tag:  walkability
thumbnail-path: img/mapping-parks-initiatives-in-nyc/bSPNXyF.png
img-folder: ../../img/mapping-parks-initiatives-in-nyc/
timestamp: 5/14/2019 2:49:53
---
This project's objective is to geographically present NYC Parks initiatives, such as the Community Parks Initiative (CPI) and OneNYC Resiliency Plans, while exploring park accessibility through the "Walk to a Park" service areas. The goal is to identify neighborhoods with the greatest need for park investments and to track ongoing initiatives and progress.

The CPI is an investment in neighborhood parks that are situated in areas with higher-than-average poverty and that have historically received inadequate maintenance and development. This map displays CPI Zone and Parks property data utilizing Neighborhood Tabulation Areas as the unit of measure.

The first step in my methodology was to identify which parks fell within these CPI Zones, which was done using the "intersect and aggregate" analysis tool in Carto.

<iframe width="100%" height="520" frameborder="0" src="https://thenewschool.carto.com/u/jonny-fives/builder/125dbebe-e91d-4f63-bc8f-86a1b23663ea/embed" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>

NYC Recovery and Resiliency projects seek to boost the ability of parklands to withstand disruptive events such as extreme weather. This initiative is part of OneNYC, the citywide strategic plan to build a strong and fair city. The "High Performance Landscape Guidelines" support a strategy to mitigate and adapt to the impacts of climate change through the benefits of green infrastructure by absorbing stormwater, reducing the urban heat island effect, and increasing habitat.

Resiliency projects are displayed as points. I used Carto's "filter by column" analysis to select only those projects managed by the NYC Parks Department and I styled changes by zoom level with CSS. Clicking on a project point displays a pop-up with further information, such as project type, name, details, and project phase.

![]({{ page.img-folder }}TivxnqY.png)

To identify walkability to parks, I used a shapefile of a combined buffer analysis (a half-mile to larger parklands and a quarter-mile to smaller parks) which was mapped thematically to the Neighborhood Tabulation Areas using Carto's "intersect and aggregate" analysis tool. Polygon color was measured by value density and exported as a GEO JSON for use in Glitch.

<iframe width="100%" height="520" frameborder="0" src="https://thenewschool.carto.com/u/jonny-fives/builder/5850dd9f-a5dd-4032-b2b1-74fb90f916d9/embed" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>

With the addition of a sidebar, I set up tabs to display information about the map, its methodology, sources, and author. Using Carto SQL API, I included sidebar feature content to get the count of park spaces within a half-mile of the point clicked.

This map can be used by public space advocates and resiliency planners to find more information on park initiatives and to identify areas in need of investment.
---
layout: project-page
title: "Exposing the Voids"
linkname: exposing-the-voids
author: "Claudia Rot "
tagline: "This project sheds light on Dutch open data that is often not used or not easily accessible to open a discussion about the politics of data."
location:
    - place: The Netherlands
project-link:
    - href: https://claudiarot.github.io/Exposing-the-Voids/
tags:
    - tag: Environmental justice
    - tag:  land reclamation
    - tag:  population dot map 
thumbnail-path: img/exposing-the-voids/8QgSwjL.png
img-folder: ../../img/exposing-the-voids/
timestamp: 5/12/2019 21:39:33
---
‘Exposing the Voids’ was created to shed light on Dutch open data that is often not used or not easily accessible. The Netherlands has an incredible amount of open data available for the public, but there exists no clear data hierarchy, resulting in a lot of data being snowed under by the sheer number of datasets that is available. 
By using these datasets and displaying them in a novel way, ‘Exposing the Voids’ hopes to inspire people to think about the politics behind data accessibility and if something like having access to too much data exists. 

The project consists of three maps, each of them with a focus on a different topic, but all data sets are related to the Netherlands. 

![]({{ page.img-folder }}3NLfyiW.png)

The ‘Old Maps’ page uses a dynamic scrolling structure to show the metamorphosis of the shape of the Netherlands over the past 400 years. Rather than showing the transformation of a specific part of the country, or showing a historical map, these images are extracted from shapefiles that were created for the purpose of this project. By displaying the country as a whole, with only the shape changing from map to map, the user can focus on the shape of the country without being distracted by the different cartographic layouts from the historical maps. 

For the purpose of this project, the focus of the metamorphosis was on the changing coastline and land reclamation projects over time, not on the border of the Netherlands with its neighbouring countries. For each map, a historical map of the Netherlands was used and georectified in GIS software. After the rectification of the map, a recent shapefile of the Netherlands was layered on top of the map and the shape was adjusted to the shape of the historical map using the layer editor. 

![]({{ page.img-folder }}CLetso8.png)

The ‘Population Dots’ page uses demographic data from the Dutch CBS (Centraal Bureau voor de Statistiek) and the geographical boundaries of ‘buurten’, as defined by CBS to generate random population dots within the boundaries of ‘buurten’ for the entire country. Inspired by the Racial Dot Map for the United States, the dots on this map represent 50 persons per dot, with the colour of the dot making a distinction between different migration backgrounds . Unlike the United States, the Netherlands does not collect data based on people’s self-identified race. Rather, the country uses the categories ‘no migration background’, ‘western migration background’, and ‘non-western migration background’. See here for an explanation of these categories. The two images below show the cities of Amsterdam and Rotterdam, respectively. By taking out most of the other topographic markers, the boundaries and neighbourhoods of the cities are defined by their population. 

![]({{ page.img-folder }}Z6vRCWW.png)

![]({{ page.img-folder }}neHwKnd.png)

By clicking on a point in the map, demographic statistics are pulled from the data sets to show how many people with each respective migration background live within a 7 kilometer radius of where the user clicked. 

This interactive demographic map of the Netherlands will be very useful for future use, as it can be combined with other datasets to show geospatial disparities in environmental risk between parts of the country where a lot of people with or without a migration background live. In the discourse of environmental justice, demographic maps are used to prove how communities of colour and low income communities are disproportionately affected by environmental problems and pollution. Combining this population dot map with the environmental risk map I made for my GIS class last semester can add an intersectional dimension to the project to show how physical environmental risk are perceived under different societal circumstances. See the image below where I overlaid the environmental risk map I made for Amsterdam with the population dot map. 

![]({{ page.img-folder }}eyCCoLu.png)

The ‘Water Management Projects’ page is an attempt to centralize information about Dutch engineers and architect conducting water infrastructure, land reclamation, and sea level rise adaptation projects abroad. The Netherlands is proud of its water management industry, but except for news articles there is no accessible central database of ongoing and finished projects. By crowdsourcing data and using historical sources, this map will be an ongoing compilation of water management projects. 

The orange dots on the map were all sourced from Johan van Veen’s “Dredge, Drain Reclaim: the Art of a Nation”, which was published in 1955 and includes a variety of maps and data visualizations about Dutch land reclamation practices, both in the Netherlands and abroad. The image below shows the original map from which the orange dots were extracted and geocoded. 

![]({{ page.img-folder }}prt7OF1.png)

The blue dots on the map are crowdsourced from news articles and suggestions from the page’s visitors. Before a blue dot appears on the map, it is fact checked and verified by the moderator. The image below shows the online version of the map with the view focused on Europe. 

![]({{ page.img-folder }}ClOiQY5.png)

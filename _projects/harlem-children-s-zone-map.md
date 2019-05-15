---
layout: project-page
title: "Harlem Children's Zone Map"
linkname: harlem-children-s-zone-map
author: "Nicola Stettler; Yazid Mekhtoub"
tagline: "This interactive map product displays Harlem Children's Zone's project sites throughout their ‘zone’ in Harlem, New York."
location:
    - place: Harlem, New York, USA
project-link:
    - href: https://hcz-mapping.github.io/draft_mapping_2/
tags:
    - tag: harlem
    - tag:  hcz
    - tag:  community
    - tag:  family
    - tag:  nyc
    - tag:  newyork
thumbnail-path: img/harlem-children-s-zone-map/2w2uznQ.png
img-folder: ../../img/harlem-children-s-zone-map/
timestamp: 5/13/2019 19:12:31
---
### Existing Map Product:

Our partnership organization - Harlem Children’s Zone (HCZ) - currently utilizes a standard Google Maps product to display their sites in Harlem, New York. While adequate, the organization tasked us with upgrading the interactivity for the sites, and feature the actual spatial layouts of the schools - where the buildings are located, playgrounds, special buildings, ect. 

The current map can be accessed at the following link: [HCZ Zone-Map](https://hcz.org/zone-map/). 

![]({{ page.img-folder }}XzEGEdV.png)

### Our redesigned Map Product:

As part of the project, we were tasked to design a better interface for the various site attributes  and create a more robust cartographic representation of the schools sites. Users have to be able to quickly understand the spatial components of the site, i.e. its location in Harlem, the school buildings, and the individual programs. 

Additionally, facilitate logical, intuitive access to the school characteristics as well as their additional representative media. 

In our current working process, the school features are represented as points and contain all the data, while the polygon layer acts as a visual aid. The current points have been fully rectified to fit inside the real property.

To keep consistent with the overall design of HCZ’s site, we have used the same css styling.

### Following are the tools that we prioritized:

#### Filter Data

* Filter by type and program. This is an additive process; the more checkboxes are checked the more data is shown. For example: If middle school, college, and afterschool are checked it will show all Middle Schools and Colleges that have an Afterschool program. 

#### Dropdown

* Shows a list of all the school names
* Zooms to school when clicked
* Populates sidebar

![]({{ page.img-folder }}xpxPmmK.png)

#### Sidebar

* This is where the information will populate
* Details / text for each school will be provided by HCZ
* Contains multimedia.

![]({{ page.img-folder }}65BCNEp.png)

#### Pop-ups

* When hovering or clicking the school geometry
* Shows name of school on map

#### On Click

* The map will zoom to the school
* Populates information in sidebar

#### Data Source
        
* CARTO auto updating daily from Google Sheets. This allows us and the client to update information in a familiar platform.

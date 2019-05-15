---
layout: project-page
title: "Climate of Change"
linkname: climate-of-change
author: "Abby Zan"
tagline: "An online hub for envisioning climate justice with frontline residents in D.C."
location:
    - place: Washington, D.C., USA
project-link:
    - href: https://climate-of-change.glitch.me/
tags:
    - tag: climate justice
    - tag:  facilitation
    - tag:  resources
    - tag:  public archive
thumbnail-path: img/climate-of-change/DMWWNZr.png
img-folder: ../../img/climate-of-change/
timestamp: 5/13/2019 21:20:53
---

What if climate change planning in D.C. placed frontline communities in the center? What if, rather than based in fear, planning for resilience was based in care, curiosity, and transformation? The vision at the heart of this project is a shift in D.C.’s approach to--and residents’ role in--resilience planning. Climate of Change envisions offers tools for assessing opportunity in the face of change, and catalyzing collaboration and care from the ground up.

The Climate of Change online hub is one part of a larger, interconnected set of tools developed through research and collaboration in Washington, D.C. about climate justice and resilience. Washington, D.C. is ramping up its efforts to prepare for climate change, yet members of frontline communities (low income, people of color, and others most vulnerable to climate change impacts) are being shut out of the process.

![]({{ page.img-folder }}5ozNBnE.jpg)

I collaborated with grassroots organizations and organizers to develop a ground-up visioning process, led by local facilitators using a set of tools including a facilitation guide which guides facilitators through the process of hosting a visioning workshop, a companion field guide which offers added context and ideas, and an online hub which publicizes the project, shares out resources and resident visions, and helps the disparate groups taking part in this process stay connected.

Below is a sketch of my initial ideas for the site components and functions. The vision evolved based on technical capacities and other discoveries along the way.

![]({{ page.img-folder }}ZbkMUUc.png)

I was planning to receive a large data set of unsorted resources from a partner in D.C., however they were never able to get me these resources. So, I mined for resources using open data sets (DC OPEN DATA), as well as through independent online research, drawing upon my field work and interviews. I consolidated and cleaned these data sets into a Google Drive Spreadsheet which syncs hourly with a Carto map. This syncing feature allows me to continue to update the resource database using the same variables.

Another methodology I made use of in this project was embedding Google Forms into my code, to feed user input into the dataset. This method was used both in the resource map and in the vision page.

![]({{ page.img-folder }}HXmN5z2.png)


![]({{ page.img-folder }}oOnzN56.png)
The bottom image shows the interface that website users see when they add to the embedded google form.

In addition to cleaning, sorting, and syncing data sets and working with Google Forms, I did a lot of formatting with CSS and JS, to customize page layouts and maps on the website. The home page provides basic context about the project, and serves as a landing page to connect users to the other site components.

![]({{ page.img-folder }}QWNJFfJ.jpg)

The resource map was a critical component of the website, which grew out of conversations with contacts in Southeast, D.C., who expressed a need for more centralized public platforms to connect community members to vital resources in housing, health, food, and more. The “LEARN” page (which features the resource map) serves both to practically connect residents to these poorly publicized resources, and also to educate the public about the intersectional nature of climate justice. While issues like food and work may not immediately come to mind when residents hear the word “climate change,” part of the aim of this project is to communicate how embedded climate justice is in all aspects of our lives and well-being.

![]({{ page.img-folder }}E8O2rot.jpg)

The resource map is underscored by base maps that illustrate the uneven distribution of vulnerability and risk in the D.C. metro area. With categories of unemployment, hunger, and poverty as a starting point, users can start to explore the deep inequalities that mark this region, and make climate justice such an important and multi-layered conversation. I used Javascript to create a custom legend and pop-ups, and to add filters in the left hand sidebar that allow users to view certain layers or points.

![]({{ page.img-folder }}o1U6iPT.jpg)

The CONNECT page includes another map, which documents visioning workshops. The pop-ups contain insights and brief summaries from these workshops. In the left sidebar, a Twitter feed shares out multimedia from the project process. Users are able to click the “Add a vision” button to contribute a point to the map and report back on their experiences using the facilitation methodology.

Finally, the ENVISION page shares the facilitation tools themselves, in keeping with the open source nature of the project. A button at the bottom of the sidebar connects users to the project email inbox, for inquiries and questions.

![]({{ page.img-folder }}vNWYP0x.png)

There is much I still hope to do in order to refine this website, both on my own and through feedback from partners in D.C. Having committed a lot of time to website layout and flow, I would like to revisit the resource map in more detail, including adding a more detailed legend, active links in the pop-up windows, and more. I also plan to further sort and flesh out the existing resource data set, adding images wherever possible, and other information. The vision map is still very sparse, so I plan to add a counter and other features to enhance this map and make it more dynamic for users. Finally, I plan to add a fuller about page with more history and context about the project. 









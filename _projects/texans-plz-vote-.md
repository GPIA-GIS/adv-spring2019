---
layout: project-page
title: "TEXANS, PLZ VOTE! "
linkname: texans-plz-vote-
author: "Riane Yates"
tagline: "AN ARGUMENT FOR WHY TEXAS ISN’T A LOST CAUSE &
RESOURCE FOR TEXANS TO EDUCATE THEMSELVES ON THEIR ELECTED OFFICIALS. "
location:
    - place: Texas, USA
project-link:
    - href: https://texans-plz-vote.glitch.me
tags:
    - tag: Voter Turnout, Election Swing, Turn Texas Blue 
thumbnail-path: img/texans-plz-vote-/pgAU8q9.jpg
img-folder: ../../img/texans-plz-vote-/
timestamp: 5/14/2019 2:26:32
---
**BACKGROUND:**
For the past 30 years, Texas has historically been a **RED** state. In 2016, Texas voted for Donald Trump (R) over Hillary Clinton (D) with almost a 10% spread. In 2018, during the midterm elections, Texas saw the party spread shrink to just a 2.6% win by Ted Cruz (R) over Beto O’Rourke (D). This spatial project seeks to illustrate the voting trends of Texans from the 2016 Presidential Election to the 2018 Midterm Election and provide a resource for individuals to find out who their Elected Officials are and if they want to support them in the 2020 election. 

![]({{ page.img-folder }}Ny39BS6.png)

Since 1980, Texas has voted for the Republican candidate in each Presidential Election. Since 1994, Texas has had a Republican Governor and kept both U.S. Senate seats filled with Republican candidates. With 38 Electoral College votes and a population of 28.3 million – the political swing in Texas has a large impact across the country (Texas Secretary of State). 

There have been many efforts over the past 30 years to gain some **BLUE** momentum in Texas – remember Wendy Davis? Each effort fell short. Then during the 2018 Midterm Elections, Texas saw voter turnout hit record levels – now called the Beto effect. In the 30 counties with the most registered voters, Texas saw a 78% increase in voter turnout during the 2018 Midterm Election in comparison to the 2012 Midterm Elections (Texas Tribune, 2018). 

Overall, there was a clear democratic shift from the 2016 Presidential Election to the 2018 Midterm Election by percent swing lead. This is highlighted by the 154 counties that saw a more than 1 percent democratic shift, compared to the only 54 counties that saw a more than 1 percent republican shift. In total, 46 counties did not see more than a 1 percent swing in either direction. 


**PROJECT GOAL:**
With this shift in the Texas political climate, I wanted to provide a space for Texans to easily find information on their elected officials and see that their vote matters. Primarily, this project was executed with an interactive map that allows individuals to switch between TX House, TX Senate and US House districts and click through to see information on each elected official. In addition to this main map, there is a “story” page highlighting the change in political climate in Texas.  


**ELECTED OFFICIAL INTERACTIVE MAP METHODOLOGY:** 
The bulk of my GIS work for this project took place in developing data for the interactive elected official map. The closest platform to what I was trying to build that I could locate online was the [Texas Tribune Elected Official Directory](https://www.texastribune.org/directory/). I decided to collect my data from this site, because it provides a thorough overview of each elected official on their own web page. To create the attribute tables, I collected the following data on each elected official: Name, District, Title (Party Affiliation), Contact Information (Email, phone, TX Tribune Website and twitter handle). Once I collected the data for all elected officials, I created three shapefiles - TX House, TX Senate and US House - and put them onto one map.

![]({{ page.img-folder }}MNIwcc2.png)

**2016 PRESIDENTIAL ELECTION RESULTS & SIZE LEAD BY COUNTY MAP METHODOLOGY:**
To identify election results by county for the 2016 Presidential Election, election results by county data was collected from The New York Times election tracker. A custom attribute table needed to be created with the following fields: County Name, Trump Votes, Clinton Votes, Total Votes, Percent Trump Votes, Percent Clinton Votes, Winner, Percent Size Lead (Republican), Percent Size Lead (Democrat). Winner was illustrated as RED or BLUE in graduated colors. (This was completed in a previous class, for this project I uploaded this attribute table to carto, wrote custom CSS and HTML for the map and embed it into my glitch page)


**2018 MIDTERM ELECTION RESULTS & SIZE LEAD BY COUNTY METHODOLOGY:** 
To identify election results by county for the 2018 Midterm Election, election results by county data was collected from The New York Times election tracker. A custom attribute table needed to be created with the following fields: County Name, Cruz Votes, Beto Votes, Total Votes, Percent Cruz Votes, Percent Beto Votes, Winner, Percent Size Lead (Republican), Percent Size Lead (Democrat). Winner was illustrated as RED or BLUE in graduated colors. (This was completed in a previous class, for this project I uploaded this attribute table to carto, wrote custom CSS and HTML for the map and embed it into my glitch page)


<iframe width="100%" height="700" frameborder="0" src="https://thenewschool.carto.com/u/rianeyates/builder/77996a22-0a9b-4f1b-8c2c-7c595fb08106/embed" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>

**ELECTION SWING BY COUNTY METHODOLOGY:**
To identify the swing in votes by party affiliation by county, the 2016 Presidential Election and 2018 Midterm Election attribute tables were joined by county name. This provided comparative data for the Percent Size Lead in each county from 2016 to 2018. A final field was created, Percent Size Lead Swing. This percent change allowed us to see the shift from one party to another. Percent Size Lead Swing was illustrated in graduated colors from BLUE to RED. (This was completed in a previous class, for this project I uploaded this attribute table to carto, wrote custom CSS and HTML for the map and embed it into my glitch page)

<iframe width="100%" height="700" frameborder="0" src="https://thenewschool.carto.com/u/rianeyates/builder/0a83d2da-a362-47c7-b9ce-5fd913d0173d/embed" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>

**MAKING THE WEBSITE:**
Once I had all of the data and maps loaded into carto, I then transitioned to create the layout for the website. I wanted to make the interactive map the most accessible and prominent, so it is showcased on the first page. To present the attribute data from each district, I created a sidebar to display the information. I layered each TX district data set onto one map so that people can switch between maps. I plan to upload at “search by address” feature this summer.  

There is a TX HOUSE, TX SENATE & US HOUSE button on the map. When a user clicks the button it will show that specific map layer. At that point, the user can click on any district on that layer to see the popup information.

![]({{ page.img-folder }}gX5dLKn.png)

For the “Why It Matters” story, I created a second html page to display the story behind why Texas isn’t a lost cause. I did most of the map coding inside of Carto and then embedded two maps onto the webpage. Most of the coding on this page took place in HTML and CSS - formatting the flow of the page.  

![]({{ page.img-folder }}QfJauC0.png)

**FUTURE STEPS:**
I hope to continue developing this website to incorporate additional information on each elected official, add in the search by address feature and develop the story section. 

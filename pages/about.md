---
title: About
layout: about
permalink: /about.html
# include CollectionBuilder info at bottom
credits: true
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---

{% include feature/jumbotron.html objectid="mercer-fonthill-museum.jpg %}

{% include feature/nav-menu.html sections="About the Collection;About the About Page" %}

## About the Collection

This project was created by Sara Davis during the workshop "Small Data, Big Dreams: Minimal Computing for Data Collection & Visualization" during <a href="https://pricelab.sas.upenn.edu/events/dream-lab-2025">Dream Lab 2025</a>.

The project uses a subset of the <a href="https://www.datalumos.org/datalumos/project/219155/version/V1/view?path=/datalumos/219155/fcr:versions/V1">Museum Data Files (MDF)</a> published by the Institute of Museum and Library Services (IMLS) in 2018 and preserved on DataLumos. The MDF includes more than 30,000 observations of museums across the United States, segmented by museum discipline. The category "Uncategorized or General Museums" (GMU) includes institutions from maritime museums to historical societies and grantmaking organizations to recreational attractions. Some, but not all, of these institutions have designations from the North American Industrial Classification System (NAICS) and National Taxonomy of Exempt Entities Core Codes (NTEEC). These taxonomies provide a  

For this website, I limited my dataset to GMU observations geocoded in the state of Pennsylvania, which totaled **325** institutions. I also added NAICS and NTEEC categories to the discipline category, which offered a more detailed picture of what these institutions do; unsurprisingly, the largest categories were "Museum" and "Colleges, universities, and professional schools." Yet there are still **142** institutions with no designation beyond "Uncategorized," including the Rosenbach Museum and Library, a historical house and rare book library where I worked in 2016-2018. Thus, this project invites questions that might be answered by different treatments of the IMLS data. For example, are "Uncategorized" museums more likely to be in urban, suburn, or rural locales? Do "Uncategorized" museums exhibit a different revenue range than the total list? Etc. 

The object icons were created by 
<a href="https://www.flaticon.com/authors/freepik" title="Freepik icons - Flaticon">Freepik</a> and represent each museum's locale (city, town, suburb, or rural) as designated by IMLS. 



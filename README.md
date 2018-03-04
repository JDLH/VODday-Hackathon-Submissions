# VODday-Hackathon-Submissions
We participated in the *Vancouver Open Data Day* on 3. March, 2018.

## Team Name
*Team Meta* (Jim DeLaHunt).

## Vancouver Open Data Day Challenge

We didn't particularly focus on the [2018 VODday Challenges](https://www.opendatabc.ca/pages/vodday-2018-vancouver-open-data-day-hackathon#challenges).

## Prototype Problem Statement

My vision is that Vancouver-area open data apps should be localised into all the 
languages in which local residents want them. 

Over [40% of the people in the Vancouver region speak a language other than English at 
home](http://www12.statcan.gc.ca/census-recensement/2016/as-sa/fogs-spg/Facts-CMA-Eng.cfm?TOPIC=5&LANG=Eng&GK=CMA&GC=933), 
says Stats Canada. That is over 1m people of the 2.4m people in the area. 
Now of course localising those apps and web sites is a task for the developer. 
My discipline, internationalisation (i18n), is a set of design and implementation techniques 
to make it cheaper and easier to localise an app or web site. At some point, an app or 
web site presents data sourced from an open data dataset. 

In order for the complete user experience to be localised, the dataset also needs to be localised. 
A challenge of enabling localisation of open data-sourced apps is to set up formats, social 
structures, and incentive structures which makes it easier for datasets to get localised into 
the languages which matter to the end users.

To that end, I picked a modest project for the day. It was to make a 
[language census of the city of Vancouver’s Open Data 
datasets](http://wiki.opendataday.org/Vancouver_Open_Data_language_census). 
The link is to a project page I started on the Open Data Day wiki. 

However, the [Vancouver Open Datasets catalogue](http://data.vancouver.ca/datacatalogue/index.htm) 
is published as an HTML table. It is difficult to copy this table and process it with software. 
So, the first problem to solve was converting this catalogue into a standard, machine-readable format.

## Protoype Summary

Generate a version of the Vancouver Open Data catalogue as a dataset. 

Update the dataset list in the Vancouver Open Data language census with the most recent datasets.

Incremental progress on the language census.


## Open Data Sets

### What Open Data Sets Did You Use?

* [Vancouver Open Data Catalogue](http://data.vancouver.ca/datacatalogue/index.htm)
* The [Project Open Data Metadata Schema](https://project-open-data.cio.gov/v1.1/schema/)

### What Open Data Sets Do You Still Need?
* A dataset containing the *Vancouver Open Data Catalogue*. 
* Translation of Vancouver open data sets into languages used by the Vancouver public

## Prototype

### Live Prototype

Our 2017 work is captured in two wiki pages. Unfortunately this wiki is now read-only, so I couldn’t post updated content there. I may come back to this project, and post the 2018 data somewhere else.
* http://wiki.opendataday.org/Vancouver_Open_Data_language_census \[2017 edition, read-only] lists all the datasets in the Vancouver Open Data catalogue, and notes what kind of language-specific data would need to be translated.
* http://wiki.opendataday.org/Vancouver_Open_Data_Catalogue_dataset \[2017 edition, read-only] is a JSON object listing the datasets in the Vancouver Open Data Catalogue. It is based on the Project Open Data Metadata Schema.

### Presentation

*None.*

## Next Steps

* Complete the Vancouver Open Data language census.
* Define requirements for an open-data-driven service delivered in a language other than English.
* Implement this service
* Translate the datasets needed to drive this service.

## Progress

* Vancouver Open Data dataset catalogue, in JSON based on [Project Open Data metadata schema](https://project-open-data.cio.gov/v1.1/schema/), available at http://wiki.opendataday.org/Vancouver_Open_Data_Catalogue_dataset#Vancouver_Data_Catalogue_in_Common_Core_Metadata_JSON_Format
* Incremental progress on the Vancouver Open Data language census, available at http://wiki.opendataday.org/Vancouver_Open_Data_language_census



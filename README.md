## UFOs - A web page for in-depth analysis of UFO sightings
#
![too hot to handle](https://github.com/jcsargis00/UFOs/blob/main/static/images/ufo.PNG)
## Analysis
#
This module creates dynamic content with JavaScript, HTML, CSS, and bootstrap.
#
## Overview
#
The purpose of this project is to create an interactive web page for Dana's users to parse the data around UFO sightings.
#
### Methodology
#
The data is in a JavaScript data file.  The data was transformed into an HTML table using JavaScript.  The table was built by iterating through an array of objects and appending them to 
a table row.  Code was written to loop through the data rows, with each row containing the contents of one siting, e.g. date, city, state, country, shape of UFO.
#
### Tools
#
The tools used were JavaScript, HTML, CSS and bootstrap.  A web page was built with filter capability on each of the characteristics of a sighting, e.g. date, city, state, country, shape of UFO, allowing a user to select what filtered set of sightings they are interested in.  D3.js was used to listen for events that occur on the webpage, in this case, entering filter parameters. 
#
### Results
#
The dynamic web page allowed filtering based on date, city, state, county and shape.
![web page](https://github.com/jcsargis00/UFOs/blob/main/static/images/webpage.PNG)
# How to perform a search
Using the filter search, on the LHS of the web page, a user can filter by one or all of the search criteria shown. For example, if you search by "Date", you will see that the table updated to show the reported sightings that were recorded for that specific date.
#
![filter search](https://github.com/jcsargis00/UFOs/blob/main/static/images/filtersearch.PNG)
#
The search on 1/1/2010 returns this page of results:
#
![date filter](https://github.com/jcsargis00/UFOs/blob/main/static/images/filterpage.PNG)
#
To search on a sighting specifically on 1/1/2010 in Bonita, CA, US, with shapes = light, type in this information in the filter boxes, as shown below.
#
![filter box](https://github.com/jcsargis00/UFOs/blob/main/static/images/bonita.PNG)
#
To get this search result:
#
![just one choice](https://github.com/jcsargis00/UFOs/blob/main/static/images/bonitatable.PNG)
#
## Summary
JavasScript and the ES6 update from 2015 make complex, interactive form building easier.
This comes in handy for building online shopping websites with many options for shoppers,
tracking large data sets for weather (NSIDC) or large and diverse datasets requiring 
dynamic tables (NEON).
### Drawbacks
#
* The search fields are case sensitive.  If the user enters partial information, no data will be returned.
* There is no enter button, to tell the user the table will run a query and return results
* There is no information about what data is included, how current the site is, or information about how to use the filter windows.
#
### Suggestions for follow on work
#
Additional Recommendations
* Help facilities to suggest what to input
* Drop down boxes for states and countries, and states
* A map showing what areas data about sightings exists
* Information about the sources of data and latest findings
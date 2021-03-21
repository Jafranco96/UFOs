# UFOs

## Overview of Project
### Purpose

A data journalist, Dana, has decided to delve deep into the reported sightings of UFOs for her next assignment. Using a JavaScript file of recorded UFO sightings, Dana wants to publish the data in tabular form within a HTML Page.

In her initial publication of the HTML page, Dana created a table populated with sightings occurrences that could be filtered by the recorded date. Dana soon realizes that the data is too dynamic to only have one filter. As such, she wants to republish the HTML page with four additional table filters. These filters are a city, state, country, and shape filter. With these additional filters, Dana feels that any end-users would be able to exactly pinpoint the occurrences they are searching for.

## Analysis Results 

With the additional filters built, the updated HTML page looks as follows:

<img src ="https://github.com/Jafranco96/UFOs/blob/main/Resources/Webpage_1.PNG">

Before explaining the process of how to use the filters, it is imperative to acknowledge the exact process that the HTML page is using to “look” for changes within the filters. Instead of anticipating a button click, the event listener of the HTML page is anticipating any input changes to the filters. Instead of having to click a button to get to the filtered data, the table will filter automatically when any of the filters have been changed.

As an example, by just inputting a city into the “Enter City” filter, the table instantly updates:

The HTML webpage also has the capability to hold changes to all five filters and, if occurrences with all five parameters exists, the table will be updated as well.


## Analysis Results Summary

While the new HTML page allows for efficient filtering for end-users, there are still opportunities for improvement that could streamline the filtering process. 
For example, how would any end-user unfamiliar with the source data know all the possible parameters for each filter? Particularly for the more subjective categories like “Shape” that has non-intuitive parameters such as “chevron” or “teardrop”.  A recommendation would be to convert the filters from user-inputted to a selected drop-down list. This would give the end-user visibility to all possible input parameters. 

Another recommendation to aid the filtering process would be to create a “Comments” filter. While it is not possible to filter to a specific comment by user input, the “Comments” filter could instead be used to look for specific phrases within the comments text such as “green” or “projectile”.

With these two additional recommendations, Dana could improve the end-user experience of her HTML page to an even greater extent.

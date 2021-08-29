# UFOs
Github Repo for the UFO's sighting's assignment
## Overview of Project
The purpose of this project was to build an HTML page where a user is able to to parse through a JavaScript file by using filters embedded in the HTML page. Instead of trying to sift through an array of objects, the user can see easy-to-understand tabular data where they can filter the data how they please with convenient, dynamic filters.

## Results
The filtering capabilities of the HTML page makes navigating UFO sighting data a breeze. Initially the user is met with a webpage with a large amount of data like so:

![noFilter](https://github.com/typicalchazz/UFOs/blob/main/static/images/no_filter.png)

But by using the filters on the side, the data will be dynamically refreshed and filtered based on user input like so:

![filters](https://github.com/typicalchazz/UFOs/blob/main/static/images/ca_light_date_filter.png)


## Summary
This new site design is great, but a drawback it has is that it doesn't filter for every dimension of the data. Filters for duration (and arguably comments) should be added to the design. To improve this site, I would recommend changing the underlying data source from a static data object and instead plug into a dynamic dataset that will pull live data into the site, as opposed to having to manually update the data array with objects. Another improvement, albeit slight, would to have columns separated with a line to help better differentiate the columns in the data.
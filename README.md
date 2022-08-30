# UFO Sightings : Expanding Filtering Capability of Interractive Web UFO Sighting Table
### Increasing Functionality of Database Data Filtering Using Javascript and HTML 
The purpose of this project is to provide expanded filtering capacity of a provided database of UFO sightings. The ultimate deliverable is an interractive table hosted on an html website that allows website visitors to filter through the database using multiple criteria and execute a very pointed search. We're adding 4 additional filter criteria to the original "date" criteria; city, state, country, and shape.

### Results: Original Search Engine
Before any manipulationg of the filtering function, users could screen the data using a filter on the "date" data only. The table had an input function, once users supplied a date, could use the "filter" button and return their results, as seen below. The client wanted users to be able to screen the data and more criteria and have the search experience be more intuitive.
! insert image of original website with just date search here
In order to create additional filter criteria the source code was updated in 2 places: the html.index and app.js files. The html file needed to be edited to include iterations of the <li /> items so that visitors could see input boxes for city, state, country and shape below the original "date" input box. New html code highlighted in yellow.
! insert image of the aditionall list items.
Because the html.index and app.js work in concert, the code that executed the filter function needed to be revamped to allows for multiple criteria.
! insert image of additional function
An additional function was added to take in any changes in the input. Once the function reads the updated filter criteria, for loop to iterate, build the table with date that meets filtered data criteria. The action that reads this is built on "change" not "click" which allows users to simply enter input and hit return, making the experience immediate and intuitive.
! insert image here of all filters with input




### Summary: In a summary statement, describe one drawback of this new design and two recommendations for further development.
missing feedback loop of button push. 


The summary addresses one drawback of this webpage (2 pt) many people look for visual cues, generally built into the sight structure, that show a visitor how to navigate through the space. These feedback loops increase userability and mitigate frustration and ultimately visitors navigating away from the sites before finding their target information. While the shift away from the button to detecting change in input might increase functionality but . . . Create the site to return the filtered data either by hitting return after each criteria or hitting the filter data button.

the current user interface with the dataset assumes some user knowledge and might alienate some visitors. The table would be more inclusive to all visitors if the search criteria for city, state, country and shape had drop down menus with lists of all possible acceptable entries.

A button that allows visitors to download the dataset. Especially powerful to allows visitors to download the dataset filtered by their user criteria.

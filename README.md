# UFO Sightings : Expanding Filtering Capability of Interractive Web Table
## Increasing Functionality of Database Filtering Using Javascript and HTML 
The purpose of this project is to provide expanded filtering capacity on a provided database of UFO sightings. The ultimate deliverable is an interractive table hosted on an html website that allows website visitors to filter through the database using multiple criteria and execute a refined search. We're adding 4 additional filter criteria to the original "date" criterion; city, state, country, and shape.

## Adapting Search Engine Filtering Function Results
The original table allowed users could screen the data using a singular filter on the "date" criterion. The table allowed for one input function and in order to execute the search using the filter users were required to click the "search" button. In addition to adding more filter criteria to the database table, the client wanted to users to be able to return results at each input by simply hitting the "return" key and increase the intuitive use of the website. The original website search function is pictured below.
! insert image of original website with just date search here
In order to create additional filter criteria the source code was updated in 2 places: the "html.index" and "app.js files". The html file was edited to include multiple iterations of the "<li />" tag that holds the label and input functions. As seen below 4 "<li />" tags were added to house each of our new filters, as seen by the highlighted code in the image below.

![Screen Shot 2022-08-30 at 7 01 13 PM](https://user-images.githubusercontent.com/107326987/187576909-8e3e6013-852d-44c2-867c-fbc51ee88bd6.png)

Because the html.index and app.js work in concert, the code that executed the filter function needed to be revamped to allow for multiple criteria inputs. In the below image we have a snapshot of the new function that creates variables to hold the values of the updated filter id's. 

![Screen Shot 2022-08-30 at 7 03 05 PM](https://user-images.githubusercontent.com/107326987/187576935-cdb57795-9902-4edd-ba24-bebcaeee175d.png)

Furthermore, the "event listener" code needed to be updated to be triggered into action at any "change" of users input in the filter elements instead of listening for the "click" of a search button. Below is the edited "event listener" action code. 

![Screen Shot 2022-08-30 at 7 01 59 PM](https://user-images.githubusercontent.com/107326987/187576954-5b6ae2f3-2180-4354-9bed-c3a42f3ae51e.png)


Once the new function to hold multiple filter input is created, the remaining code can iterate through the table and find rows of data fro the database that meet the filtered search criteria of the users input. Below is an image of the 5 total search boxes in use, returning a filtered search of the database.

![Screen Shot 2022-08-30 at 7 04 39 PM](https://user-images.githubusercontent.com/107326987/187576981-0f6e2869-e1be-4e5a-aa93-829dcd80612b.png)


### Assessed Userability of Site Filtering Function and Further Development Recommendations

The summary addresses one drawback of this webpage (2 pt) many people look for visual cues, generally built into the sight structure, that show a visitor how to navigate through the space. These feedback loops increase userability and mitigate frustration and ultimately visitors navigating away from the sites before finding their target information. While the shift away from the button to detecting change in input might increase functionality but . . . Create the site to return the filtered data either by hitting return after each criteria or hitting the filter data button.

the current user interface with the dataset assumes some user knowledge and might alienate some visitors. The table would be more inclusive to all visitors if the search criteria for city, state, country and shape had drop down menus with lists of all possible acceptable entries.

A button that allows visitors to download the dataset. Especially powerful to allows visitors to download the dataset filtered by their user criteria.

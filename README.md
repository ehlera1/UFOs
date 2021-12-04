# UFO Analysis - Interactive Webpage
## Project Overview

The purpose of this analysis was to create an interactive webpage that allows readers to review data in relation to UFO sightings. We partnered with Dana, a data journalist to complete our analysis as she had a vision for how the interactive webpage should be structured with a table that can be easily filtered by users. While previously working with she provided with us with the raw data in a JavaScript file. We then looped through that file to create a clean table that could easily be filtered based on a user’s input. Using HTML, Bootstrap, and CSS we were able to construct a simple webpage that will allow users to explore data on UFO sightings. 

## Tools/Programing Languages Used 
-	JavaScript, HTML, Bootstrap, CSS 

## Results
The webpage we created is structured into a few key elements that users will want to interact with. If you notice the red boxes over the areas in the image below, on the lower left-hand side of the page there are attributes that will allow users to filter their search (we’ll go in to greater detail on how use the filters in a moment) and in the lower center-right the data that is returned from the filters is present. 
Webpage Sample: 

![TheTruthIsOutThere](https://user-images.githubusercontent.com/90698381/144724133-c6e3c24b-2e5f-4f37-8e75-3412ab5914c0.png)


Filtering this data is relatively strait forward and filters can easily be added or deleted depending on what data users would like to see. By reviewing the columns listed in the table, you can filter on the Date, City, State, Country, and the Shape of the object spotted. Users can simple use one of these filters to narrow their search or multiple. 
For example; If someone wanted to search and focus on sightings in the city of Benton, they could type “benton” into the Enter a City box to return sightings for only cities with the name Benton. 

![CityFilter](https://user-images.githubusercontent.com/90698381/144724141-5bd57111-91e5-49cc-8617-52eaf67b3ac2.png)


Or if a user wanted to see sightings using multiple filters such as "date" and "state" they could enter that information to further filter the table. In the below example, we filtered with a date of 1/4/2010 and only in the state of CA. 

![DateState](https://user-images.githubusercontent.com/90698381/144724145-f461d53d-f0ca-43c0-b456-e80fcbc743dc.png)



## Summary 

### Drawbacks
While the page is relatively intuitive and easy to navigate it’s simplicity does have a couple drawbacks. 
-	The search fields are case-sensitive and the table will not update correctly unless the filter criteria perfectly matches what is listed in the table. 
-	There is also no button or call to action that users need to preform to update the table. This may have some users concerned that the table did not update when they entered their filter requirements. 

### Recommendations for Further Development 
-	If we were to publish the webpage we would recommend connecting it to a live data source so the information is up-to-date. 
-	We would also recommend that the filtering functionality be further refined with a click-button, drop down lists or that auto-fill functionality be added so users can more easily narrow their search results. 

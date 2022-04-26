# UFO
## Overview 
The purpose of this analysis was to assist Dana, a data journalist, in the development of her new article: UFO sightings throughout the United States. In order to have a strong foundation for her article, I have created a JavaScript interactive web-page where users can filter through the various UFO sightings data. The web-page provides:

- Introductory article 
- Eye-catching header for curious minds
- Data displayed in a table format that allows for users to filter for multiple criteria (date, city, state, country, and shape of sighting)

## Results
To perform a search, the user begins by accessing the full webpage. 
![This is an image](https://github.com/leilacf/UFO/blob/main/UFO%20main%20page.png)

The dynamic table can be found on the bottom right-hand corner, with the subsequent filter on the left.

![This is an image](https://github.com/leilacf/UFO/blob/main/UFO%20table%20and%20search.png)

Depending on the users input into the filter, the table will update to reflect the particular data the user is looking for. The default information on the filter provides the user the format their search query should follow. 

For example:
- the date should be entered in the format of M/DD/YYYY, indicating that there is 1-digit month, seperator, 2-digit day, seperator, and 4-digit year
- City, State, and Country are all lower case
- Shape requires a 1 word search

![This is an image](https://github.com/leilacf/UFO/blob/main/UFO%20filter%20search.png)

The new data will then be shown in the table. Upon finalizing their search, the user can manually clear the filter input or refresh the page to start again.

## Summary
The creation of this webpage required our data source in a JavaScript list, VS code, JavaScript, HTML, CSS, and Bootstrap 3. Despite its great features and functionality, it is not yet at its optimal use. A few drawbacks of this current version includes:
- The filter system is quite limited and does not allow for users to conduct a more granular level search 
- Users cannot add or submit for review, their own new UFO sightings to keep the data up-to-date 
- The entirety of our data set is displayed at once when opening the webpage which makes it visually heavy
- Reseting the filter requires manual work if one does not refresh the page

In addressing these drawbacks, below are a few reccomendations for further development:
- Converting the filter conditions to allow for users to search in either lower or upper case to facilitate their experience and not run into errors
- Creating a submission entry box so that users can provide continuous data on their sightings and keep the table updated
- Updating the filter with either more search criteria options or a drop down menu that can assist in initializing their inquiry

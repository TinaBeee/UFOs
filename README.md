## UFOs - JavaScript, HTML & CSS
Creation of an website on supposed UFO sightings that includes an interactive table component that allows users to filter the data

### Resources
- Data Sources: data.js (contains reported suspected UFO sightings with data, location, shape of sighting and additional details)
- Software: Visual Studio Code 1.60.0, Node.js 16.13.1, d3 library, Bootstrap 4.0.0

## Results
Website features panoramic picture below navigation bar and text describing the project. Below the text fields, users can input search parameters in the filter field on the bottom left of the page to sort the raw data on the bottom right of the page.

The navigation bar titled "UFO Sightings" can be clicked to refresh the raw data and clear all filters.

<img src="https://user-images.githubusercontent.com/90064437/148699236-69659fad-fb4d-4505-87ba-fe14aa9d75a3.png">

Placeholder text inside the filter boxes allows the user to see the format of each filter option.

<img src="https://user-images.githubusercontent.com/90064437/148699276-c26bd5ec-d083-4f66-bc1e-aa27e58788e2.png">

The user can enter search criteria in one or several of the search fields, with the app's code in the backend storing any search criteria inside an initially empty filters object. If a user subsequently clears the filter, that filter criteria gets deleted from the filters object.

Filtering the dataset for sightings in the state of Florida on January 1, 2010:

<img src="https://user-images.githubusercontent.com/90064437/148699487-b9a855e4-8b7d-48dc-b09c-a05592280e9a.png">

Deleting the date from from the date time filter:

<img src="https://user-images.githubusercontent.com/90064437/148699554-eb402bf5-7b39-4157-968f-065fb8b76604.png">

## Summary
In an initital version of the website, the only filter option was the date, followed by a botton users could click on to filter th date. When additional filter criteria was added to the code, the botton was deleted, meaning website users now have have to press enter or click outside the form field to execute their filter criteria. 
Given the length of the dataset, users can also not easily tell, which data is available inside the set. When searching for the date, for example, it is unclear which range the data covers, so users would have to enter various dates in trial and error fashion. The filter box could be improved by offering filters on a select, existing data parameters.



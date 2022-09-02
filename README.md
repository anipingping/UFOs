# UFOs - They Are Out There

## Overview of the Analysis
This analysis constructed a webpage and dynamic table that allows users to search and filter a dataset of UFO sightings with multiple criteria. Specifically, visitors to the page can filter for sightings by date, city, state, country and shape of the sighting.

## Results
Visitors to the page can use the website by typing filter parameters into 5 fields: date, city, state, country and shape (of the object reported). In the screenshot below, a user has filtered the dataset down to sightings in January 2010, specifically 1/12/2010, in the city of Eugene, in the state of OR, and one sighting from the dataset has been returned:
![Screenshot_Eugene_OR](https://user-images.githubusercontent.com/106618404/188243526-5f1648cd-12e7-47ab-b024-b0cf1b7e8c19.PNG)

## Summary - A description of one drawback and 2 recommendations for further development

### One Drawback
There are several pretty serious flaws in the current design of the website but potentially the most serious is the inability of the filtering script to account for small changes in the way filter data is keyed in. A user filtering for cities must type the city EXACTLY as the dataset is storing it. Eugene OR for instance must be filtered for using all lowercase letters "eugene". If a user types in "Eugene" using proper capitalization, the table will not return any data because Eugene is different than eugene. See the example below:
![Eugene_no_data](https://user-images.githubusercontent.com/106618404/188244150-bf955bc1-4446-4705-b252-6bb1bad0cdb4.PNG)

### 2 Recommendations for Further Development
1. Obviously, to correct the drawback just described, we need to adjust the script driving the filters for more flexibility in typing entries into the filter fields. That change will enormously enhance the user experience.
2. A second recommendation for further development is to add an option for the user to extract the filtered results as a data file, such as a .csv or .txt file, which they can then pull down into Excel on their computer. This type of functionality is available on many different websites including Peloton, the Bureau of Labor Statistics, and even my local credit union bank account summary. This type of functionality will provide the user with data that they can take away from the website rather than being limited to just what the page shows at any given moment.

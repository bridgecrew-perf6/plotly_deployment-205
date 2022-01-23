# plotly_deployment
# UFOs

## Overview 
The purpose of this project is to assist my client (Probable Beef (PB)) with producing a webstie using JavaScript.  My client has collected data in hopes to determine what species colonize an individual's belly button.  This information will be used to help my client produce a protein that tastes like beef.  My first sprint delivered a site with a dashboard of demographic information of volunteers participating in this data collection.  PB, would like me to visualize the bacterial data for all their volunteers.

My final sprint will include adding three (3) specific visualization which are identified below.  As always, my analysis followed the data analysis principles of (1) Determine the number of rows and columns; (2) Data types used; and (3) Is the data readable?

__Client Expected Results:__
- Visualize the top 10 bacterial species in an individual's navel using a Horizontal __Bar Chart__
- Visualize a voluteer's wash frequency using a __Gauge Chart__
- Visualize the bacteria cultures per sample using a __Bubble Chart__


## Resources
The resouces used develope this JavaScript application included;
- Visual Studio Code
- HTML
- JavaScript/JavaScript Events
- BootStrap
- D3 (Data-Driven Documents)
- Sample.json (JSON data file)

## Results
All sprints were completed as scheduled and I delivered on all client expectations/results.

__Deliverable 1:__ Creation of dasboard related to a volunteers' demographics
- Looking at the below visualization you can see how easy on the eyes this website is.

![Demograhic Information](https://github.com/SheaButta/UFOs/blob/main/static/images/UFO_Orig.PNG)

__Deliverable 2:__ Creation of three (3) visualizations charts that reflects the data


__Visualization 1 - Visualize the top 10 bacterial species in an individual's navel:__

![](https://github.com/SheaButta/UFOs/blob/main/static/images/ScreenShot_NoFilters.PNG)


__Visualization 2 - Visualize a voluteer's wash frequency:__

![](https://github.com/SheaButta/UFOs/blob/main/static/images/ScreenShot_NoFilters.PNG)


__Visualization 3: Visualize the bacteria cultures per sampl__

![](https://github.com/SheaButta/UFOs/blob/main/static/images/ScreenShot_NoFilters.PNG)


- The below visualization illustrates the first filter on the date; however, __the filter has NOT been applied.__  The application is listening for a change and once a user hits the tab key the filter will be applied.

![Filter on date - NO Filter Applied](https://github.com/SheaButta/UFOs/blob/main/static/images/ScreenShot_DateFilter.PNG)

- The below visualization illustrates an applied filter on date.  You can clearly see the amount of data has decreased since applying the date filter.
 
![Filter on date - Filter Applied](https://github.com/SheaButta/UFOs/blob/main/static/images/ScreenShot_DateFilterResults.PNG)

- The below visualization illustrates an __applied filter on date ONLY__; however, another filter is about to be applied on city.  
 
![Filter on date and city - One Filter Applied](https://github.com/SheaButta/UFOs/blob/main/static/images/ScreenShot_Date_CityFilter.PNG)

- The below visualization illustrates an __applied filter on date and city.__  The results have decreased yet again since applying the filter on date and city.
 
![Filter on date and city - Two Filters Applied](https://github.com/SheaButta/UFOs/blob/main/static/images/ScreenShot_DateCityFilterResults.PNG)


## Summary
Since adding this new design for my client, there may be a drawback of user control.  There are some users who like to control when and how they perform searches which would lead back to the "onClick" event.

Besides this drawback, I would like to recommend the following two (2) improvements;
1. Using a drop-down list to select a search criteria. Typing search criterias would be reduced.
2. Look for a different bootstrap class to help align the "input" tag under the "label" tag all the time.  This would improve the visualization and keep these tags from moving around on the website as you change screen sizes.



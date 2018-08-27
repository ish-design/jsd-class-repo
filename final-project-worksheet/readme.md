# Project Overview

## Project Schedule

This schedule will be used to keep track of your progress throughout the week and align with our expectations.  

You are **responsible** for scheduling time with your squad to seek approval for each deliverable by the end of the corresponding day, excluding `Saturday` and `Sunday`.

|  Day | Deliverable | Status
|---|---| ---|
|Aug 27th| Project Description | Incomplete
|Sep 5th| Wireframes / Priority Matrix / Functional Components | Incomplete
|Sep 10th| External API(s) Decision / Core Application Structure (HTML, CSS, etc.) | Incomplete
|Sep 17th| Minimal Viable Product | Incomplete
|Sep 26th| Styling / Bug Fixes | Incomplete


## Project Description

### State Tastes

#### What
The vision for this project is a choropleth map of the US that is broken down by the specific tastes for each state/region. The tastes will come from venues that are prevelant to those areas and may not necessarily revolve around just food. Neighborhood with large amount of pizza places would end up falling under the over arching taste of "pizza" whereas another that has mostly music shop might be considered "music lovers".

##### Examples and Resources
[Mapbox 1](https://www.mapbox.com/help/choropleth-studio-gl-pt-1/)<br />
[Mapbox 2](https://www.mapbox.com/help/choropleth-studio-gl-pt-2/)<br />
[Mapbox by zoom](https://www.mapbox.com/mapbox-gl-js/example/updating-choropleth/)


#### How
The necessary data is pulled from the [Foursqaure API](https://developer.foursquare.com/) and the map rendered with [Mapbox](https://www.mapbox.com/). From the API i'll be able to pull venue Lat/Lon's and drop them onto a stylized mapbox map. The app's functions and interactions are powered by the Mapbox JS library and possibly some custom JS, and consits of the follwing:

##### State Borders and Location
Ability to break down the map by regions and drop the Foursquare Lat/Lon in their corresponding locations.

##### Aggregated Tastes
Lopping through the API results in order to display only the predominant tastes.

##### Hover
Display some information(predominant taste, state name, #of venues, etc) regarding the state the usre hover over. 

##### Zoom Function (nice to have)
Affect information being displayed depening on user's zoom level. 

##### Resources
[Foursquare endpoint](https://developer.foursquare.com/docs/api/endpoints)
[Foursquare venue details](https://developer.foursquare.com/docs/api/venues/details)
[Mapbox Studio](https://www.mapbox.com/mapbox-studio/)


[I'm an inline-style link](https://www.google.com)

## Wireframes

Upload images of wireframe to cloudinary and add the link here with a description of the specific wireframe.

## Priority Matrix

Include a full list of features that have been prioritized based on the `Time and Importance` Matix.  

### MVP/PostMVP - 5min

The functionality will then be divided into two separate lists: MPV and PostMVP.  Carefully decided what is placed into your MVP as the client will expect this functionality to be implemented upon project completion.  

#### MVP 

- Find and use external api 
- Render data on page 
- Allow user to choose favorites 
- Save their choices in firebase

#### PostMVP 

- Add user auth

## Functional Components

Based on the initial logic defined in the previous  phases section try and breakdown the logic further into functional components, and by that we mean functions.  Does your logic indicate that code could be encapsulated for the purpose of reusablility.  Once a function has been defined it can then be incorporated into a class as a method. 

Time frames are also key in the development cycle.  You have limited time to code all phases of the game.  Your estimates can then be used to evalute game possibilities based on time needed and the actual time you have before game must be submitted. 

| Component | Priority | Estimated Time | Time Invetsted | Actual Time |
| --- | :---: |  :---: | :---: | :---: |
| Adding Form | H | 3hrs| 3.5hrs | 3.5hrs |
| Working with API | H | 3hrs| 2.5hrs | 2.5hrs |
| Total | H | 6hrs| 5hrs | 5hrs |

## Helper Functions
Helper functions should be generic enought that they can be reused in other applications. Use this section to document all helper functions that fall into this category.

| Function | Description | 
| --- | :---: |  
| Capitalize | This will capitalize the first letter in a string of text | 

## Additional Libraries
 Use this section to list all supporting libraries and thier role in the project. 

## Code Snippet

Use this section to include a brief code snippet of functionality that you are proud of an a brief description  

```
function reverse(string) {
	// here is the code to reverse a string of text
}
```

## jQuery Discoveries
 Use this section to list some, but not all, of the jQuery methods and\or functionality discovered while working on this project.

## Change Log
 Use this section to document what changes were made and the reasoning behind those changes.  

## Issues and Resolutions
 Use this section to list of all major issues encountered and their resolution.

#### SAMPLE.....
**ERROR**: app.js:34 Uncaught SyntaxError: Unexpected identifier                                
**RESOLUTION**: Missing comma after first object in sources {} object

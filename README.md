# ufo-s
# Overview of Project:
Using Javascript and HTML to develop a webpage which contain a dynamic table to filter for and review UFO sightings.

# Purpose:
Using Javascript and HTML to develop a webpage that has a dynamic table to filter for and review UFO sightings. The dynamic table features multiple filter criteria (date, city, state, country, and shape) that can be used individually or in combination for further refinement.

Webpage Results and Challenges:
Webpage Use and Navigation:
The UFO sightings webpage has been configured to offer multiple filter criteria settings in order for users to review UFO sightings that match their search criteria. To focus a users review of UFO sightings, filter criteria are available for UFO sighting date, city, state, country, and shape. Each filter criteria can be populated individually or in combination to further refine search results. Example values have been pre-populated into each filter criteria field for users to see the filter's format criteria value should be entered. After populating at least one filter criteria with a search value and pressing either the Enter or Tab key, the table will update to reflect the UFO sightings that match the filter criteria value entered. Below are two illustrations that reflect (1) the full website without any filter criteria entered, (2) the updated table when a filter criteria value is entered (in this case, a state of "nm" is entered for New Mexico).

#### Website Screenshot
![im1](https://user-images.githubusercontent.com/63277310/119300137-42ca3e00-bc2e-11eb-9686-a70fbd48ea10.png)

#### Website Screenshot with State Filter Entered
![im2](https://user-images.githubusercontent.com/63277310/119300290-82912580-bc2e-11eb-8755-1f67d158d189.png)

When the filter criteria are used in combination with each other, the table will display results for the first criteria value entry and then further refine the results based on the second filter criteria value entry. Below is an illustration of a two criteria filter setting (in this case, a state of "nm" and a shape of "light").

#### Website Screenshot with State and Shape Filters Entered 
![im 3](https://user-images.githubusercontent.com/63277310/119301104-f08a1c80-bc2f-11eb-8b5a-2a63ef56a669.png)

Once filter criteria values entered have been cleared (e.g. deleted), the table updates to reflect either the remaining filter criteria (if a combination was used) or returns to its original state where all UFO sightings are listed in the table. See above Website Screenshot for reference of the webpage's original or starting state.

#### Challenges and Difficulties Encountered
The only challenge experienced while re-configuring the webpage to contain multiple filters was ensuring the index and app file references were aligned. Also, applying the appropriate formatting updates to the Filter box required some finessing.

# Summary
A drawback of this new design is that the user must have a good idea of the filter criteria values that they would like to enter or they will return no results. For example, conspiracy theorists would presume there are UFO sightings in the city of Roswell as the default example city value in the website suggests. But when "roswell" is entered as a City filter value, no results are returned and the table is empty. A dropdown menu to either select or enter Filter Search criteria values that correspond to results would be more user friendly.

In addition to drop down menu selection options for the Filter search criteria, the following two recommendations would also enhance the webpage:

If no search results are returned from a Filter criteria value entry, the table should communicate "No Results Found" so that users do not think there is an issue with the filtering capability of the webpage.

It is difficult to differentiate between the default filter criteria value examples displayed in the webpage when no filter criteria is set from the actual filter value entries input by users. The design should be updated to clearly make a difference between the default values from the user entered values by either changing the font color or making the font bolder or darker for user entered values. This differentiation will allow users to clearly recognize when filter criteria values have been entered, and which they would like to change or remove as they are performing their review.

# Website Screenshot Filter Value Entry Comparison
![im4](https://user-images.githubusercontent.com/63277310/119301407-727a4580-bc30-11eb-9a35-0d0c2e151439.png)

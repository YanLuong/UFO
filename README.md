# UFO


### Background:

Dana is a data journalist from McMinnville, Oregon. The town is famous for UFO sightings. She has a keen interest in UFOs and was given an opportunity to investigate and write about the UFO sightings. The data she analysed was in a Javascript file which she published to a webpage displaying the data in a table format.

### Overview of the analysis:

Currently, Dana's website only allows you to filter the table by only one search criteria (date) which is inputted by the user. Dana's objective is to further refine the filter search function to allow for additional search criterias such as city, state, country and shape. By allowing users to filter by multiple search criterias, it will allow for a more in-depth analysis. To carry out multiple search criterias, the event listener will be modified to detect changes in each filter.

----

### Results:

Dana's webpage is fully functioning now.

Follow the steps below to perform a search:

|      Image       |  Filter Guide           |
| ----------- | ----------- |
| ![input](https://github.com/YanLuong/UFO/blob/main/static/images/input_text.png)   | Navigate to left of the page (as shown in left image) and enter a specific search or multiple criterias. If entering a date, follow the date format that is suggested in the 'Enter Date' search box. Once you have entered a search criteria, you must either click 'enter' on your keyboard/keypad or right click the mouse. This will trigger a "change" event if search criterias are inputted.     |
|![2 filters](https://github.com/YanLuong/UFO/blob/main/static/images/az_filter.png) |  In the left image, we have an example of a search criteria filtering out the results by state. In the state text box, 'az' was entered to filter out only results that occurred in 'az'. If you enter 'az' in the state text box, you should see the same results being filtered out.   |
|![all filters](https://github.com/YanLuong/UFO/blob/main/static/images/all_filters.png)| On the left, we have an example of the results being filtered with all search criterias. To do a multiple search criteria, you enter each search criteria in the search text box and remember to click 'enter' or right click on the mouse to trigger the search. You should see the filtered results based on all the criterias that was entered.            |


----

### Summary:

After reviewing the UFO webpage. The search function can be improved. At the moment it is not very intuitive. For example, after a search criteria has been entered, it will not prompt the user how to trigger the search. Usually, there is a 'search' button that will commence the search and filter the results. Another aspect that can be improved is to show how many results are found and returned especially if there is a large number of results. This feedback will also help the user to decide whether the search should be further refined to narrow the results. Currently, if no results are found there is no indication of that other than blank results in the table so the user would have to automatically assume that there is no match.

### Recommendation:

  * The webpage could be further improved by having a 'search' button to begin the search. As of now, there is no indication to the user on how the search is triggered other than trying out to see what works. From an accessibility point of view, it will help the user navigate around the page if there is a 'search' button. Once a search has been performed, an ideal result will also indicate how many results (or none) are returned and matched the search criteria.
  * Another recommendation that can enhance the user experience is having a clear filter button. After a user has performed a search and filtered the results, to perform another search again will require the user to manually clear each search criteria that was entered previously. This is quite a tedious process which can be replaced with button to clear all the previous search criterias.

# UFOs

## Overview of the project

Dana is a data analyst and she has just chosen to write an article on UFOs. She has a JavaScript file filled with informations on UFOs in different cities, States, and types of sighting. Her plan is to use JavaScript to display the data in tables and use filters to help others find the details they are interested in. As her article will be posted online, she will present her results and analysis in an HTML page where data and filters will be available. 

## Presentation of the webpage

Dana webpage is easy to understand and to use. The table you access is a record of all the data she has. You have access to the folowing details:
  * the date of the UFO appearing,
  * city
  * state,
  * country,
  * shape,
  * duration of the event,
  * comments.

![Webpage](https://user-images.githubusercontent.com/85641189/132380784-326746c5-010c-4dcf-981d-cbfca4f6ab2c.png)

With around hundred UFOs records, we created a filter in order to check the information you are interested in. On the left side of the webpage, you have a filter tool which proposes five filter options:
  * filter by date,
  * filter by city,
  * filter by state,
  * filter by country,
  * filter by shape.

In order to perform a search, you have to enter your search criteria (either date, city ...). You will have to press on the "Filter table" button.

![Filter_options2](https://user-images.githubusercontent.com/85641189/132382867-f213e943-ceed-4ca7-9921-c717ba395c43.png)

## Summary: improvement opportunities

In order for the users to have a perfect experience with the webpage, I would recommend Dana to specify the date format with MM/DD/YYYY. The webpage does not specify the period of time during which the UFOs records were made. It will be easier for the users to have a tip on the date format. The code in the index.html file should be as followed:
```
 <li class="bg-dark list-group-item">
                      <input type="text" placeholder="MM/DD/YYYY" id="datetime" />
                      <label for="date">Enter Date</label> 
                    </li>
```

I would also recommend Dana to create filters with submenus. Like for the date, the users do not have any details on the cities, states, and countries where the UFOs events were recorded. If Dana creates a submenu for each of those filters, the users will be able to chose between the available choices. Creating a submenu is also a way to avoid any mispelling and misformating (lower case or upper case) from the users.

I have the same recommandation for the shape. The search would be easier if the users have access to a list of choices available in the database.


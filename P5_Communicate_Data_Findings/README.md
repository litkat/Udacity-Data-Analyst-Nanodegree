### Communicate Data Findings for the dataset Ford GoBike System Data ###

The data set includes information about individual rides made in a bike-sharing system in February, 2019. The total amount of data items (rides) in the dataset after cleaning all incorrect data is 174952. The data for this dataset was downloaded from Udacity. In this analysis, the main interest is the data associated with the user, as well as the features associated with the movement of the users.
I find it useful for business to have an information about the most popular stations, user routes, and the hours and days of the week when users are most active in rental.

**Summary of observations:**

- A huge part of the dataset is occupied by subscribers: 90.5% and only 9.5% are client users.
- Users with gender "Male" occupy the majority of the dataset. But also a small percentage of the 'Other' genders.
- The most common birth years of users belongs to 1988, i.e. users who are 31 years old.
- Most of the trips take between 250 and 600 seconds or about 4 and 10 minutes. This suggests that users prefer short routes in terms of duration.
- The most popular starting station is the station called 'Market St at 10th St' with a сount of 3649.
- The most popular ending station is the station called 'San Francisco Caltrain Station 2 (Townsend St at 4th St)' with a сount of 4624.
- Male users in general have shorter trip duration, than Female and Other users.
- Subscribers usually use bicycles for much shorter trips than Customers.
- Regardless of the user type the most popular time to pick up the bike is around 8 and 17 o'clock. Based on this we can conclude that majority of people use this service to get to their work place and back.
- Also, regardless of the type of user, the busiest day is Thursday, which is quite unexpected.
- Subscriber journey times are almost equally distributed up to age 63 and then reduced. For customers, the difference is more noticeable, with the longest trips made by users between the ages of 20 and 40. We also found that customers have more long trips than subscribers.   
- The most popular route is from 'Berry St at 4th St' to 'San Francisco Ferry Building (Harry Bridges Plaza)' with the count of 327 rides.

**Key points for presentation:**   

For my presentation, I decided to include observations related to such parameters as types of users (subscribers / non-subscribers) and their travels (trip duration, popular stations, routes, etc.).   

**A summary of data processing for this project can be viewed here:** 

[exploratory data analysis](exploration_dataset_Ford_GoBike.ipynb) - includes all parts of data processing.   
[explanatory data analysis](slide_deck_for_the_dataset_Ford_GoBike_System_Data.ipynb) - part of data visualization for an external audience.   
[slide deck](slide_deck_for_the_dataset_Ford_GoBike_System_Data.slides.html) - slide presentation.   

**Supporting resources:**   

https://stackoverflow.com/questions/38933071/group-by-two-columns-and-count-the-occurrences-of-each-combination-in-pandas   
https://stackoverflow.com/questions/25068384/bbox-to-anchor-and-loc-in-matplotlib   
https://pandas.pydata.org/docs/reference/api/pandas.Series.dt.dayofweek.html   
https://seaborn.pydata.org/generated/seaborn.heatmap.html   

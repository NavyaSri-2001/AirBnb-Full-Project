# AirBnb-Full-Project

Link to the Dashboard : https://public.tableau.com/app/profile/navya.as/viz/AirBnBFullProject_16944649364990/Dashboard1

# Steps:
Use case: If someone wants to start a house renting business, he should know what factors he should consider, how to put it up on airbnb and start renting, at what price etc.
He should consider factors like location, price, bedrooms etc. He has to optimize and get maximum profit.
1. Took the dataset from kaggle. There are 3 csv files namely calender.csv, lisitings.csv, reviews.csv
2. We joined all the csv files in tableau using inner join based on listing_id column.
3. The dataset has multiple columns like listing_id, listing_url, location, name, price, no.of beds, no.of bedrooms, price, price per extra person, id of reviwers, comments by reviewers, date, status of room-taken/vacant etc

Made 5visualizations. Their usecases:
1. avg price per zipcode bar graph: To know which location has highest price, to make more profit
2. avg price per zip code map: Just to see a different visualization
3. price per year filtered on weekly basis on x-axis: If a user wants to rent it only on specific periods and use it on his own in other times. Based on the graph we can see that summer time and year end are the highest priced.
4. avg price per no.of bedrooms bar graph: We can see that as the no.of rooms of a house increase, it's avg is significantly increasing.
5. distinct count of houses with different no.of bedrooms: We can see the single bedroom houses are high and no.of houses with higher of rooms is drastically decreasing.
   

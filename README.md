# Heroes_of_PyMoli - Pandas Assignment
DataAnalytics BootCamp Using Pandas

## Background
Now, it's time to take what you've learned about Python Pandas and apply it to new situations. For this assignment, you'll need to complete one Data Challenge.

After a lot of hard work in the data munging mines, you've landed a job as Lead Analyst for an independent gaming company. You've been assigned the task of analyzing the data for their most recent fantasy game Heroes of Pymoli.
Like many others in its genre, the game is free-to-play, but players are encouraged to purchase optional items that enhance their playing experience. 

### Tasks
As a first task, the company would like you to generate a report that breaks down the game's purchasing data into meaningful insights.

The final report includes each of the following:

### Player Count

* Total Number of Players

### Purchasing Analysis (Total)

* Number of Unique Items
* Average Purchase Price
* Total Number of Purchases
* Total Revenue

### Gender Demographics

* Percentage and Count of Male Players
* Percentage and Count of Female Players
* Percentage and Count of Other / Non-Disclosed

### Purchasing Analysis (Gender)

* The below each broken by gender
  * Purchase Count
  * Average Purchase Price
  * Total Purchase Value
  * Average Purchase Total per Person by Gender

### Age Demographics

* The below each broken into bins of 4 years (i.e. &lt;10, 10-14, 15-19, etc.)
  * Purchase Count
  * Average Purchase Price
  * Total Purchase Value
  * Average Purchase Total per Person by Age Group

### Top Spenders

* Identify the the top 5 spenders in the game by total purchase value, then list (in a table):
  * SN
  * Purchase Count
  * Average Purchase Price
  * Total Purchase Value

### Most Popular Items

* Identify the 5 most popular items by purchase count, then list (in a table):
  * Item ID
  * Item Name
  * Purchase Count
  * Item Price
  * Total Purchase Value

### Most Profitable Items

* Identify the 5 most profitable items by total purchase value, then list (in a table):
  * Item ID
  * Item Name
  * Purchase Count
  * Item Price
  * Total Purchase Value

### Final Observations.

* Pandas Library and the Jupyter Notebook are used.
* A written description of three observable trends based on the data.


## Analysis Results
From the obtained results. We can see that:

* Male players are more common than female or non-disclosed players. Male players represents more than 3/4 from the total player counts, while female players represents less than 1/4.

* It is also clear that male players spend more money purchasing items for the game than female players or other kind of players. With more than 5 times the money spent for this purpose. BUT we also see that in average, each female and even each other player spent more money than the male players. (in average each male player spent $4.07, while each female $4.47 and non-disclosed $4.56, per person.

* Having a look at the age. People between 20 and 24 years old are more likely to do this kind of purchases, and they are also the kind of people that spent more money than the rest. This group of people spent more than the double of money than the people between 15 and 19, ($114.06 from the first group VS $412.89 from the second), which are also the second group of people who purchased an item (or more). In third place, the group between 25 and 29 years old, spent a little more than the half than the second group. ($412.89 VS $293.00). The groups of people with the less amount of money spent are the under 10 and above 40 years old, with people under 10 spending a little more.

* Regarding the items purchased, we see that the item that was bought the most it is not the most expensive. Some items which have been bought less times are more expensive than the first item. The difference between the first and the second items is 3. So the most popular item has an average price.

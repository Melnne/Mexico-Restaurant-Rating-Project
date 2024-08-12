# Mexico Restaurant Rating Analysis

### Table of Content
- [Introduction](#introductio)
- [Problem statement](#problem-statement)
- [Skills Demonstrated](#skills-emonstrated)
- [Data Source](#data-source)
- [Tool](#tool)
- [Data Transformation](#data-transformation)
- [Results and Findings](#Results-and-Findings)
- [Recommendation](#recommendation)

### Introduction

This data set is called the restaurant rating dataset which contains information about restaurants in mexico. A customer survey was carried out in this city in 2012 to collate information about each restaurant, their cuisines, information about their consumers and the preferences of the consumers. I analyzed the data to provide insight into the restaurant rating and make-data driven recommendation. 



### Problem Statement
1. What can you learn from the highest rated restaurants? Do consumer preferences have an effect on ratings?
2. What are the consumer demographics? Does this indicate a bias in the data sample?
3. Are there any demand & supply gaps that you can exploit in the market?
4. If you were to invest in a restaurant, which characteristics would you be looking for
   
### Skills Demonstrated
- Data transformation
- Data cleaning
- Visualization
- Filters
- Data modelling

### Data Source

The dataset used for this analysis was provided by the training institution i am training with, **Digitaley Drive**. 
The data contained 5 tables which are;
- Consumer Preference
- Consumers
- Rating
- Restaurant Cuisines
- Restaurant

### Tool

PowerBI 

This tool was used for the data cleaning, analysis and the creation of the dashboard.

### Data Transformation
- I downloaded the CSV files and imported them separately into Power Query Editor.
- The Customer Preferences table was the first I imported into Power Query Editor it was clean however, i renamed the columns to go in line with the rest of the tables. 
- the second dataset to be imported was Consumers, There was a lot of empty cells in this, i went ahead and replaced them with (Null) using the find and replace function in Power Query Editor these included the Budget, Occupation, Children, Marital Status, Transportation Method and Smoker Columns, I also noticed some colunms had wrong data types and i went ahed to rectify that.
- Next was the Ratings dataset, this data set was fine all i did was to change the data type of the Restaurant_ID column.
- Followed was the Restaurant Cuisines dataset which had only two columns, no errors, no null values and all datatypes were accurate. 
- The last dataset was the Restaurants dataset, this had 56 null values in the zip code column which I replaced with 0. I also noticed the data type for zip code column was wrong and i went ahead and changed it from Decimal Number to ‘whole number 123’.

### Modelling
While exploring the data i took notice of the consumer preference table being detached from the the rest of the tables in my semantic model, I proceeded to manage the relationship between it and the consumer table using the consumer_id in both as the connecting factor and ensured it was active so  as for all the tables to interact accurately and conviniently with eachother.


### Results and Findings
1. There are 130 restaurants, 138 consumers, 3 states and 23 cuisines
2. The restaurant with the highest  ratings is  Tortas lucas Hipocampo  and they are mostly patronized by those with medium budget because these people prefer restaurants with medium price that matches their budget,
3. On the basis of occupation most of the consumers are student, on the basis of marital status most of the consumers are single people and on the basis of  age they are young adults within the age of 20-30.
4. San Luis Potosi have the highest number of restaurant which makes them have the highest number of consumers.
5. Most of the consumers(97) prefer Mexican cuisine yet there is only 28 restaurants that offer this cuisine out of 130 restaurants showing a huge demand and supply gap


 ### Recommendation
I would recoomend that an investor interested in restaurant should consider some of the following characteristics
- the population size of the consumers
- preferred cuisine of the the consumers
- consumers demographics and the level of pricing of the restaurant. 

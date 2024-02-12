# DataCollection-Challenge
## Module 11 Challenge


### Overview
The challenge consists of two Jupyter Notebook files. 

The first file, "part_1_mars_news," scrapes article information from the [Mars news site](https://static.bc-edx.com/data/web/mars_news/index.html), utilizing splinter and BeautifulSoup. It then uses a for loop to extract the article title and summary from the articles on the first page of the news site. The information is stored in a list of dictionaries.

The second file, "part_2_mars_weather," scrapes temperature information from the [Mars Temperature Data Site](https://static.bc-edx.com/data/web/mars_facts/temperature.html), also utilizing splinter and BeautifulSoup, and stores the data into a Pandas DataFrame. The data is cleaned by assigning appropriate data types. Then, a short analysis explores the data and creates visualizations of temperature and atmospheric pressure utilizing Pandas and Matplotlib. Finally, the DataFrame is exported to a .csv file. 



### Resources
To complete this assignment, I referred to the solutions for class activity files to accurately implement the for loops and extract text. I also referred to my work in the previous Pymaceuticals challenge and my group's work on Project 1 to recall how to sort values and indices.
# Data-Cleaning-and-EDA
Cleaning and preparing data for Analysis and Machine Learning techniques


## Data
The data used is from the World Health Organization, it can be downloaded in this link:

https://apps.who.int/gho/data/node.main.A900A?lang=en

It contains Obesity index  by country, year and gender from 1975 to 2016

## Notebook

**Data Wrangling**
When downloaded as a .csv file, the format of the data is wide, thus uncomfortable to deal with. The main transformations:

- Transform its format from wide to long, so its easier to treat
- Deal with the values and convert them into a more usable format. For example: The Obesity Index
  - From 5.5[3.4-8.1] to 5.5. I don't drop the confidence intervals since I don't want to lose information, but I will be working with the average, stored in another column.
  
  **Visualizations**
The main objective is just to perform a basic EDA. Since this is a dataset that contains a lot of different categories (one per country, really), the visualizations had to be really efficient.

Main visualizations:
- Average Obesity evolution since 1975 to 2016. (line plot)
- Distribution of obesity among Genders in 3 different time periods. (violin plot)
- Representation of the countries that have had the greatest and lowest growth in obesity in these 40 years. (bar plot)

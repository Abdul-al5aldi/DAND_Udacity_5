# Project 5: Wrangle and Analyze Data
### Data Analyst Nanodegree - Udacity


Data wrangling is a core skill that everyone who works with data should be familiar with since so much of the world's data is not clean. It is a process divided into 3 main steps:
- Gathering.
- Assessing.
- Cleaning. 


## Gathering
Data was gathered from 3 different sources:
1. From WeRateDogs Twitter archive given by Udacity in csv format.
2. Image prediction file downloaded programmatically using Requests library and the URL provided by Udacity in tsv format.
3. Data retrieved by querying Twitter's APIs and using Tweepy library. 


## Assessing
After gathering the data and storing them in DataFrames, the following step was assessing the data for quality and tidiness. Data were assessed programmatically and visually.


## Cleaning
It is the process of fixing and resolving issues identified in the Cleaning process. The (define, code, and test) steps were used in the cleaning process. First, copies of the DataFrames were created before cleaning. Then, the steps of cleaning were applied iteratively on all issues. 


## Storing
The final DataFrame called 'twitter_archive_clean' contains 1990 rows and 15 columns with the correct data types. The dataset is then stored in a csv file called 'twitter_archive_master.csv'. At this point, the data was successfully wrangled and therefore ready for analysis and visualization. 


## Analysis & Visualization
These steps are not part of data wrangling process. However, it cannot reflect correct and accurate insights without performing data wrangling first. Visualizations and insights are provided in ‘act_report.pdf

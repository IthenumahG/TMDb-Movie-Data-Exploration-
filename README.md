# Investigating TMDb movie dataset  
## By Gideon Ithenumah  

## Introduction  
This is an investigation on TMDb movie dataset. This data set contains information about 10,000 movies collected from The Movie Database (TMDb).
In this investigation I used exploratory data analysis to answer some questions and make some inferences about the dataset. The tools used in thiis investigation include but not limited to pandas, matplotlib, numpy and seaborn.  

## Data Preparation 
From a preview of the dataset was observed that there are some issues that will need to be attended to in order to have it ready for analysis. these are;  
* Some columns not useful for my analysis will have to be dropped.
* Columns with multiple values which will have to be expanded into distinct rows for analysis.
* Null and missing values.
* columns with wrong data type.
* Columns with 0 values.  

The highlighted issues above were cleaned and dataset made ready for exploratory analysis.

## Exploratory Data Analysis  
Questions answered by my analysis includes;
* Which are the most successful and unsuccessful novies?
* Is popularity related to movie success?
* Which are the most popular genres?
* Is movie success related to time of release?

## Conclusion  
After ample wrangling and analyzing of the TMDb dataset and answering some questions through visualisation, below is a summary of my findings and limitations;  

* Movies like Avatar, Star Wars, Titanic grossed highest profits while the likes of The Warrior's Way, The Lone Ranger and The Alamo returned the least profits.
* The Genre with highest popularity is Adventure, however Animation appears to be the the most profitable genre.  
* Popularity and net profits skewed in same direction could mean a positive correlation between the two attributes.
* My findings are tentative as it will require more in-depth analysis to give concrete insights of the data. 

##### **Limitations**  
* The dataset was greatly limiting as it contained many irregularities, missing data, zero values in entries that ought to have significant values.
* As a result of the nature of the dataset I had to drop some unwanted columns and also rows that had zeroes values, NA and duplicate this led to a huge reduction in the size of the dataset that had adverse effects on my analysis.


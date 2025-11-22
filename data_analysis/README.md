## Data analysis notebooks for COMM3130 Group Data Project

## 00_data_cleaning.ipnyb
* This is a notebook where we clean the data.
* For instance, the published_date field is a timestamp but is loaded as a string object
* Furthermore, articles before 2020 are filtered out as there aren't many of them and they are not relevant to our analysis. 

## 01_data_analysis.ipnyb
* This is a notebook where we perform our data analysis.
* We identified themes of mental health using n-gram analysis
* Identified which years had the most articles related to mental health
* Examined fluctuations in mental health article count by month with frequency analysis
* Uncovered what facets of mental health were explored by the articles with KWIC
* Pinpointed the sentiment of the articles and how different facets of mental health affected sentiment using VADER sentiment analysis
* Performed topic modeling to see evolving changes

## 02_data_scraping.ipnyb
* This is a notebook that scrapes the articles from the link provided in the csv file from the initial data
* Unfortunately, sections were not included in the original csv file, but it was a dimension that we wanted to analyze. 
* Using the digital publication website, we retrieved the html for each section's unique url and matched each article from the original CSV to their respective section.



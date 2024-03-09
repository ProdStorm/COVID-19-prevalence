# Exploratory Analysis of COVID-19 prevalence across the world

## Table of Contents
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Recommendations](#recommendations)
  
### Project Overview
This analysis is solely descriptive as it explores the COVID-19 dataset. Analyzing the historical data, we provide insights into the total confirmed cases, death cases, death rate, and countries with the highest/lowest prevalence of the disease.

### Data Sources
Two datasets were merged and used for this analysis. The datasets are [Confirmed_cases.csv](https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_confirmed_global.csv) and [Death_cases.csv]( https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_deaths_global.csv), containing detailed information about each confirmed and death case respectively.

### Tools
Excel – Data Cleaning and Transformation, Data Analysis and Visualization

### Data Cleaning and Transformation
In the initial data cleaning phase, we performed the following tasks:
1.	Unpivoting Columns
2.	Formatting data types
3.	Merging datasets
4.	Data Loading and Inspection

### Exploratory Data Analysis
These key questions were answered using EDA
-	What are the Top 5 countries with highest COVID-19 prevalence?
-	What are the Bottom 5 countries with the lowest COVID-19 prevalence?
-	What is the death rate across the world?
-	What time of the year had the highest prevalence of the disease?
-	Did some countries/regions record no deaths? If yes, how many?

### Data Analysis
All analyses were done using pivot tables – summarizing the dataset into simpler tables.
![Snip 2](https://github.com/ProdStorm/Prevalence-of-COVID-19/assets/82668824/505638cb-1b3f-443a-845f-0959a7970773)
![Snip](https://github.com/ProdStorm/Prevalence-of-COVID-19/assets/82668824/f2cabb02-76c2-400f-81db-cd23ca575692)

### Results/Findings
The analysis results are summarized as follows:
1.	The spread of COVID-19 disease has been rapidly increasing over the years analyzed, with a noticeable peak in 2022. Each month recorded over 10 million COVID-19 cases.
2.	US, Brazil, India, Mexico and Russia are the top 5 countries with the highest prevalence of COVID-19.
3.	Winter Olympics 2022, Holy See, MS Zaandam, Antarctica, and North Korea are the bottom 5 countries with the lowest prevalence of COVID-19.
4.	The average death rate across the world is 1.39%.
5.	The Christmas/New Year season had the highest prevalence of the year.
6.	Five countries/regions (Summer Olympics 2020, Antarctica, Tuvalu, Holy See, and Winter Olympics 2022) recorded no COVID-19 deaths despite the number of confirmed cases.

### Recommendations
-	Other countries should seek, study and if possible, adopt the management or quarantine strategies implemented by the five countries/regions with no death record.
-	Relevant disease control bodies should brainstorm ideas on how to stop the widespread of the disease during the festive seasons (Christmas and New Year). 

### Limitations
The COVID-19 record for the year 2023 is incomplete. Hence, all visualizations or numbers for 2023 aren’t fully representative.

### Resources
[COVID-19 Dashboard MS Excel](https://techcommunity.microsoft.com/t5/educator-developer-blog/build-covid-19-dashboard-with-microsoft-excel/ba-p/3509050)

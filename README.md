# Covid-19 Worldwide Analysis 2020-to-2022
The report analyzes Covid -19 confirmed, recovered and death cases worldwide from January 22, 2020, to August 2, 2022.

# Introduction
Corona Virus, commonly known as Covid-19, has impacted the world badly since 2019. The virus causes illnesses that range from the common cold to even more severe respiratory-related diseases. The virus has greatly affected day-to-day life since 2020, with millions of people contracting the disease, a portion of them dying while others are recovering. There is a need for health organizations to understand the trend of the virus to take active and effective measures to protect the public. In this project, I analyzed the covid- 19 trend from January 2020 to August 2022.

# Problem Statement
This Analysis aims to look at the Covid-19 confirmed cases trend from January 2020 to August 2022 from the Covid-19 dataset. The trend of confirmed cases will then be compared to the Death and recovered cases within this period to help understand the state of covid-19 worldwide. The Analysis would be helpful to both international and local health organizations and practitioners to assess and come up with effective measures to control the spread of the virus.

# Data Sourcing
The data set used for this Analysis was sourced from [GitHub](https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_time_series)
The dataset had three spreadsheets containing the confirmed number of cases, recovered number of cases, and Death cases from all countries worldwide from January 22 2020, to August 2 2022.

# Data Cleaning
Tools used for data cleaning and preparation:
1.	Microsoft Excel
2.	Power Query

## Power Query
I loaded the data into Power Query for transformation through the dataset links for each of the three tables.
I renamed the first table to Confirmed, then selected (Province/State, Country/Region, Lat, and Long) columns unpivoted. The new columns were renamed Date and Confirmed.
The Confirmed table was then duplicated and renamed as Death, and from the data source, I pasted the source link to load the death cases data.
I duplicated and renamed the death table to Recoveries. Then I pasted the link to the dataset from the source data to load the recoveries data.
I then merged the table Confirmed and Death as new and renamed Consolidated data.
I merged the Consolidated table to recoveries, and the last column was renamed as recovered.
I removed all the steps for the change type from the confirmed and Death table.
The merged data (Consolidated data) was then loaded into Microsoft Excel

## Microsoft Excel
In MS Excel, I checked the data for misspellings, duplicates and Null values.
I created new columns for Year, Month, and Day to get more insights during visualization.
After cleaning, there were 263,341 rows and 11 columns. A new worksheet was created for the visualization and renamed Analysis.

# Attributes of the Data
1. Province/State: The Province/State reporting the confirmed Death or recovery case.
2. Country/Region: The Country/Region reporting the confirmed Death or recovery case.
3. Lat: Distance of each location from the equator.
4. Long: Measurement of the east or west of the prime meridian.
5. Date: The date the cases were reported.
6. Confirmed: Number Confirmed of cases reported.
7. Death: Number of death cases reported.
8. Recovered: Number of recovered cases reported.
9. Year: The year the cases were reported.
10. Month: The month the cases were reported.
11. Day: The Day the cases were reported.

# Analysis
On the newly created worksheet, I did Analysis by summarizing the table using pivot tables to create the following insights:
1.	Confirmed cases by country (I filtered the top 5.)
2.	Confirmed cases by country (I filtered the bottom 5.)
3.	Confirmed cases and Death cases.
4.	Confirmed cases by year.
5.	Confirmed cases by month.
6.	The proportion of confirmed cases by year
7.	Comparison of all cases by year.

# Visualization
All visualizations were created using MS Excel to form a dashboard.
The following charts were used to draw the insights and merged to make a dashboard.
1.	A Bar chart for the top five cases.
2.	A Clustered column for the bottom 5 cases.
3.	Line chart to show cumulative cases yearly.
4.	Bar chart to show confirmed cases by month.
5.	A Month, Year table to show confirmed cases.

[View and interact with the data and dashboard here](https://docs.google.com/spreadsheets/d/1eeQA0d4Hcf26PXXS4HdAVDwIq4ul11vi/edit?usp=sharing&ouid=117627235192123615887&rtpof=true&sd=true)

# Recommendations
•	The Ministry of Health should ensure people adhere strictly to the measures the World Health Organization put in place to prevent an upsurge in the number of confirmed cases.
•	More people should be sensitized to be vaccinated to ensure they are prevented from Covid-19.
•	There should be global sensitization on the measures to be taken by citizens to ensure covid-19 prevention; regularly wash hands, use disinfectants, wash hands, and uphold coughing etiquette.

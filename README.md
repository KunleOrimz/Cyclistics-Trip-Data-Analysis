# Cyclist Bike Share Analysis
## Table of contents
- [Project Overview](#project-overview)
 - [Data sources](#data-sources)
 - [Tools](#tools)
 - [Data Cleaning/Preparation](#data-cleaning/preparation)
 - [Exploratory Data Analysis](#exploratory-data-analysis)
 - [Data Analysis](#data-analysis)
 - [Results/Findings](#results/findings)
 - [Recommendations](#recommendations)
 - [Limitations](#limitations)
 - [References](#references)
### Project Overview
This project aims to provide insights into the cycling patterns of the both annual rgistered  and casual memebers over the past couple of years of Cyclistic, a bike share company in Chicago. By analyzing these riders cycling patterns, i seek to identify trends, make data-driven recommendations to increase the revenue,gain a deeper understanding of the different type of riders and their choices and maximize the number of annual memberships.

### Data Sources
This analysis use Cyclistic’s historical trip data to analyze and identify trends. The previous 12 months of Cyclistic trip data was made available and downloaded (Note: The datasets have a different name because Cyclistic is a fictional company. For the purposes of this case study, the datasets are appropriate and it enabled me to answer the business questions. The data has been made available by Motivate International Inc.license.) This is public data was used to explore how different customer uses Cyclistic bikes. Kindly note that Data-privacy issues prohibit me from using riders’ personally identifiable information

### Tools
  - Microsoft Excel- Data Cleaning [Download here](https://microsoft.com)
  - PowerBI -Creating reports and Visuals [Download here](https://microsoft.com)

### Data Cleaning/Preparation
In the initial data preparation phase, we performed the following tasks:
1. Data loading and inspection
2. Handling missing and negative values
3. Data cleaning and formatting

### Exploratory Data Analysis
EDA involved exploring the sales data to answer key questions, such as:
  - How annual members and casual riders use Cyclistic bikes differently? 
  - What story does your data tell? 
  - How do your findings relate to your original question? 
  - Can data visualization help you share your findings?  
  - What surprises did you discover in the data?
  - What trends or relationships did you find in the data? 
  - How will these insights help answer your business questions?

### Data Analysis
Excel power query was used in formating and analyzing the datasets, extra columns were added, surplus column not needed for the analysis was deleted and it was loaded onto powerBI for further analysis and data visualization preparation

### Results/Findings
The analysis results are summarized as follows:
1. Cyclistics as a company has more annual registered members than the casual members
2. Registered members and the casual members both ride during weekdays but registered members ride mostly during the week 
3. Casual members ride more during weekends that the weekdays
4. Casual members ride more during summer compare to other seasons specifically in June, July and August 
5. Registered members ride all season but are lesser in number during summer
6. Casual members ride more for fun unlike registered members that mostly ride for daily commuting 

### Recommendations
From the exploratory data analysis results, the following are my recommendations to convert more of the casual members to annual registered members
1. Discounted rental rate to be introduced only over the weekends for registered annual members only 
2. Cyclist to come up with promotions encouraging casual members to get registered as annual members such as discounted registration fee over the weekends
3. Face to Face sensitization of the casual members to be carried out during weekends emphasizing the benefits of getting registered as annual member
4. Social activities to be introduced for registered annual members only over the weekends to encourage bonding and networking

More marketing activities should be targeted at the casual riders during weekend to convert them to annual registered members. Other attractive incentives also can be introduced over weekends only as more casual riders come out over the weekends compared to weekdays, this is to attract more casual members to become registered 

### Limitations
I had to convert all negative values on the 'ride_duration' column during  data cleaning to positive values as these would have affected the accuracy of my conclusion and may also give wrong outcomes for data visaulisation but formimg wrong outliers. The company name 'Cyclistics' is fictitious, it was named such solely for this study.

### References
1. Google Professional Certificate of Data Analytics(Capstone Project)
2. [Cyclistic trip dataset](https://divvy-tripdata.s3.amazonaws.com/index.html)





# Analysis_of_US_Accidents

This project presents a comprehensive analysis of car accidents in the United States using a real-world dataset. Our analysis will uncover valuable insights into the frequency and distribution of accidents across the country, and provide potential explanations for the underlying causes. The goal of this project is to contribute to efforts to reduce accidents and improve road safety by shedding light on the importance of safe driving.

## About the Dataset
I would like to draw your attention to a comprehensive dataset on car accidents in the United States, encompassing 49 states. The data, spanning from February 2016 to December 2021, was sourced through multiple APIs, providing real-time information on traffic incidents. These APIs transmit traffic data gathered from a range of sources, including departments of transportation at the state and federal levels, law enforcement agencies, traffic cameras, and sensors embedded within the road networks. With approximately 2.8 million records, this dataset represents a valuable resource for those seeking to gain insights into the patterns and trends of car accidents in the US.

## Number of Records &nbsp;  &nbsp;  &nbsp;  &nbsp;  &nbsp;  &nbsp;  Number of Features
# ~ 2.8 Million &nbsp;  &nbsp;  &nbsp;  &nbsp;  &nbsp;  &nbsp;  &nbsp;  &nbsp;  47

# Data Preparation and Cleaning
The data preparation and cleaning phase involved loading and downloading the files using Pandas, analyzing the information contained within, and correcting or accounting for any missing or incorrect values. This step is crucial in ensuring the accuracy and reliability of our analysis.

<img width="1274" alt="Screen Shot 2023-03-10 at 11 35 05 AM" src="https://user-images.githubusercontent.com/105601398/224371534-fd0803e6-6649-4cbe-a4d0-e0539f18744c.png">
Based on the bar chart of missing values, it appears that a few columns have a missing value percentage exceeding 30%. In the interest of maintaining the accuracy and representativeness of our data, it would be appropriate to exclude these columns from our analysis.

# Exploratory Analysis and Visualization
The exploratory analysis and visualization phase involved analyzing key columns such as City, Start Time, Start Latitude, and Start Longitude. These columns were chosen as they are likely to provide useful insights into the frequency and distribution of accidents across different regions and time periods. The results of this phase will be used to guide further analysis and hypothesis testing.

## Cities with the most Accidents
The number of cities in this dataset is: 9681 out of over 108,000 in the United States.

Top 10 cities in the US with the most accidents

<img width="215" alt="Screen Shot 2023-03-10 at 11 36 37 AM" src="https://user-images.githubusercontent.com/105601398/224371860-fe7b70e6-6421-422d-9c33-14185549868e.png">
It is noted that New York City, which is the most populated city in the United States, is not represented in this data set.

## Number of Accidents per City

<img width="1270" alt="Screen Shot 2023-03-10 at 11 38 13 AM" src="https://user-images.githubusercontent.com/105601398/224372274-0c82029b-6bb7-4d00-adc1-a3bbe09944f5.png">

## Heatmap of US Accident Incidents
Higher Layers Represent Increased Accident Density and Severity

<img width="761" alt="Screen Shot 2023-03-10 at 11 40 03 AM" src="https://user-images.githubusercontent.com/105601398/224372573-7178bb05-40c5-4046-bb18-d3243d842f07.png">

The map was generated from sampling 50,000 coordinates from the US accidents dataset and provides a visual representation of the distribution of accidents across the US. The map uses red hexagon layers to represent the density of accidents, with higher positioned layers indicating a higher number of accidents, as well as more severe ones. This map allows us to quickly identify areas with a high concentration of accidents, and can be used as a tool to help focus on reducing accidents in these areas.

## Weekday Accidents by Hour
<img width="725" alt="Screen Shot 2023-03-10 at 11 43 00 AM" src="https://user-images.githubusercontent.com/105601398/224373230-78ea5bcd-301c-459e-b115-87ecb560966b.png">

Our analysis suggests that a significant proportion of accidents occur during the morning rush hour between 6am and 9am on weekdays. This is likely due to a higher volume of individuals in a hurry to arrive at their workplace. A higher peak in accidents is observed between 2pm and 5pm, which corresponds to the evening commute as individuals leave work and return home.

## Weekend Accidents by Hour

<img width="728" alt="Screen Shot 2023-03-10 at 11 44 11 AM" src="https://user-images.githubusercontent.com/105601398/224373468-16536520-c634-4660-9d99-78b738a2267e.png">

Our analysis shows that there is a relatively consistent frequency of accidents occurring throughout the day on weekends, with a noticeable increase in accident occurrences observed between 11am and 6pm.

## Key Takeaways and Observations
Several key observations were made during the analysis of the US Accidents dataset. Excluding columns with over 30% missing values is recommended to ensure the data's accuracy and representativeness. Additionally, the absence of New York City, the most populous city in the United States, in the dataset may impact the overall representation of accidents in the country.

The analysis revealed a higher frequency of accidents during rush hour periods, with a significant proportion of accidents occurring during the morning and evening commutes. On weekends, a relatively consistent frequency of accidents was observed throughout the day, with a noticeable increase in occurrences between 11am and 6pm. However, the dataset did not include important factors that may contribute to car accidents, such as demographic factors, accident history, criminal record, sobriety, car body style, and car condition. Analyzing these factors may help identify potential solutions to reduce accident rates.

To decrease accident rates in the United States, it is essential to consider various factors that may contribute to car accidents. Unfortunately, the analysis was limited by the dataset, which did not include some essential factors. Therefore, it may be useful to investigate demographic factors such as age, nationality, and gender in car accidents. Other relevant information, including the driver's accident history, whether they are a first-time or repeat offender, and their existing criminal record, should be considered. It may also be helpful to investigate the role of sobriety and car body style, including micro, sedan, CUV, SUV, and others. Additionally, it may be useful to consider car condition, specifically whether the car is registered and insured. Analyzing these factors may help us better understand the causes of car accidents and identify potential solutions to reduce accident rates.

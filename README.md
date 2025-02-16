# Canada-Collision-2019
## Objective

Canada Collision 2019 is a project focused on analyzing and visualizing data related to vehicular collisions in Canada from the year 2019. This project utilizes data science and machine learning techniques to identify patterns, predict accident hotspots, and gain insights into factors influencing traffic safety. Key features include data cleaning, exploratory analysis, predictive modeling, and interactive visualizations.

## Data Source

This project uses the vehicle collision dataset for 2019, which was made publicly available by the Government of Canada. The data can be accessed [Here](https://open.canada.ca/data/en/dataset/1eb9eba7-71d1-4b30-9fb1-30cbdab7e63a)
 . It includes information on various accident details, such as hotspot, time, and weather conditions used for analysis and prediction."

 ### Data Transformation & Cleaning process
 The dataset initially contained numeric values, requiring extensive data standardization and multiple joins. I utilized Excel’s VLOOKUP function to match each numeric value with its corresponding text string from the data dictionary. Additionally, I handled several missing values to ensure data completeness. 

 ## Insight 1
|  Month    |   Total Collision   |   Total Fatality   |    Total Injury   |             
|-----------|---------------------|--------------------|-------------------|
| January   |25,000               | 115                |135,000
| February  |22,000               | 93                 |11,000
| March     |20,000               | 95                 |10,000
| April     |17,000               | 98                 |9,000 
| May       |20,000               | 135                |11,000
| June      |24,000               | 173                |12,000 
| July      |25,000               | 191                |13,000
| August    |25,000               | 202                |13,000
| September |23,000               | 161                |12,000
| October   |25,000               | 176                |13,000
| November  |23,000               | 176                |12,000
| December  |23,000               | 147                |12,000

## Insight 2
| Weather Conditions | Total Collision |
|--------------------|-----------------|
|Clear Sunny         | 193,680         |
|Overcast & Cloudy   | 24,822          |
| Raining            | 22,824          |
| Snowing            | 18,369          |
| Visibility Limitations | 5617        |

## Dashboard
View the dashboard 

[Here]![image](https://github.com/user-attachments/assets/c298c238-0592-4b30-89ad-3e0e60e95ec0)


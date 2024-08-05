# Project03
This is project-03 for the lede program.
<br>
Link to the project-03 (https://riyonakasaka.github.io/Project_3/)

## Title
Dining Habits of Japanese Prime Minister Fumio Kishida
<br>
An Analysis of Activities Since October 5, 2021 to July 9, 2024

## Aim
To deepen the understanding of the Japanese Prime Minister by analyzing dining trends with politicians and private individuals over approximately two years.

## Findings
1. The Prime Minister frequently dines on Japanese cuisine, followed by Chinese and French dishes. Notably, he often chooses sukiyaki and restaurants specializing in beef, such as steakhouses and Korean BBQ.
2. Most dining locations are within a 5 km radius of the Official Residence/Prime Minister's Residence.

## Data Collection Process
1.Data was scraped from Nikkei's "Prime Minister's Official Activities" articles. The scraping process can be reviewed on the GitHub page for Project 2, in the "scraping" section: GitHub Scraping Notebook(https://github.com/riyonakasaka/Project_2/blob/main/notebook/scrapping.ipynb).
2.Restaurants listed from the scraping process were manually categorized by type and geographic information (refer to dataset PM_dinner.xlsx).

## Data Analysis Process
The frequency of dining by category was counted using foodcategory.ipynb, and results were exported to foodcategory.csv. Geographic data was processed with latitude and longitude in data.csv. Visualization was performed using Flourish and Datawrapper, with preliminary geojson files created.

## New Skills and Growth
1. Visualized dining preferences using a pickle circle chart.
2. Unified chart and map colors across the project using color codes.
3. Gained experience with geojson and Datawrapper for map creation, a new skill set compared to previous projects.

## Future Work
In data collection, although categorized restaurant information was obtained using undocumented APIs from Japanese gourmet search websites, matching with actual Prime Minister's dining venues proved challenging. Manual classification was therefore necessary.

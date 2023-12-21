# Olympic Games Visualisation and Data Analysis

![Olympic Games Visualisation Dashboard](https://github.com/KahHongg/Olympic_Games_PowerBI/assets/54535637/00919e31-8f71-43e8-a53c-dd7997a1fe08)


# Introduction:

* This repository contains code and data for visualizing Olympic Games data obtained from Kaggle. 
* The data has been processed, transformed, and visualized to gain insights into medal distribution, athlete performance, and other relevant metrics.

# Purpose:

* This project analyzes and visualizes Olympic Games data, aiming to uncover insights into medal distribution, athlete performance, and key metrics. 
* Utilizing Kaggle data and advanced processing techniques, it offers a comprehensive exploration of historical Olympic Games. 
* The visualizations provide accessible insights for enthusiasts, analysts, and researchers, facilitating a deeper understanding of performance trends among countries and athletes in the Olympic Games.

# Data Processing

## Data Import and Transformation
* Imported CSV file from Kaggle containing Olympic Games data.
* Transformed data by removing ID, renaming NOC to Country, and deleting rows with missing values for height, weight, and age.
* Replaced NA values with "participated" and renamed the city column to "Host City" for clarity.
* Renamed gender values (M to Male, F to Female) and removed the "Team" column as its not relevant for this analysis.

## Data Joining
* Imported another csv file to join the dataset, displaying the full name of the country.
* Used merge queries with a left join to show only the names of the country in the athlete table.
* Renamed columns for clarity and removed irrelevant columns.

# Key Features (Visualisations)

## Medal Distribution by Country

![Medal Distribution by Country](https://github.com/KahHongg/Olympic_Games_PowerBI/assets/54535637/7a67800c-353a-4323-8634-aecf95c75987)

* Utilized the metrics table for a detailed view of medal distribution by country.
* Filtered for the top 10 countries with the most medals and specified medal types (Bronze, Silver, Gold).

## Medal Distribution by Gender
![Medal Distribution by Gender](https://github.com/KahHongg/Olympic_Games_PowerBI/assets/54535637/44c1953c-8151-41b1-a304-8909602d55f5)

* Created a piechart visualization showing the distribution of medals by gender.
* Included Gender and Count of medals columns, placing values inside using data labels for aesthetic purposes.

## Medal Distribution by Sport

![Medal Distribution by Sports](https://github.com/KahHongg/Olympic_Games_PowerBI/assets/54535637/d5691a04-d2b1-4b60-8c97-5431ad624455)

* Utilized the treemap visualisation to show the top 15 sports with the most amount of medals.
* Used conditional formating with colour gradient to show the highest and lowest number of colours. Dark red representing the highest number of medals.
* Enabled data labels to display the number of medals in each treemap box for clarity.

## Top 10 performing athletes in the Olympics

![Top 10 athletes with the most amount of medals](https://github.com/KahHongg/Olympic_Games_PowerBI/assets/54535637/2065db27-fa44-41f9-b5aa-9829a19869a2)


* Plotted a bar chart with Athlete Name on the X-axis and Count of Medals on the Y-axis.
* Enabled data labels to display the number of medals won by each athlete.
* Applied color coding for bronze, silver, and gold medals.
* Filtered for the top 10 performing athletes of all time.

## Filter Panel and Cards

![Filter Panel and Cards](https://github.com/KahHongg/Olympic_Games_PowerBI/assets/54535637/73c15e4e-4837-4606-8f4a-0f01dadc3a3f)

* Utilized multiple slicers and grouped into a small panel for interactivity purposes
* Users can select a specific Olympic game year and sport to see the statistical distribution of the features listed above
* Created a clear filter bookmark and linked it to an image png using an action button to allow users to clear their selection
* Cards are placed at the side of the panel to give a quick overview of the number of countries participated, athletes who competed and number of distinct sports held at the event.

Google Play Store Apps Analysis
An exploratory data analysis of Google Play Store apps, looking at how categories, ratings, installs, pricing and other app attributes relate to each other.
Overview
This project cleans and analyzes Google Play Store app data to uncover trends in the app market. The goal is to answer questions such as:
Which categories have the most apps and the most installs?
How do ratings vary across categories?
Do paid apps get better ratings than free apps?
How do app size, price and update frequency relate to popularity?
Repository Contents
File
Description
Playstorejb (11).xlsx
Excel workbook with the dataset and analysis
Dataset
The workbook contains Google Play Store app records. Typical fields include:
App: name of the app
Category: app category
Rating: average user rating
Reviews: number of user reviews
Size: app size
Installs: number of installs
Type: free or paid
Price: price of paid apps
Content Rating: target age group
Genres: app genres
Last Updated: date of the latest update
Android Version: minimum supported Android version
Update this list to match the exact columns in your workbook.
Methodology
Data cleaning: removed duplicates, handled missing values, and standardized formats (installs, size, price).
Analysis: summarized data with pivot tables and formulas.
Visualization: built charts to show category, rating and install trends.
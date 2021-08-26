# BRK Consulting King County
Authors: Lorela Blaka, Meaghan Ross, Rashid Karriti
# Overview
This project analyzes a series of linear regressions to provide recommendations for King County Real Estate to have a better understanding on how to price homes in Washingtons King County. Interpretive analysis shows that income per capita and square footage of the home are strong indicators on how to price a home.
# Business Understanding 
King County Real Estate has contracted us to investigate what home features have the greatest impact on pricing and speeding up the sale of the home. Based on our models, King County Real Estate should: A) Review the relationship between the square footage of the home and price of a home and B) Review the relationship between income per capita of a neighborhood and price of a home.
# Data Analysis & Methodology
The project utilizes a descriptive analysis, linear modeling, and running several iterations of an OLS regression on home features to reveal which factors contribute most to housing prices.  Our main data sets are King County House Sales Data from 2014 to 2015, and USA.com data on income per capita across cities in King County. The prediction accuracy of the features of a home included in our model accounted for about 67% of the variation in price, with a price prediction of +/- $192,033 from the actual price.
# Results
The square feet of the home shows a strong correlation between the size of the home and an increase in the price. Our recommendation is to price homes based on how the square footage is.

![download](https://user-images.githubusercontent.com/82670256/131034563-d504254d-11a4-40d0-aa84-34b2427d9b6e.png)

The income per capita shows a strong correlation between the income per capita of a neighborhood and an increase in price. Our recommendation is to price homes that have a higher income per capita. 

# Conclusion 
Real estate companies working on pricing of homes in King County should consider the square footage of the home, and income per capita of the home to give the most accurate pricing evaluation.
# Next Steps
For more comprehensive evaluation of pricing a home, a real estate company should further inquire into:
- Expanding the data to years beyond 2015, to see if pricing has changed overtime with other important features to the home.
- Include property tax information to better predict prices in the future.
- Include more features of a neighborhood, such as a school district.
# Additional Information 

- Jupyter Notebook
- Instructions on navigating repo 

Lorela Blaka: lblaka@gmail.com

Meaghan Ross: mer423@nyu.edu 

Rashid Karriti: rhk48@georgetown.edu
# Project Structure 
```
├── README.md
├── data      <-- CSV 
├── images    <-- visualizations from working notebooks and external images
├── Individuals Notebooks       <--- Directory for individual workspaces
│   ├── meaghan
│   ├── lorela
│   ├── rashid
│   
├── Project 2 Notebook.ipynb    <-- Jupyter Notebook containing codes detailing project's analysis 
├── RealEstateProject.pdf   <-- non-technical presentation slides
└── .gitignore
```

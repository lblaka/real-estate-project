# BRK Consulting King County
Authors: Lorela Blaka, Meaghan Ross, Rashid Karriti
# Overview
This project analyzes a series of linear regressions to provide recommendations for King County Real Estate to have a better understanding of how to price homes in Washington's King County. Interpretive analysis shows that income per capita and the square footage of the home are strong indicators of how to price a home.
# Business Understanding 
King County Real Estate has contracted us to investigate what home features have the greatest impact on pricing and speeding up the sale of the home. Based on our models, King County Real Estate should: A) Review the relationship between the square footage of the home and price of a home and B) Review the relationship between income per capita of a neighborhood and price of a home.
# Data Analysis & Methodology
The project utilizes a descriptive analysis, linear modeling, and running several iterations of an OLS regression on home features to reveal which factors contribute most to housing prices.  Our main data sets are King County House Sales Data from 2014 to 2015, and USA.com data on income per capita across cities in King County. The prediction accuracy of our varaibles included in our model accounted for about 67% of the variation in price, with a price prediction of +/- $201,491 from the actual price.
# Results
Here the Price vs Square Feet of the home presents a strong correlation between the size of the home and an increase in the price. Our recommendation is to price homes based on the number of the square footage of the home.

![download-3](https://user-images.githubusercontent.com/82670256/131037456-12821660-d6db-47ff-b42f-60f2d6254107.png)

Here based on Mean Price by income shows a strong correlation between the income per capita of a neighborhood and an increase in price. Our recommendation is to price homes that have a higher income per capita. 
![download-2](https://user-images.githubusercontent.com/82670256/131037464-4f2eff4c-2c35-400f-ab1b-59b34500ef25.png)

# Conclusion 
Real estate companies working on pricing of homes in King County should consider the square footage of the home, and income per capita of the home to give the most accurate pricing evaluation.
# Next Steps
For a more comprehensive evaluation of pricing a home in the future, a real estate company should further inquire into:
- Expanding the data to years beyond 2015, to see if pricing has changed over time with other important features to the home.
- Include property tax information to better predict prices in the future.
- Include more features of a neighborhood, such as a school district & public transit.
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
├── final_notebook.ipynb    <-- Jupyter Notebook containing codes detailing project's analysis 
├── RealEstateProject.pdf   <-- non-technical presentation slides
└── .gitignore
```

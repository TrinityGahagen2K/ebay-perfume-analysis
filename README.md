# Ebay Perfume Analysis
Phase 1 Project for Flatiron school's Data Science Live Curriculum.

## Objective
---
In this project, I perform an exploratory data analysis on ebay perfume listing data to find valuable insights on (and visualize) consumer preferences and demographics, and different brand and type distributions. The dataset I used can be found on [*this Kaggle page*](https://www.kaggle.com/datasets/kanchana1990/perfume-e-commerce-dataset-2024).

### Dataset Overview
This dataset consisted of 2 CSV files, one with data pertaining to men's perfumes, and another pertaining to women's. The columns included in each file are:

`brand` : The brand of the perfume
`title` : The title of the ebay listing
`type` : The type of perfume being sold (eau de parfum, eau de toilette, etc.)
`price` : The price that the perfume is listed as
`priceWithCurrency` : A text version of the price column, including the currency
`available` : The number of products available in stock
`availableText` : The information that ebay provides about availability
`sold` : The number of products already sold
`lastUpdated` : The date that the listing was last updated
`itemLocation` : A list of locations where the item can ship from

## Project Overview
---
This project showcases my data cleaning and visualization skills by leveraging pandas' different data manipulation techniques (i.e., str attributes of DataFrames) and Matplotlib's extensive plotting module, `pyplot`.

Several descriptive questions were asked and answered using these visualizations, questions such as:
1. What is the count of different perfume types?
2. What is the distribution of perfumes intended for specific genders?
3. Which locations do perfumes ship from most?
4. Which brands have the highest average price?
5. What about the highest average price of brands and perfume types across different genders?

An inferential analysis section is also included towards the end of the notebook, posing and answering a few questions like:
1. Is there a significant difference between sales of perfumes that target each gender?
2. Is there a significant difference between prices of perfumes that target each gender?
3. Are the number of units of Calvin Klein perfumes sold statistically different between men and women?

To answer these questions I utilized Scipy's `stats` module to conduct the appropriate hypothesis tests.

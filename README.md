# Housing Supply Analysis
U.S. Rental Market, 2017 - 2023

**Author**: Samuel De La Paz

**Date**: December 5, 2025


# Executive Summary

## Context and Scope
This notebook walks through the exploratory data analysis and visualization steps I took when trying to understand how estimates are made regarding the impact of increased housing supply on rent prices. I combined Zillow rent data with components of the U.S. Census Bureau's American Community Survey (5-year estimate) data to link rent prices and population characteristics by zip code. The final data set includes 1,806 zip codes from 157 metropolitan areas and 47 states between the years 2017 and 2023.

## Key Findings
From investigating my completed data set, I made some interesting observations.
* **Variable Relationships:** There is a positive relationship between median income, average rent, and the share of the population that work from home. There is a lack of a relationship between the share of population that rents and median income, showing it is not necessarily true that areas with higher incomes have lower rental rates.

* **Affordability Trends:** While the average monthly rent increased by \$575, the average median monthly income increased by \$2,075 for these zip codes. This suggests that renting should be more affordable, however it does not consider the potential inequality of income increase between renters and homeowners. There was no visible shift in the renter share or rent burdened share of the population.

* **Supply and Rent:** A 10% increase in housing supply growth is significantly associated to a 1.1% decrease in rent growth.

## Future Recommendations
There are a few aspects that I would develop further in the future to make this report more robust.

* **Statistical Significance:** Instead of merely observing visual shifts, I can use hypothesis testing to measure if changes in certain variables, such as renter share or rent burdened share, are statistically significant.

* **Decomposition:** Instead of looking at the trends, such as the increase in rent and income, for the whole data set, I could group the data into categories, such as income levels, to see if there is a different effect across groups.

* **Work From Home Effect:** The relationship between the increasing share of people working from home and population change should be investigated to see if there is a shift of people moving to more affordable areas to work from home, changing the demand for rental units in expensive areas.

## Conclusion
This exploration demonstrated an association between increasing housing supply growth with decreasing rent growth controlled for various population characteristics. Local policymakers in metropolitan areas concerned with rent growth should consider policies that will incentivize increased housing supply.

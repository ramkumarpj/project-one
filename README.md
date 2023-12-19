## Abnormal Distribution

Project 1

In this project we are attempting to answer critical questions regarding the best return on investment(ROI) of Oklahoma residential real estate.

## Questions

* Which zip code gives the best home value ROI?

* What is the impact of intrest rate on median sales price?

* Which zipcope is the best to own rental property? 

## Data sets 

* [Zillow](https://data.nasdaq.com/databases/ZILLOW) : Home Value, Median Sales and Rental data.
  
* [FRED API](https://fred.stlouisfed.org/) : 30 Year Mortgage rates and 10 Year Treasury Yield.

## Analysis
* Best Home Value ROI : Monthly Home value for years 2013 thru 2022 was obtained from Zillow. The difference in home value as a percentage for each year was aggregated for each zip. The zip that produced top returns were plotted to a scatter plot.

* Impact of interest rate on Median Sales Price: 30 Year Mortage rates for 2013 thru 2022 was obtained using FRED API. The weekly mortgage rates date was aggregated to monthly buckets so that it can be compared against the monthly median sales price data obtained from Zillow. A line plot of both 30 year mortgage rates and median sales price changes were plotted in a single plot to identify the impact.

* Zipcode that provides best Rental ROI: 10 year Treasury rates was obtained from FRED API. The home value and monthly rental data for 2014 thru 2021 were obtained from Zillow. The rental ROI for each zipcode for the analysis period was calculated based on this data.

## Findings

* 74534 Centrahoma (Southern Oklahoma) had the best home value ROI.

* Generally interest rates and median sales price are inversely correlated.

* 73016 Oklahoma City had the best rental ROI.
  
### Documents

Project Proposal 

### Code

Jupyter Notebooks: 
* code/HomeRental_ROI_Analysis.ipynb 
* code/HomeSales_IntrestRate_Analysis.ipynb 
* code/Homesales_ROI_Analysis.ipynb

### Resources

* Zillow Data - https://data.nasdaq.com/databases/ZILLOW \
  resource\Zillow_Data.csv(<ins>to be downloaded since the dataset is around 5GB</ins>),\
  resources\Zillow_Indicators.csv,\
  resources\Zillow Regions.csv

* FRED API - https://fred.stlouisfed.org/

## Output

* Best Home Value ROI
  * output/average_home_value_change_by_year.png
  * output/most_profitable_yoy_zips.png

* Impact of interest rate on Median Sales Price: 
  * output/interest_rate_change_median_sales_price.png
  * output/change_in_median_sales_price_major_cities.png
  * output/least_profitable_metros_yoy.png
  * output/most_profitable_metros_yoy.png

* Zipcode that provides best Rental ROI
  * output/10-year-treasury-market-yield.png
  * output/homerental_roi_highest_rental_roi.png
  * output/homerental_roi_highest_rental_roi-1.png
  * output/homerental_roi_lowest_rental_roi.png
  * output/homerental_roi_lowest_rental_roi-1.png
  
  




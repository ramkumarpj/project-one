# # Abnormal Distribution

In this project we are attempting to answer critical questions regarding the best return on investment(ROI) of Oklahoma residential real estate.

## Questions to be answered: 

* Which zip code gives the best home value ROI?

* What is the impact of intrest rate on median sales price?

* Which zipcope is the best to own rental property? 

## Data sets 

* [Zillow](https://data.nasdaq.com/databases/ZILLOW) : Home Value, Median Sales and Rental data.
  
* [FRED API](https://fred.stlouisfed.org/) : 30 Year Mortgage rates and 10 Year Treasury Yield.

## Analysis
* Best Home Value ROI : Monthly Home value for years 2013 thru 2022 was obtained from Zillow. The difference in home value as a percentage for each year was aggregated for each zip. The zip that produced top returns were plotted to a scatter plot.

* Impact of interest rate on Median Sales Price: 30 Year Mortage rates for 2013 thru 2022 was obtained using FRED API. The weekly mortgage rates date was aggregated to monthly buckets so that it can be compared against the monthly median sales price data obtained from Zillow. A line plot of both 30 year mortgage rates and median sales price changes were plotted in a single plot to identify the impact.

* Zipcode that provides best Rental ROI: 10 year Treasury rates was obtained from FRED API. The home value and monthly rental data for 2014 thru 2021 was obtained from Zillow. The rental ROI for each zipcode for the analysis period were calculated based on this data.
  
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




# Web scrape tutorial

[Link](https://rpubs.com/haleyepperlyfox/916671) to published tutorial made using quarto.

This is a tutorial for web scraping data in R using the `rvest` package. The data, agricultural subsidies received by USA counties, are scraped from this [website](https://farm.ewg.org/index.php) managed by the Environmental Working Group.

These data are publicly available, but there is no way to export data from the website. This tutorial shows you how to loop through \~500 webpages (combination of different states and years of data availability) and download data from interactive maps. At the end of the tutorial, you will have a dataframe with the amount of agricultural subsidies by category (e.g., commodity, insurance) received by each county in the USA from 2010 through 2019.

## Note: The final code chunk takes \~7 minutes to run.

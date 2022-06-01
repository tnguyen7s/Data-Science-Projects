# Rental Prices of 5 different cities in the United States (May-2022) Analysis Project
## Set up project
### Create a folder for my project:
![alt text](https://github.com/tnguyen7s/Data-Science-Projects/blob/main/House-Prices-In-USA/project_images/create_project_folder.png?raw=true)
### Create a virtual environment:
![alt text](https://github.com/tnguyen7s/Data-Science-Projects/blob/main/House-Prices-In-USA/project_images/virtual_env.png?raw=true)
### Install libraries and packages in my newly created virtual environment:
![alt text](https://github.com/tnguyen7s/Data-Science-Projects/blob/main/House-Prices-In-USA/project_images/install_libs.png?raw=true)
## Main:
### 1. Webscraping
My project rental data is obtained via utilizing Python webscraping library. Data is extracted from apartments.com. There are two versions of code, one uses Scrapy (see scrape_house_price.ipynb) and one uses Selenium (scrape_house_price_using_selenium.ipynb). The webscraper obtains the number of beds and the price for each rent that it sees. Rental data scraped covers 5 main cities in USA, namely, New York city, Austin - TX, Tampa - FL, Minneapolis - MN, Saint Louis - MO. Webscraped data is exported into rents.csv file.

### 2. Data cleaning
Data webscraped then is cleaned and transformed (see more at <a href="https://github.com/tnguyen7s/Data-Science-Projects/blob/main/House-Prices-In-USA/main/House_Prices_In_USA_Data_Cleaning.ipynb">House_Prices_In_USA_Data_Cleaning.ipynb</a>) into a desired format using Pandas library and exported to a csv file named cleaned_rents.csv.


### 3. Data Analysis
Well-formated data is then analyzed using fundamental descriptive statistics, inferential statistics, and hypothesis testings concepts (See more at house-prices-analysis.xlsx)

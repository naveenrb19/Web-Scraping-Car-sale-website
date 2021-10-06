# Web-Scraping-Car-sale-website

* The notebook file contains code to scrape website from **www.edmunds.com** for details about listed cars.
* The code takes zip code and search radius as input.
* Post that after search according to user preference is carried out it counts the number of pages connected to search done as per user preference.
* Once count of pages is gathered the code loops through each page and appends hyperlink of each car listed in each page into a list.
* Post that each page connected to a car is scraped for details such as Name,Price,VIN,Vehicle Summary and Top features.
* At the end the accumulated data is saved as an excel file.

# Comprehensive-Data-Analysis-of-Apartment-rental-offers-in-Germany

### Data
* **Where is the data from?**

The data was scraped from Immoscout24, the biggest real estate platform in Germany. Immoscout24 has listings for both rental properties and homes for sale, however, the data only contains offers for rental properties.

At a given time, all available offers were scraped from the site and saved. This process was repeated three times, so the data set contains offers from the dates 2018-09-22, 2019-05-10 and 2019-10-08.


* **Content**

The data set contains most of the important properties, such as living area size, the rent, both base rent as well as total rent (if applicable), the location (street and house number, if available, ZIP code and state), type of energy etc. It also has two variables containing longer free text descriptions: description with a text describing the offer and facilities describing all available facilities, newest renovation etc. The date column was added to give the time of scraping.

* **Acknowledgements**

The data belongs to www.immobilienscount24.de and is for research purposes only. The data can be found in the following [kaggle link](https://www.kaggle.com/corrieaar/apartment-rental-offers-in-germany).

### Analysis
All of the analysis is in the notebook : `Analysis_notebook.ipynb`
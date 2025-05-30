# Project Overview

In this project, we'll predict tomorrow's temperature using historical data.  We'll start by downloading a dataset of local weather.  You can customize this to your own location.  Then, we'll clean the data and get it ready for machine learning.  We'll build a system to make historical predictions.  Then, we'll add more predictors to improve the model.  We'll end with how to make next-day predictions.

**Project Steps**
* Download weather data
* Clean and graph data
* Create a testing framework
* Improve model accuracy


## Code

File overview:

* `predict.ipynb` - predict the temperature

# Prerequisites

To complete this project, you'll need to have a good understanding of:

* Python syntax, including functions, if statements, and data structures
* Data cleaning
* Pandas syntax
* Using Jupyter notebook


# Local Setup

## Installation

To follow this project, please install the following locally:

* JupyerLab
* Python 3.8+
* Python packages
    * pandas
    * scikit-learn

## Data

We'll download our dataset from NOAA, a US government agency.  You can follow these instructions to download the data:

* Go to [NOAA Search](https://www.ncdc.noaa.gov/cdo-web/search)
* Enter the years you want data for (I recommend starting with 1970), and search for the closest airport to you.
    * <img src="../weather/imgs/download_1.png" width="500"/>
* Click add to cart on the airport you want.
    * If there is no airport near you, try your city or country name instead.
    * <img src="../weather/imgs/download_2.png" width="500"/>
* Go to the [cart](https://www.ncdc.noaa.gov/cdo-web/cart)
* Select the csv format and click continue.
    * <img src="../weather/imgs/download_3.png" width="500"/>
* Select all of the checkboxes for data types.
    * <img src="../weather/imgs/download_4.png" width="500"/>
* Enter your email and click continue.
    * <img src="../weather/imgs/download_5.png" width="500"/>
* You'll get an email with a link to download the data.
    * <img src="../weather/imgs/download_6.png" width="500"/>
* Make sure to take a look at the [data documentation](https://www1.ncdc.noaa.gov/pub/data/cdo/documentation/GHCND_documentation.pdf) as well.

# Crime of 3 Cities Analysis

## Prerequisites / Installs

Data Setup:

To download the data, first use the CSV_Data_Download.ipynb file. This file utilizes the Selenium type library to webscrape data and download the CSV files. 
In order for below to work download Chrome onto your machine. Once in Chrome check the version of Chrome you are on.  You can check the version by copying and pasting the below line into Chrome:
chrome://settings/help

Next, download chromedriver from the link below for the version of Chrome you are using:
https://chromedriver.chromium.org/downloads
and place the chromdriver.exe file into the  Project1 folder that is from the repository when you download

Installs You May Need (if not installed already)
Run the following in terminal:

pip install jupyter-dash

Ensure you have all 3 data sets in the Data folder as well as the Chicago Population CSV file

## Project Links for Data Sets
## City Links
## San Francisco
[San Francisco](https://data.sfgov.org/Public-Safety/Police-Department-Incident-Reports-2018-to-Present/wg3w-h783)

## Philly
[Philadelphia](https://phl.carto.com/api/v2/sql?q=SELECT+*,+ST_Y(the_geom)+AS+lat,+ST_X(the_geom)+AS+lng+FROM+incidents_part1_part2&filename=incidents_part1_part2&format=csv&skipfields=cartodb_id)

## Chicago
[Chicago](https://data.cityofchicago.org/api/views/ijzp-q8t2/rows.csv?accessType=DOWNLOAD&amp;api_foundry=true)

# References
* https://dash.plotly.com/
* https://community.plotly.com/t/use-one-dropdown-countries-to-change-all-graphs-in-my-dashboard/10532
* https://www.selenium.dev/documentation/
* https://hvplot.holoviz.org/
* https://docs.mapbox.com/api/overview/
* https://panel.holoviz.org/
* https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.iloc.html

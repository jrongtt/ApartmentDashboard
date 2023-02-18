# Apartment Dashboard

Code for an Tableau Dashboard for apartment data.

Apartment Data was Web Scraped for Jan 2023 1 Bedroom, 1 Bathroom Apartment Listings in Zumper and saved to CSV Files. This code can be found in: 'PythonwebScraper.ipynb'. The CSV Files for each city under the 'data' directory (data-coords directory has lat and long but less data).

The median rental price was then calculated for the 25 cities and added to a csv along with the median incomes for those cities in the notebook file 'medians.ipynb'. This data was saved to a cleaned CSV file: city_median_income.csv.


Finally a Tableau visualization dashboard was created using the median rent and per capita income (from https://www.statista.com/statistics/205618/per-capita-income-in-the-top-20-most-populated-cities-in-the-us/ ). The final Tableau dashboard can be viewed here: https://jrongtt.github.io/tab.html

# INTERSTELLAR PAGE VIEWS OVER TIME

## Project Description
This project extracts page view data using Wikimedia's pageviews REST API from the "Interstellar (film)" Wikipedia page. I extract, transform, and load the data into a CSV file, and display a scatter plot with the data collected. I would like to see how the viewcount has changed over a period of around a year. 

## API's Used
Wikimedia REST API: https://wikimedia.org/api/rest_v1/#/

CSV API: https://docs.python.org/3/library/csv.html

JSON API: https://docs.python.org/3/library/json.html

Pandas: https://pandas.pydata.org/docs/

matplotlib: https://matplotlib.org/stable/api/index.html

## Data Attributes 
Date(date): The date of the recorded view count.
Views(integer): The recorded view count on a specific day.
Day of Week(string): What day of the week a recorded view count is.
Month(string): What month is the day recorded in. 

# Licenses
My code is under the MIT License, which is in this repository. 
My data is accessed with the GNU Free Documentation License, which is in this repository.

# Known issues or Biases 
There are no issues or biases I see in the data set, however, one could classify the large outliers as issues in the data set if trying to extract an R correlation.
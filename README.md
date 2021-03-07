# weather-website-dashboard

## Getting Started

The weather dashboard was created using HTML and CSS, utilizing Bootstrap (https://getbootstrap.com/)

index.html file contains the Landing Page for the Weather Dashboard website

All visualizations for this project were created in a different repository (https://github.com/Seltsam1/python-api-weather)


## Features

- index.html
  - Explanation of project
  - Linkes to the 4 visualization pages of each scatter plot
  - A navigation bar

- visualizations (temp.html, humidity.html, cloudiness.html, windspeed.html)
  - Focus on each specific visualization
  - Paragraph explaining the scatter plot
  - Visualization portion on the right will show a border around currently selected chart

- comparison.html
  - All visualizations on the same page for easy comparison
  - Utilizes the Bootstrap grid
  - Clicking on an image will take user to corresponding visualization page

- data.html
  - Displays a respsive table containing all the data used for the scatter plots
  - Utilizes a bootstrap table component
  - Data was first prepared in the csv-to-html.ipynb file 

- styles.css
  - Includes additional formatting of html
  - Media queries for different size screens (600px and below)

- csv-to-html.ipynb
  - Jupyter Notebook file with python code to convert csv into DataFrame, then into html
  - Preliminary step for the data.html page

## Licensing by:

The code in this project is licensed under MIT license.

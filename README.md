# Project Summar
----------------------
## Data Journalism and D3

![Newsroom](https://media.giphy.com/media/v2xIous7mnEYg/giphy.gif)

This Project is About Creating a Data Visualition using D3.JS, and JavaScript by analyzing the current trends shaping people's lives, as well as creating charts, graphs, and interactive elements to help readers understand my findings.



The data set used in this project is based on 2014 ACS 1-year estimates: https://factfinder.census.gov/faces/nav/jsf/pages/searchresults.xhtml](https://factfinder.census.gov/faces/nav/jsf/pages/searchresults.xhtml)
This data set incldes data on rates of income, obesity, poverty, etc. by state. MOE stands for "margin of error."

### Step 1: D3 Dabbler

![4-scatter](Images/4-scatter.jpg)

First I created a scatter plot between two of the data variables: `Healthcare vs. Poverty`.

Using the D3 techniques I created a scatter plot that represents each state with circle elements.

* Include state abbreviations in the circles.

* Create and situate your axes and labels to the left and bottom of the chart.

* I used Python Server `python -m http.server` to run the visualization. This will host the page at `localhost:8000` in the web browser.

- - -

### Step 2: More Data, More Dynamics

![7-animated-scatter](Images/7-animated-scatter.gif)

In this Step I included more demographics and more risk factors. Placed additional labels in my scatter plot and gave them click events so that the users can decide which data to display. Added animation to the transitions of the circles' locations as well as the range of the axes. created three for each axis.

* I did bind all of the CSV data to the circles. This will let the user easily determine their x or y values when he clicks the labels.

#### 2. Incorporate d3-tip

While the ticks on the axes allow us to infer approximate values for each circle, it's impossible to determine the true value without adding another layer of data. Added tooltips to my circles and display each tooltip with the data that the user has selected. Used the `d3-tip.js` plugin developed by [Justin Palmer](https://github.com/Caged).

![8-tooltip](Images/8-tooltip.gif)


- - -


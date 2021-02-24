# Web Visualization Dashboard

- - -

I used HTML and CSS to create a visualization dashboard website by plotting [weather data](Resources/cities.csv).
- - -  

## Latitude Analysis Dashboard - Website

The website consists of 7 pages total, including:

* A landing page containing:
  * An explanation of the project.
  * Links to each visualizations page. 
  * A sidebar containing preview images of each plot, and clicking an image should take the user to that visualization.

![](Images/landingResize.png)

* Four visualization pages, each with:
  * A descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison.
  * A paragraph describing the plot and its significance.

  ![](Images/visualize-lg.png)

* A "Comparisons" page that:
  * Contains all of the visualizations on the same page so we can easily visually compare them.
  * Uses a Bootstrap grid for the visualizations.
    * The grid contains two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.

 ![](Images/comparison-lg.png) 

* A "Data" page that:
  * Displays a responsive table containing the data used in the visualizations.
    * The table is a bootstrap table component. 
    * Used Pandas to generate a HTML table from a pandas dataframe. 

![](Images/data-lg.png)

* At the top of every page, there is a navigation menu that:
  * Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
  * Contains a dropdown menu on the right of the navbar named "Plots" that provides a link to each individual visualization page.
  * Provides two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.
  * Is responsive.

![](Images/nav-lg.png)

- - -
The data is provided by UCSD Extension: Data Science and Visualization Bootcamp.
- - -

Contact:

Email: arcebri1@gmail.com
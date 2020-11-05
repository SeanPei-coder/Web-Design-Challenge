# Web-Design-Challenge

## Background

I am using what I've learned about HTML and CSS to create a dashboard showing off the analysis I've done.

## Latitude - Latitude Analysis Dashboard with Attitude

In building this dashboard, I'll create individual pages for each plot and a means by which I can navigate between them. These pages will contain the visualizations and their corresponding explanations. I'll also have a landing page, a page where we can see a comparison of all of the plots, and another page where we can view the data used to build them.

## Website Specification

The website consists of 7 pages total, including:
- A landing page containing:

  - An explanation of the project.
  - Links to each visualizations page. There is a sidebar containing preview images of each plot, and clicking an image should take the user to that visualization.


- Four visualization pages, each with:

  - A descriptive title and heading tag.
  - The plot/visualization itself for the selected comparison.
  - A paragraph describing the plot and its significance.


- A "Comparisons" page that:

  - Contains all of the visualizations on the same page so we can easily visually compare them.
  - Uses a Bootstrap grid for the visualizations.

  - The grid will be two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.




- A "Data" page that:

  - Displays a responsive table containing the data used in the visualizations.

  - The table will be a bootstrap table component. 
  
  
The website will, at the top of every page, have a navigation menu that:

- Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
- Contains a dropdown menu on the right of the navbar named "Plots" that provides a link to each individual visualization page.
- Provides two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.
- Is responsive (using media queries).

Finally, the website will be deployed to GitHub pages.


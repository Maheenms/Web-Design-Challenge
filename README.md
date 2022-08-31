# Web-Design-Challenge
 Web Visualization Dashboard

## Background
HTML stands for HyperText Markup Language. For a web page creation, HTML is the standard markup language. It allows the creation and structure of sections, paragraphs, and links using HTML elements (the building blocks of a web page) such as tags and attributes. CSS stands for Cascading Style Sheets. It describes how HTML elements are to be displayed.
In this assignment we need to use what weve laerned about HTML and CSS to create a dashboard featuring the analysis that we've done, as captured in the following image:

![Image](./Assets/Images/landingResize.png)


## Before We Begin we need to do the following:

1. Create a new repository for this project called `Web-Design-Challenge`. 

2. Clone the new repository to our computer.

3. Inside our local Git repository, add our HTML files along with three folders; `assets`, `Resources` and `visualizations`. 

  * Include an `index.html` file in the main folder, which we will edit later and should be the landing page that a user first encounters when viewing.

  * Inside the `assets` folder, create two more folders: `css` and `images`, which we will use to store our CSS and image assets, respectively.

  * The `Resources` folder should contain the CSV file with the data we are using for this website. The `visualizations` folder will contain the HTML pages that display wer visualizations.

4. Push the changes from Steps 1 through 3 to GitHub.

5. Deploy to GitHub Pages. 

## Instructions 

For this homework assignment, we'll create a website by using visualizations that were created in wer Python-APIs homework, or we can use the [weather data](./Resources/cities.csv) provided.

As we build this dashboard, we'll create individual pages for each plot and a way to navigate between them. These pages will contain the visualizations and des. we will also build a landing page to provide a comparison of all the plots, along with another page to present the data used to build them.

### Website Requirements
 
The website must consist of seven pages in total, including:

* A landing page containing the following elements:

  * An explanation of the project

  * Links to each visualizations page. There should be a sidebar containing preview images of each plot. Clicking an image should take the user to that visualization.

* Four visualization pages, stored in the `visualizations` folder, each with the following elements:

  * A descriptive title and heading tag.

  * The plot or visualization for the selected comparison (latitude vs: max temperature, humidity, cloudiness, or wind speed). The images displayed on these pages should be stored in the `assets/images` folder.

  * A paragraph describing the plot and its significance.

* A "Comparisons" page that does the following:

  * Contains all of the visualizations on the same page so they can easily be compared with each other.

  * Uses a Bootstrap grid for the visualizations.

    * The grid must be two visualizations across medium and large screens, and it must be one visualization across on extra-small or small screens.

* A "Data" page that displays a responsive table containing the data used in the visualizations.

  * The table must be a Bootstrap table component. Refer to the [Bootstrap documentation](https://getbootstrap.com/docs/4.3/content/tables/#responsive-tables) for how to use responsive tables. 

  * The data must come from exporting the `.csv` file as HTML or by converting it to HTML. Try using a tool that we already know: Pandas. Pandas has a method, appropriately called `to_html`, that allows we to generate an HTML table from a Pandas DataFrame. To learn more, review the [documentation](https://pandas.pydata.org/pandas-docs/version/0.17.0/generated/pandas.DataFrame.to_html.html).

At the top of every page, the website must have a navigation menu with the following elements:

* It should have the name of the site on the left of the navigation bar, allowing users to return to the landing page from any page.

* It should contain a dropdown menu on the right of the navigation bar, named "Plots," to provide links to each individual visualization page.

* It should provide two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.

* It should be responsive (using media queries). 

Finally, the website must be deployed to GitHub Pages.

Once finished, we need to submit links to 1) the deployed app and 2) the GitHub repository.

We need to ensure our repository has regular commits and a descriptive `README.md` file.

### Considerations

* We may use the weather data we collected for the WeatherPy section of wer Python-APIs Homework, or we may use the included [cities dataset](./Resources/cities.csv) and pull the images from the [assets folder](./Assets/Images).

* We must use Bootstrap. This includes using the Bootstrap `navbar` component for the header on every page, the Bootstrap table component for the data page, and the Bootstrap grid for responsiveness on the comparison page.

* We must deploy our website to GitHub Pages, with the website working on a live, publicly accessible URL as a result.

* We need to make sure to use a CSS media query that uses Bootstrap and/or `@media` for the navigation bar.

* We need to make sure that our website works at all window widths or sizes.

* We can take some liberty in the visual aspects, but we need to keep the core functionality the same.

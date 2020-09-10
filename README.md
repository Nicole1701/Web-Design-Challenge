
# Web Visualization Dashboard
Click here to got to the website: [The Office: An Analysis](https://nicole1701.github.io/web-design-challenge/WebVisualizations/index.html)

![The Office](WebVisualization/images/office_logo_2.png)


### Website Requirements
The website must consist of at least 7 pages total, including:
* A landing page containing:
    * An explanation of the project.
    * Links to each visualizations page. There should be a sidebar containing preview images of each plot, and clicking an image should take the user to that visualization.
* Four visualization pages, each with:
    * A descriptive title and heading tag.
    * The plot/visualization itself for the selected comparison.
     A paragraph describing the plot and its significance.
* A "Comparisons" page that:
    * Contains all of the visualizations on the same page so we can easily visually compare them.
    * Uses a Bootstrap grid for the visualizations.
    * The grid must be two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.
* A "Data" page that:
    * Displays a responsive table containing the data used in the visualizations.
    * The table must be a bootstrap table component. Hint: Bootstrap has a relatively easy way to make tables responsive but it isn't the only way.
    * The data must come from exporting the .csv file as HTML, or converting it to HTML. Try using a tool you already know, pandas. Pandas has a nifty method approprately called to_html that allows you to generate a HTML table from a pandas dataframe. See the documentation here. Or use an online html table generator.

The website must, at the top of every page, have a navigation menu that:
* Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
* Contains a dropdown menu on the right of the navbar named "Plots" that provides a link to each individual visualization page.
* Provides two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.
* Is responsive such that at smaller screen sizes the navbar links are replaced by a sandwich menu. The nav must have similar behavior as the screenshots "Navigation Menu" section (notice the background color change). Again, bootstrap has relatively easy ways to accomplish this, but it's not the only way.

### Considerations
* You have three options for choosing the content for your website:
    * You may use the weather data from the Resources folder and pull the corresponding images from the included assets folder,
    * You may use the included weather data and use your own images from the previous assignment,
    * Or you may choose another dataset entirely and generate your own images.
* You must use Bootstrap. This includes:
    * Using the Bootstrap navbar component for the header on every page,
    * The Bootstrap table component for the data page, and
    * A Bootstrap grid for responsiveness on the comparison page.
* You must deploy your website to GitHub pages, with the website working on a live, publicly accessible URL as a result.
* Be sure to use a CSS media query to control the behavioral states of the navigation menu.
* Be sure your website works at all window widths/sizes.
* Feel free to take some liberty in the visual aspects, but keep the core functionality the same.


### Bonuses
* Use a different dataset! The requirements above still hold, but make it your own.
* Use a Bootstrap theme or template to customize your website. You may use a source like Start Bootstrap or Bootstrap Made. * Make it look snazzy, give it some attitude. And be sure you also meet all of the requirements listed above and in the rubric.
* Add extra visualizations! The more comparisons the better, right?
* Use meaningful icons next to links in the header. One well-documented method is to use Font Awesome.
* Have visualization navigation on every visualizations page with an active state.
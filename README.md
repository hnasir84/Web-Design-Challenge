## Web-Design-Challenge

For this project, I created a website by using visualizations that were created in my Python-APIs project.
I created individual pages for each plot and a way to navigate between them. These pages  contain the visualizations and destinations. I built landing page to provide a comparison of all the plots, along with another page to present the data used to build them.



# Project Requirements


The website must consist of seven pages in total, including:


A landing page containing the following elements:


An explanation of the project

![](../../../../../../C:/Users/user/Desktop/DSBCGA/Web-Design-Challenge/web_images/MainPage.png)


Links to each visualizations page. There should be a sidebar containing preview images of each plot. Clicking an image should take the user to that visualization.



Four visualization pages, stored in the visualizations folder, each with the following elements:


- A descriptive title and heading tag.


The plot or visualization for the selected comparison (latitude vs: max temperature, humidity, cloudiness, or wind speed). The images displayed on these pages should be stored in the assets/images folder.


-  A paragraph describing the plot and its significance.




- A "Comparisons" page that does the following:

Contains all of the visualizations on the same page so they can easily be compared with each other.

![](../../../../../../C:/Users/user/Desktop/DSBCGA/Web-Design-Challenge/web_images/comparison.png)

Uses a Bootstrap grid for the visualizations.

The grid must be two visualizations across medium and large screens, and it must be one visualization across on extra-small or small screens.





- A "Data" page that displays a responsive table containing the data used in the visualizations.

![](../../../../../../C:/Users/user/Desktop/DSBCGA/Web-Design-Challenge/web_images/Data.png)

The table must be a Bootstrap table component. Refer to the Bootstrap documentation for how to use responsive tables.


The data must come from exporting the .csv file as HTML or by converting it to HTML. Try using a tool that you already know: Pandas. Pandas has a method, appropriately called to_html, that allows you to generate an HTML table from a Pandas DataFrame. To learn more, review the documentation.




At the top of every page, the website must have a navigation menu with the following elements:


It should have the name of the site on the left of the navigation bar, allowing users to return to the landing page from any page.


It should contain a dropdown menu on the right of the navigation bar, named "Plots," to provide links to each individual visualization page.


It should provide two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.


It should be responsive (using media queries). The navigation bar must be similar to the screenshots in the "Navigation Menu" section (notice the background color change).


Finally, the website must be deployed to GitHub Pages.

https://hnasir84.github.io/Web-Design-Challenge/

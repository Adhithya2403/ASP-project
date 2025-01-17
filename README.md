# ASP-project
Source code 
How to Use
Run the ASP.NET Core project.
Navigate to the page, enter shift details in the form, and click "Submit."
View the data in the table or visualize it using the buttons for different chart types.
This provides a cohesive interface for inputting and visualizing shift-related data.

EXPLANATION
Form Section:

Users can input shift details such as from-date, to-date, shift, and employee ID.
Submitting the form can be extended to dynamically populate the table and charts.
Results Section:

Displays a table where shift data will be shown. Rows can be dynamically added using JavaScript or a backend call.
Chart Section:

Contains buttons for visualizing the data in 8 different chart types.
Uses Chart.js to render charts dynamically.
Chart.js Script:

The renderChart function takes the chart type as input and dynamically updates the chart displayed in the <canvas> element.

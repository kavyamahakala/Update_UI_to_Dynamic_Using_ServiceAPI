# Update_UI_to_Dynamic_Using_ServiceAPI
This is a web application which is developed to forecast the weather for the next 7 days from the given date using Restful Web Services. The data consists of weather information from 2013 (date, tmax and tmin). In this application, Ajax is used to call the form and display the result without refreshing the current page. The output contains of a graphical representation of the weather information.

The URL for accessing the web application is: http://ec2-13-58-39-78.us-east-2.compute.amazonaws.com:5000/ The application works best in Google Chrome.

Using AWS E2 instance we deploy the application. The application contains of a python file (homework3.py) and a html file (ui.html)

While the application displays the graph for the next 7 days from the selected date. This is displayed on the same page without refreshing to a new page again. While this done, another chart is displayed which is the information from a third party API (Accuweather). This chart displays the tmax and min from current date to next 5 days.


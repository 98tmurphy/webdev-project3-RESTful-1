# The St Paul Crime Map
This project was designed to illustrate all police responses in the St Paul area.
To do so , we created a REST web server that stores and keeps all of the data. The server then sends the data to the webpage, which then parses the data and extracts all of the location, time, date, and visit nature information. This is then all fed to a map API, which displays the information on a map.

The user can filter the data based on a wide range of options. They can choose the date range, the time of day, the catagory of police response(robbery, violent crime, misc, etc) and then the specific crime code. The user can even select only certain neighborhoods, which are hard coded into the page.

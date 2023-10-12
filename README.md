# I310DCodingAssignment
This repository contains code to collect, process, and visualize data on the highest mountains on Earth. The data is collected from the Wikipedia page "List of highest mountains on Earth".

The code then parses the HTML content of the page and finds the table with the class wikitable. The code then extracts the table data into a list of dictionaries, with each dictionary representing a single mountain. The code then creates a DataFrame from the list of dictionaries and saves the DataFrame as a CSV file named mountains_data.csv.

The code then loads the mountain data from the CSV file and creates a bar chart visualization of the mountain heights. The code then saves the visualization as an image named mountain_heights.png.

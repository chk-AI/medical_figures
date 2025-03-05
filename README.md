# medical_figures
Medical figures with research data

Step 1: Find or create a template of what you want to visualize.

Step 2: Annotate the areas using a program (I used FIJI (ImageJ), which is open-source) by clicking along the edges with the polygon tool. The more points you click, the smoother the final figure will be. This step took the longest time. There might be a better way to do this, for example using photoshop.

Step 3: Export the coordinates as x-y coordinates to a CSV file (I created a separate file for each area and then merged them in R, adding a variable to indicate the area).

Step 4: Import the CSV files into R.

Step 5: Merge the dataset with additional data in R and visualize it using geom_polygon with a fill representing the data you want to display in ggplot.

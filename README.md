# medical_figures
How to create medical figures for visualizing research data

# Creating a figure from the beginning
# Step 1: 
Find or create a template of what you want to visualize.

# Step 2: 
Annotate the areas using a program (I used FIJI (ImageJ), which is open-source) by clicking along the edges with the polygon tool. The more points you click, the smoother the final figure will be. This step took the longest time. There might be a better way to do this, for example using photoshop.

# Step 3: 
Export the coordinates as x-y coordinates to a CSV file (I created a separate file for each area and then merged them in R, adding a variable to indicate the area).

# Step 4: 
Import the CSV files into R.

# Step 5: 
Merge the dataset with additional data in R and visualize it using geom_polygon with a fill representing the data you want to display in ggplot.




# Using our code to create a brain figure
Open the R-markdown file and load the csv-files with the x-y coordinates for the brain figures. You can replace our example data with your own data. Please cite our work if you want to apply the figure to your own data:

Krag, C. H., Müller, F. C., Gandrup, K. L., Raaschou, H., Andersen, M. B., Brejnebøl, M. W., Sagar, M. V., Bojsen, J. A., Rasmussen, B. S., Graumann, O., Nielsen, M., Kruuse, C., & Boesen, M. (2023). Diagnostic test accuracy study of a commercially available deep learning algorithm for ischemic lesion detection on brain MRIs in suspected stroke patients from a non-comprehensive stroke center. European Journal of Radiology, 168, 111126. Artikel 111126. https://doi.org/10.1016/j.ejrad.2023.111126


![image](https://github.com/user-attachments/assets/a4ea3322-20bc-475c-a68e-e31d44c7566b)

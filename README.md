# Seaborn for Data Visualization

## This repository has some files with Python codes that I created while doing the Seaborn courses by DataCamp

## Course Scope

Introduction to Data Visualization with Seaborn
1. Introduction to Seaborn
2. Visualizing two Quantitative Variables
3. Visualizing a Categorical and a Quantitative Variable
4. Customizing Seaborn Plots

Intermediate Data Visualization with Seaborn
1. Introduction to Seaborn
2. Customizing Seaborn Plots
3. Additional Plot Types
4. Create Plots on Data Aware Grids

## Key Takeaways

- Plots with Lists
<br>
<br>
Creating a Scatter Plot
<br>
![Alt text](/screenshots/sns_scatter1.JPG)
<br>
Creating a Count Plot
<br>
![Alt text](/screenshots/sns_countplot1.JPG)
<br>

- Plots with Pandas DataFrames
<br>
<br>
Creating a Scatter Plot 
<br>
"Hue" will define a third variable and hue_order will set the order accordingly.<br>
The first variable is Total Bill (x axis), the second variable is Tip (y axis) and the third variable is Smoker (Y/N), shown in the graph by colors: orange or blue.
<br>
![Alt text](/screenshots/sns_scatter2_hue.JPG)
<br>
Creating a Count Plot
<br>
![Alt text](/screenshots/sns_countplot2.JPG)
<br>
Creating a Count Plot
<br>
We can define the colors we want to be shown in the plot by creating a dictionary mapping subgroup.<br>
In this example, the dictionary maps the value "Rural" to the color green and the value "Urban" to the color blue.
<br>
![Alt text](/screenshots/sns_countplot2_palette.JPG)
<br>

- Relational Plots with relplot()
<br>
<br>
The Seaborn Relational Plot (relplot) allows us to visualise how variables within a dataset relate to each other. 
<br>
Creating a Scatter Plot 
<br>
In this example, you can make subplots based on the study time by defining the variable "col":
![Alt text](/screenshots/relplot1.JPG)
<br>
Changing Styles in Scatter Plots
<br>
<br>
You can use Hue and Style to create different colored points and also to change the style of the points:
<br>
![Alt text](/screenshots/relplot_style1.JPG)
<br>
You can set the variable alpha to change the transparency of the points. This is very useful to help with the data visualization when you have many points in your Scatterplot.
<br>
![Alt text](/screenshots/relplot_style2.JPG)
<br>
Changing Styles in Line Plots
<br>
<br>
You can use Hue and Style to create different styles and colors of lines for subgroups:
![Alt text](/screenshots/relplot_line1.JPG)
<br>
You can use Markers to create different marker styles on the subgroup lines:
![Alt text](/screenshots/relplot_line2.JPG)
<br>


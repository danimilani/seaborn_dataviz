# Seaborn for Data Visualization

This repository has some files with Python codes that I created while doing the Seaborn courses by DataCamp.

## Course Scope

Introduction to Data Visualization with Seaborn
<br><br>
[1. Introduction to Seaborn](#introduction-to-seaborn) <br>
[2. Visualizing two Quantitative Variables](#visualizing-two-quantitative-variables) <br>
[3. Visualizing a Categorical and a Quantitative Variable](#visualizing-categorical-and-a-quantitative-variable) <br>
[4. Customizing Seaborn Plots](#customizing-seaborn-plots) <br>

Intermediate Data Visualization with Seaborn
1. Introduction to Seaborn
2. Customizing Seaborn Plots
3. Additional Plot Types
4. Create Plots on Data Aware Grids

## Key Takeaways

### Introduction to Seaborn 
<br>

**Plots with Lists**
<br>
<br>

*Creating a Scatter Plot*

<br>

![Scatter Plot](/screenshots/sns_scatter1.JPG)

<br>

*Creating a Count Plot*

<br>

![Count Plot](/screenshots/sns_countplot1.JPG)

<br>

**Plots with Pandas DataFrames**
<br>
<br>

*Creating a Scatter Plot*

<br>
"Hue" will define a third variable and hue_order will set the order accordingly.
<br>
The first variable is Total Bill (x axis), the second variable is Tip (y axis) and the third variable is Smoker (Y/N), shown in the graph by colors: orange or blue.
<br>

![Scatter Plot 2](/screenshots/sns_scatter2_hue.JPG)

<br>

*Creating a Scatter Plot*

<br>

![Scatter Plot 3](/screenshots/sns_countplot2.JPG)

<br>

*Creating a Count Plot*

<br>
We can define the colors we want to be shown in the plot by creating a dictionary mapping subgroup.<br>
In this example, the dictionary maps the value "Rural" to the color green and the value "Urban" to the color blue.
<br>

![Count Plot 2](/screenshots/sns_countplot2_palette.JPG)

<br>

### Visualizing two Quantitative Variables
<br>

**Relational Plots with relplot()**
<br>
<br>

The Seaborn Relational Plot (relplot) allows us to visualise how variables within a dataset relate to each other. 

<br>

*Creating a Scatter Plot*

<br>

In this example, you can make subplots based on the study time by defining the variable "col":

<br>

![Rel Plot](/screenshots/relplot1.JPG)

<br>

*Changing Styles in Scatter Plots*

<br>
<br>
You can use Hue and Style to create different colored points and also to change the style of the points:
<br>

![Rel Plot Style](/screenshots/relplot_style1.JPG)

<br>
You can set the variable alpha to change the transparency of the points. This is very useful to help with the data visualization when you have many points in your Scatterplot.
<br>

![Rel Plot Style 2](/screenshots/relplot_style2.JPG)

<br>

*Changing Styles in Line Plots*

<br>
<br>
You can use Hue and Style to create different styles and colors of lines for subgroups:
<br>

![Line Plot Style](/screenshots/relplot_line1.JPG)

<br>
You can use Markers to create different marker styles on the subgroup lines:
<br>

![Line Plot Style 2](/screenshots/relplot_line2.JPG)

<br>

### Visualizing a Categorical and a Quantitative Variable
<br>

*Count Plots and Bar Plots*

<br>

- catplot() for Categorical Plots: comparisons between groups - count plots and bar plots - kind = "count" <br>
- catplot() for Bar Plots: displays the mean of quantitative variable per category - kind = "bar". The confidence interval is automatically set as 95% but can be changed via "ci" <br>

![Cat Plot Style 1](/screenshots/cat_quant_1.JPG)

<br>

![Cat Plot Style 2](/screenshots/cat_quant_2.JPG)

<br>

*Box Plots*

<br>

A box plot shows the distribution of quantitative data. The color box represents the 25th to 75th percentile and the line in the middle of the box represents the median. The whiskers give a sense of the spread of the distribution and the floating points, the outliers. <br>

<br>

![Box Plot Style 1](/screenshots/box_1.JPG)

<br>

![Box Plot Style 2](/screenshots/box_2.JPG)

<br>

![Box Plot Style 3](/screenshots/box_3.JPG)

<br>

*Point Plots*

<br>

They show the mean of a quantitative variable for the observations in each category, plotted as a single point. The vertical lines show the interval of confidence. One of the axis is a categorical variable.

<br>

![Point Plot Style 1](/screenshots/point_1.JPG)

<br>

![Point Plot Style 2](/screenshots/point_2.JPG)

<br>

![Point Plot Style 3](/screenshots/point_3.JPG)

<br>

### Customizing Seaborn Plots
<br>

- Style: you can customize your graph with different styles: whitegrid, ticks, dark, darkgrid.
<br>

![Style 1](/screenshots/style_whitegrid.JPG)

<br>

![Style 2](/screenshots/style_ticks.JPG)

<br>

![Style 3](/screenshots/style_dark.JPG)

<br>

![Style 4](/screenshots/style_darkgrid.JPG)

<br>

- Palletes: you can customize the color palettes with diverging, sequential or your own palette.
<br>

![Palette 1](/screenshots/palette_diverging.JPG)

<br>

- Scales: you can change the scale of your plot with the function "set context" - the options are: options are: "paper", "notebook", "talk" and "poster".
<br>

![Scale 1](/screenshots/scale1.JPG)

<br>

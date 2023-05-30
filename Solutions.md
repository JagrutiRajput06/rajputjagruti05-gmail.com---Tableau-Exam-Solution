## 1. Explain in detail the area graphs and line graphs in tableau and how to create them with examples. (With the help of an example create one in tableau)

### Area Graphs:
- Area graphs are used to display quantitative data over time, typically representing cumulative totals or proportions.
- The graph consists of filled areas bounded by lines, with the area between the lines filled with color.
- Area graphs are useful for comparing the overall values and relative proportions of different categories over time.

Create the area graph:
- Drag the time-related field (Year) to the Columns shelf.
- Drag the quantitative field  to the Rows shelf.
- Tableau will automatically aggregate the values based on the time period.
- To create the area graph, click on the "Show Me" panel on the right side of the interface and select the "Area" chart type.


### Line Graphs:
- Line graphs are used to show the relationship between two continuous variables, typically representing trends, changes, or comparisons over time.
- The graph consists of data points connected by straight lines.
- Line graphs are effective for illustrating the magnitude and direction of change in data.

Create the line graph:
- Drag the time-related field (Year) to the Columns shelf.
- Drag the quantitative field  to the Rows shelf.
- Tableau will automatically aggregate the values based on the time period.
- To create the line graph, click on the "Show Me" panel on the right side of the interface and select the "Line" chart type.




## 2. What are the different steps in grouping fields and combining tables in tableau ? Explain with examples. (With the help of an example create one in tableau)

### Grouping the fields:
- Right-click on the selected fields and choose "Group."
- A new group will be created with the selected field values.



### Join the tables:
- In the Data pane, locate the common field in one table.
- Click on the field and drag it to the common field in the other table.
- Tableau will automatically detect the join type based on the data.
- If needed, you can edit the join type by right-clicking on the join line in the Data pane and selecting the desired join type (e.g., Inner Join, Left Join).


## 3. What is the use of color and size options in the marks cart of tableau ? (With the help of an example create one in tableau)

In Tableau, the color and size options in the Marks card allow you to encode additional information within your visualizations. They provide a way to visually represent data dimensions or measures, enhancing the understanding of patterns, comparisons, and relationships in your data.

The use of color and size options in the Marks card:

<b>Color</b>:
- The color option allows you to assign different colors to data points based on a chosen field or measure.
- It helps in highlighting categories, groups, or specific data points within your visualization.
- By assigning distinct colors to different categories, you can easily differentiate and compare them.

<b>Size</b>:
- The size option allows you to vary the size of data points based on a selected measure.
- It helps emphasize the magnitude or importance of a particular data point or value.
- By adjusting the size of data points, you can visually highlight trends or outliers in your visualization.





## 4. What are the different joins supported by tableau? (With the help of an example create one in tableau)

<b>The common types of joins in Tableau are:</b>

<b>1. Inner Join:</b> 
An inner join returns only the rows that have matching values in both tables being joined. It includes only the data that appears in both tables.

<b>2. Left Join:</b> 
A left join returns all the rows from the left table and the matching rows from the right table. If there are no matches in the right table, it includes null values for the columns of the right table.

<b>3. Right Join:</b> 
A right join returns all the rows from the right table and the matching rows from the left table. If there are no matches in the left table, it includes null values for the columns of the left table.

<b>4. Full Outer Join:</b> 
A full outer join returns all the rows from both tables. It includes all the data from the left table and the right table, and if there are no matches, it includes null values for the non-matching columns.



## 5. Explain the steps to create dashboard in tableau with example (With the help of an example create one in tableau)

To create a dashboard in Tableau, follow these steps:

Step 1: Connect to Data
- Launch Tableau and connect to the desired data source (e.g., Excel, CSV, database).
- Select the tables or data sources you want to use in your dashboard.

Step 2: Build Worksheets
- Create individual worksheets by dragging and dropping fields from the data pane onto the canvas.
- Apply appropriate visualizations (e.g., bar chart, line chart, map) to represent the data in each worksheet.
- Customize the formatting, labels, colors, and other visual properties as needed.

Step 3: Arrange Worksheets on the Dashboard
- Go to the Dashboard tab by clicking on the "New Dashboard" button.
- Drag and drop the worksheets you created onto the dashboard canvas.
- Resize and rearrange the worksheets to achieve the desired layout.
- Use containers, horizontal/vertical layouts, and text boxes to organize and annotate the content.

Step 4: Add Interactivity and Filters
- Enhance the user experience by adding interactive elements such as filters, parameters, and actions.
- Use filters to allow users to dynamically explore and analyze the data.
- Configure actions to enable users to navigate between different worksheets or dashboards based on selections.

Step 5: Format and Customize the Dashboard
- Apply formatting options to the dashboard to make it visually appealing and intuitive.
- Adjust the size, alignment, and spacing of the components.
- Add titles, captions, and legends to provide context and explanations.
- Choose appropriate fonts, colors, and backgrounds to match your design preferences.

Step 6: Test and Publish
- Preview the dashboard to ensure all elements are displaying correctly and functioning as intended.
- Test the interactivity and filters to verify the expected behavior.
- Save the dashboard and publish it to Tableau Server, Tableau Public, or other platforms for sharing with others.


## 6. Explain in detail the heat maps and scatter plot and how to create them with example (With the help of an example create one in tableau)

### Heat Map: 
Heatmap is defined as a graphical representation of data using colors to visualize the value of the matrix. In this to represent more common values
or higher activities brighter colors basically reddish colors are used and to less common or activity values darker colors are preferred. Heatmap is also defined by
the name of the shading matrix.
To create an Heat map steps are:
		1. connect the data.
		2. add measure and dimension on which you want to plot a graph.
		3. click on show me.
		4. click on the heat map.

### Scatter plot :
As the name suggests, a scatter plot shows many points scattered in the Cartesian plane. It is created by plotting values of numerical variables as X and Y coordinates
in the Cartesian plane. Tableau takes at least one measure in the Rows shelf and one measure in the Columns shelf to create a scatter plot. However, we can add 
dimension fields to the scatter plot which play a role in marking different colors for the already existing points in the scatter graph scatter plot is generally used to see the parameter which are overlapping each other.
To create an Scatter plot : 
		1. connect data with the tableau.
		2. add measure and dimension in the rows and column where you want to perform a task.
		3. click on show me and then click on the scatter plot.
    
    
## 7. How to create table calculations in tableau with examples . (With the help of an example create one in tableau)

Define the Table Calculation

- Select the measure you want to perform the table calculation on.
- Right-click on the measure and navigate to "Quick Table Calculation."
- Choose the appropriate table calculation function based on your analysis requirements. 
- Tableau provides various functions such as SUM, AVG, MIN, MAX, RANK, RUNNING_SUM, etc.
- After selecting the table calculation function, specify the "Compute Using" options. 
- These options define how the calculation should be performed, such as by dimensions, specific fields, or addressing partitions.
- Right-click on the measure and navigate to "Compute Using" to select the desired options.



## Q8: Explain in detail the distribution bands in tableau and how to create them with example.


In Tableau, distribution bands are used to group a continuous variable into discrete segments, or bins. 
This is particularly useful when dealing with large datasets that may have a wide range of values. By creating distribution bands, you can visualize data more easily 
and identify patterns and trends.
	To create distribution bands in Tableau, follow steps:
		1.Drag the continuous variable you want to bin onto the Rows or Columns shelf.
		2.go into the analytical section which is present on the left side upper corner.
		3.From the custom section click on the Distribution band.
		4.Custom the feild as per your requirement.



## Q9: Explain the steps to create bar chart and pie diagram in tableau with example.

Creating a Bar Chart in Tableau:
		1. Open Tableau and connect to your data source
		2. Drag the dimension you want to measure to the Columns shelf
		3. Drag the measure you want to chart to the Rows shelf
		4. Tableau will automatically create a bar chart. You can customize the chart by adding labels, colors, and formatting options from the Marks card.


Creating a Pie Chart in Tableau:
		1. Open Tableau and connect to your data source
		2. Drag the dimension you want to measure to the "Angle" field in the Marks card
		3. Drag the measure you want to chart to the "Size" field in the Marks card
		4. Tableau will automatically create a pie chart.(If not created then click on show me and then click on pie chart.) 
			You can customize the chart by adding labels, colors, and formatting options from the Marks card.




## Q10: How to add story points on the dashboard.

To add story points on the dashboard in Tableau, you need to first create a story by clicking on the "New Story" button on the toolbar.
Once you have created your story, you can add story points by clicking on the "Add" button below the story point canvas. 
You can then drag and drop sheets or dashboards onto the story 	point canvas and arrange them in the order you want them to appear.
You can also add text, images, and web pages to your story points. Once you have finished creating your story points, you can preview your story by clicking on the "Preview" button on the toolbar.

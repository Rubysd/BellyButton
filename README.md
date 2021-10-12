# BellyButton

# Plotly (Belly Button Biodiversity Dashboard)

## Overview of Project

Roza has a partially completed dashboard that she needs to finish. She has a completed panel for demographic information and now needs to visualize the bacterial data for each volunteer. Specifically, her volunteers should be able to identify the top 10 bacterial species in their belly buttons. That way, if Improbable Beef identifies a species as a candidate to manufacture synthetic beef, Roza's volunteers will be able to identify whether that species is found in their navel.

#### Deliverable 1: Create a Horizontal Bar Chart
#### Deliverable 2: Create a Bubble Chart
#### Deliverable 3: Create a Gauge Chart
#### Deliverable 4: Customize the Dashboard
#### Deliverable 5: A written report on the Belly Button Biodiversity Dashboard analysis README.md

# Deliverable 1:

Create a Horizontal Bar Chart
Deliverable Requirements:
Using your knowledge of JavaScript, Plotly, and D3.js, create a horizontal bar chart to display the top 10 bacterial species (OTUs) when an individual’s ID is selected from the dropdown menu on the webpage. The horizontal bar chart will display the sample_values as the values, the otu_ids as the labels, and the otu_labels as the hover text for the bars on the chart.

Your bar chart should look like the following image:
![image](https://user-images.githubusercontent.com/86340630/136833333-84f67156-90a0-407d-b8ed-8ef74f615a33.png)

Code is written to create the arrays when a sample is selected from the dropdown menu.
Code is written to create the trace object in the buildCharts() function, and it contains the following:
The y values are the otu_ids in descending order.
The x values are the sample_values in descending order
The hover text is the otu_labels in descending order.
Code is written to create the layout array in the buildCharts() function that creates a title for the chart.
When the dashboard is first opened in a browser, ID 940’s data should be displayed in the dashboard, and the bar chart has the following:
The top 10 sample_values are sorted in descending order
The top 10 sample_values as values
The otu_ids as the labels

# Results with detail analysis:

Code is written to create the arrays when a sample is selected from the dropdown menu.

![Captura de pantalla (841)](https://user-images.githubusercontent.com/86340630/136853884-34721d60-a340-4dc8-9bf5-bd5473ef7ab3.png)

Code is written to create the trace object in the buildCharts() function, and it contains the following:
The y values are the otu_ids in descending order.
The x values are the sample_values in descending order
The hover text is the otu_labels in descending order.

![Captura de pantalla (839)](https://user-images.githubusercontent.com/86340630/136854101-6aeb5c0f-0ea6-47d7-85b7-6660b319560d.png)

Code is written to create the layout array in the buildCharts() function that creates a title for the chart.

![Captura de pantalla (843)](https://user-images.githubusercontent.com/86340630/136854307-5a3f9653-66bd-49d1-b7bb-ab9739c52b2f.png)

When the dashboard is first opened in a browser, ID 940’s data should be displayed in the dashboard, and the bar chart has the following:
The top 10 sample_values are sorted in descending order
The top 10 sample_values as values
The otu_ids as the labels

![Captura de pantalla (846)](https://user-images.githubusercontent.com/86340630/136854757-c48150a2-a5df-43df-a93d-87791b498d6a.png)
![Captura de pantalla (847)](https://user-images.githubusercontent.com/86340630/136854821-b6b7bd2e-296e-4ff7-a077-079012179e30.png)
![image](https://user-images.githubusercontent.com/86340630/136854848-74924650-50d9-4984-bcb5-1bda885917c9.png)

# Deliverable 2:

Create a Bubble Chart
Deliverable Requirements:
Using your knowledge of JavaScript, Plotly, and D3.js, create a bubble chart that will display the following when an individual’s ID is selected from the dropdown menu webpage:

The otu_ids as the x-axis values.
The sample_values as the y-axis values.
The sample_values as the marker size.
The otu_ids as the marker colors.
The otu_labels as the hover-text values.
Your bubble chart should look like the following image:

![image](https://user-images.githubusercontent.com/86340630/136854998-dac86c6e-0bbb-467d-bfbd-ea8d2e0463a8.png)

1. The code for the trace object in the buildCharts(); function does the following:
  ° Sets the otu_ids as the x-axis values
  ° Sets the sample_values as the y-axis values
  ° Sets the otu_labels as the hover-text values
  ° Sets the sample_values as the marker size
  ° Sets the otu_ids as the marker colors
2. The code for the layout in the buildCharts(); function does the following:
  ° Creates a title
  ° Creates a label for the x-axis
  ° The text for a bubble is shown when hovered over
3. When the dashboard is first opened in a browser, ID 940’s data should be displayed in the dashboard. All three charts should also be working according to their requirements when a sample is selected from the dropdown menu

## Results with detail analysis:

1. The code for the trace object in the buildCharts(); function does the following:
° Sets the otu_ids as the x-axis values
° Sets the sample_values as the y-axis values
° Sets the otu_labels as the hover-text values
° Sets the sample_values as the marker size
° Sets the otu_ids as the marker colors

![Captura de pantalla (849)](https://user-images.githubusercontent.com/86340630/136855400-7a87ce19-dea4-4964-9018-1d48253dca7d.png)

The code for the layout in the buildCharts(); function does the following:
° Creates a title
° Creates a label for the x-axis
° The text for a bubble is shown when hovered over.

![Captura de pantalla (851)](https://user-images.githubusercontent.com/86340630/136855544-2bb311f1-9f1e-4d72-9b03-bc156f4fe31c.png)

When the dashboard is first opened in a browser, ID 940’s data should be displayed in the dashboard. All three charts should also be working according to their requirements when a sample is selected from the dropdown menu.

![image](https://user-images.githubusercontent.com/86340630/136855597-4d6dd19a-a0a8-4520-b442-594fda1ccd4c.png)

# Deliverable 3:

## Create a Gauge Chart

### Deliverable Requirements:
Using your knowledge of JavaScript, Plotly, and D3.js, create a gauge chart that displays the weekly washing frequency's value, and display the value as a measure from 0-10 on the progress bar in the gauge chart when an individual ID is selected from the dropdown menu.

Your gauge chart should look similar to the following image:

![image](https://user-images.githubusercontent.com/86340630/136855716-501bdd1e-6609-4b3d-b7b8-912f719b84b9.png)

1. The code to build the gauge chart does the following:

° Creates a title for the chart.
° Creates the ranges for the gauge in increments of two, with a different color for each increment.
° Adds the washing frequency value on the gauge chart.
° The indicator shows the level for the washing frequency on the gauge.
° The gauge is added to the dashboard.
° The gauge fits in the margin of the <div> element.

2. When the webpage loads, the bar and bubble chart are working according to the requirements in Deliverable 1 and 2, respectively, and the gauge chart is working according to the requirements listed for this Deliverable

## Results with detail analysis:

1. The code to build the gauge chart does the following:

° Creates a title for the chart.
° Creates the ranges for the gauge in increments of two, with a different color for each increment.
° Adds the washing frequency value on the gauge chart.
° The indicator shows the level for the washing frequency on the gauge.
° The gauge is added to the dashboard.
° The gauge fits in the margin of the <div> element.

![Captura de pantalla (853)](https://user-images.githubusercontent.com/86340630/136856128-1d7eea60-0c62-4ffb-9ccc-2632ca5f395b.png)
![Captura de pantalla (855)](https://user-images.githubusercontent.com/86340630/136856460-dc410b48-ce43-463d-8612-01623295a904.png)
  
When the webpage loads, the bar and bubble chart are working according to the requirements in Deliverable 1 and 2, respectively, and the gauge chart is working according to the requirements listed for this Deliverable
  
![Captura de pantalla (855)](https://user-images.githubusercontent.com/86340630/136880155-061a8e6b-0a76-4edd-bf50-d1e8693808b3.png)
![Captura de pantalla (858)](https://user-images.githubusercontent.com/86340630/136880222-72f41941-191a-4c78-9ec2-bfd92a8673ea.png)
![image](https://user-images.githubusercontent.com/86340630/136880521-e990d305-7f65-4b68-8cd3-e6deb5a98c11.png)

# Deliverable 4:
## Customize the Dashboard

Deliverable Requirements:

Use your knowledge of HTML and Bootstrap to customize the webpage for your dashboard.


1. Customize your dashboard with three of the following:
° Add an image to the jumbotron.
° Add background color or a variety of compatible colors to the webpage.
° Use a custom font with contrast for the colors.
° Add more information about the project as a paragraph on the page.
° Add information about what each graph visualizes, either under or next to each graph.
° Make the webpage mobile-responsive.
° Change the layout of the page.
° Add a navigation bar that allows you to select the bar or bubble chart on the page.

2. When the dashboard is first opened in a browser, ID 940’s data should be displayed in the dashboard, and the three charts should be working according to their requirements.
3. When a sample is selected, the dashboard should display the data in the panel and all three charts according to their requirements.

## Results with detail analysis:

1. Customize your dashboard with three of the following:
° Add an image to the jumbotron.
° Add background color or a variety of compatible colors to the webpage.
° Use a custom font with contrast for the colors.
° Add more information about the project as a paragraph on the page.
° Add information about what each graph visualizes, either under or next to each graph.
° Make the webpage mobile-responsive.
° Change the layout of the page.
° Add a navigation bar that allows you to select the bar or bubble chart on the page.
 
![image](https://user-images.githubusercontent.com/86340630/136981745-9225af90-045b-4f89-8bd7-372a9a091540.png)
![Captura de pantalla (867)](https://user-images.githubusercontent.com/86340630/136981068-aa36e6c8-106e-4bd7-9a7f-a1560cdfe242.png)
!![image](https://user-images.githubusercontent.com/86340630/136979903-ed7fe14e-7387-46ef-8d19-c0ddb3737d84.png)



  
  
  
  
  
  




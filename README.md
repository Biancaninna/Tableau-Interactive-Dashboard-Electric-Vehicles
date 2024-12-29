# Electric Vehicles Data Analysis Dashboard
In this project, we will build dynamic and interactive Tableau dashboard to analyze the population of electric vehicles in the United States. The dashboard will be visualized using Tableau Public software, where we will use its tools which are very popular and currently in great demand by the market. Tableau was chosen because it is able to process many data sources and is integrated with scripting languages. The use of Tableau in making Dashboards has several advantages in business including making it easier to view and compare information, get relevant business data and simplify decision making. Data Source in this project is obtained from Kaggle

### To see the final result of dashboard visualization using Tableau Public, visit:

[![N|Solid](https://img.shields.io/badge/Tableau-E97627.svg?style=for-the-badge&logo=Tableau&logoColor=white)](https://biancaninna.github.io/Tableau-Interactive-Dashboard-Electric-Vehicles/)

### Tableau dasboard final looks

![image alt](https://github.com/Biancaninna/Tableau-Interactive-Dashboard-Electric-Vehicles/blob/5e29ff6a94c6a2d5be86675fc0a7139d369b0a27/Tableau%20Interactive%20Dashboard.png) 

## Business Requirement
Client wants to create an electric car population dashboard, so that they can have insight on the below requirements
### KPI's Requirements
1. Total Vehicles

   Understand the overall landscape of electric vehicles, encompassing both BEV's and PHEV's to assess the market's size and growth.
   
3. Average Electric Range

   Determine the average electric range of the electric vehicles in the dataset to measure the technological advancements and efficiency of the EV's.
   
3. Total BEV Vehicles and % of Total BEV Vehicles
   
    - Identify and analyze the total number of Battery Electric Vehicles (BEV's) in dataset.
    - Calculate the percentage of BEV's relative to the total number of electric vehicles, providing insights into the dominance of fully electric electric models.
      
4. Total PHEV Vehicles and % of Total PHEV Vehicles
    
    - Identify and analyze the total number of Plug-in Hybrid Electric Vehicles (PHEV's) in the dataset.
    - Calculate the percentage of PHEV's relative to the total number of electric vehicles, offering insights into the market share of plug-in hybrid models.

### Chart's Requirements
1. Total Vehicles by Model Year (From 2010 Onwards)
    - Visualization: Line/ Area Chart
    - Description: This chart will illustrate the distribution of electric vehicles over the years, starting from 2010 and providing insights into the growth pattern and adoption trends.
2. Total Vehicles by State
    - Visualization: Map Chart
    - Description: this chart will showcase the geographical distribution of electric vehicles across different state, allowing us to identify the region with higher adoption rates.
3. Top 5 total vehicles by Manufacturer
    - Visualization: Bar Chart
    - Description: Highlight the top 5 electric vehicles manufacturers based on the total number of vehicles, providing insights into the market dominance of specific brands.
4. Total Vehicles by CAFV Eligibility
    - Visualization: Pie Chart or Donut Chart
    - Description: illustrate the proportion of electric vehicles that are eligible for Clean Alternative Fuel Vehicle (CAFV) incentives, aiding in understanding the impact of incentives on vehicle adoption.
5. Total Vehicles by Model
    - Visualization: Grid View
    - Description: highlight the top 5 electric vehicle models based on the total number of vehicles, offering insights into customer preferences and popular models in the market.

### Software Used
1. MS EXCEL
2. Tableau Public

### Explanation of steps
1. Connect Tableau with data from MS Excel, the data in this project is csv file type so we select the text file connection and the data source page will be opened.

2. We need to check carefully each column and row whether everything looks good in data source page. We can do some data cleaning here as well. Then we can start building our report just click on Sheet 1.

4. Building Report

   We will design all our sheets and at the end we will design our dashboard. So first we have to rename the sheet according to the required KPIs.
    >Total Vehicles

     Write a calculation field to find out our Total Vehicles, then rename it as Total Vehicles and write the calculation

     ![image alt](https://github.com/Biancaninna/Tableau-Documentation-Electric-Vehicles/blob/master/5.%20Calculation%201.png?raw=true)

     Take the Total Vehicles from Table and add it into Text on Marks Tab

     ![image alt](https://github.com/Biancaninna/Tableau-Documentation-Electric-Vehicles/blob/master/6.%20Calculation%202.png?raw=true)

     do some quick formatting

     ![image alt](https://github.com/Biancaninna/Tableau-Documentation-Electric-Vehicles/blob/master/7.%20Calculation%203%20quick%20formatting.png?raw=true)

     Then click on apply and OK
   
    > Average Electric Range
    
      Just duplicate the Total Vehicles sheet, rename the sheet as Average Electric Range.
   
      ![image alt](https://github.com/Biancaninna/Tableau-Documentation-Electric-Vehicles/blob/master/8.%20Average%20Electric%20Range%20by%20duplicate%20sheet.png?raw=true)

      Create Calculated Field, name it as Avg Electric Range. Then add to Text to replace Total Vehicles 

      ![image alt](https://github.com/Biancaninna/Tableau-Documentation-Electric-Vehicles/blob/master/9.%20Calculation%20Avg%20Electric%20Range.png?raw=true)

      Go in Text and do some formatting. Click Apply and OK

      ![image alt](https://github.com/Biancaninna/Tableau-Documentation-Electric-Vehicles/blob/master/12.%20Add%20filter%20model%20year.png?raw=true)
      
_Because what we want to use in this project is data from 2011 onwards, we have to filter the year range_

   - Right click on data source, select Edit Data Source Filters, then click Add and choose Model Year. Change the year range from 2011 to 2024
      
      
      ![image alt](https://github.com/Biancaninna/Tableau-Documentation-Electric-Vehicles/blob/master/11.%20Year%20filter.png?raw=true)

      ![image alt](https://github.com/Biancaninna/Tableau-Documentation-Electric-Vehicles/blob/master/12.%20Add%20filter%20model%20year.png?raw=true)

      ![image alt](https://github.com/Biancaninna/Tableau-Documentation-Electric-Vehicles/blob/master/13.%20Add%20filter%20model%20year%202.png?raw=true)

      ![image alt](https://github.com/Biancaninna/Tableau-Documentation-Electric-Vehicles/blob/master/14.%20Last%20edit%20data%20source%20filter.png?raw=true)
     
    
  > Total BEV Vehicles and % of Total BEV Vehicles

  ##### _Total BEV Vehicles_
    
  Do the same as in the previous step. The calculation is as follows
  
  ![image alt](https://github.com/Biancaninna/Tableau-Documentation-Electric-Vehicles/blob/master/15.%20Calculation%20Total%20BEV%20Vehicles.png?raw=true)
    
  Drag it to Text and do some formatting
    
  ##### _% of Total BEV Vehicles_
    
  Add Create Calculated Field, take it and add it into TEXT. 
    
  ![image alt](https://github.com/Biancaninna/Tableau-Documentation-Electric-Vehicles/blob/master/16.%20Calculation%20%25%20of%20Total%20BEV%20Vehicles.png?raw=true)    
  
  ![image alt](https://github.com/Biancaninna/Tableau-Documentation-Electric-Vehicles/blob/master/17.%20Calculation%20%25%20of%20Total%20BEV%20Vehicles%202.png?raw=true) 
  
  Right click on the % of Total BEV Vehicles field and select Format. Click on Numbers and click on Percentage then you can do some formatting
  
  ![image alt](https://github.com/Biancaninna/Tableau-Documentation-Electric-Vehicles/blob/master/19.%20Calculation%20%25%20of%20Total%20BEV%20Vehicles%204.png?raw=true) 
    
  > Total PHEV Vehicles and % of Total PHEV Vehicles
    
  ##### _Total PHEV Vehicles_
  
  Just duplicate the Total BEV Vehicles sheet, do some formatting including adding a new Calcualted field and the rest is just repeating the previous steps.
  
  ![image alt](https://github.com/Biancaninna/Tableau-Documentation-Electric-Vehicles/blob/master/20.%20Calculation%20Total%20PHEV%20Vehicles.png?raw=true) 
    
  ##### _% of Total PHEV Vehicles_
  
  Just add Create Calculated Field 
  
  ![image alt](https://github.com/Biancaninna/Tableau-Documentation-Electric-Vehicles/blob/master/21.%20Calculation%20%25%20of%20Total%20PHEV%20Vehicles.png?raw=true) 
  
  the next step is the same as when building % of total BEV Vehicles
  
  > Total Vehicles by Model Year
     
  Add New Worksheet and name it as Total Vehicles by Model Year. We will visualize it by combining Area Chart and Line Chart because we will use dual axis chart. Take Model Year and add it into Columns, take Total Vehicles and add it into Rows
  
  ![image alt](https://github.com/Biancaninna/Tableau-Documentation-Electric-Vehicles/blob/master/22.%20Total%20Vehicles%20by%20Model%20Year%201.png?raw=true) 
  
  Right click on Model Year, select Edit Axis and custom fixed start from 2011
  
  ![image alt](https://github.com/Biancaninna/Tableau-Documentation-Electric-Vehicles/blob/master/23.%20Total%20Vehicles%20by%20Model%20Year%202.png?raw=true) 
  
  To visualize the exact year, Right click on Model Year and select Discrete and make it into Line. Because continous axis always dependent on each other, meanwhile Discrete means that they have their own bucket or it is independent from the other values
  
  ![image alt](https://github.com/Biancaninna/Tableau-Documentation-Electric-Vehicles/blob/master/24.%20Total%20Vehicles%20by%20Model%20Year%203.png?raw=true) 
  
  Convert into Area Chart and do some formatting. Then duplicate the Chart, just press Ctrl on keyboard and drag Total Vehicles in Rows to the side. Then one more chart has been created. So two particular marks have been created. Next do some formatting
  
  ![image alt](https://github.com/Biancaninna/Tableau-Documentation-Electric-Vehicles/blob/master/25.%20Total%20Vehicles%20by%20Model%20Year%205.png?raw=true) 
  
  Change the second marks into Line and right click on Total Vehicles that is in Rows and select Dual Axis
  
  ![image alt](https://github.com/Biancaninna/Tableau-Documentation-Electric-Vehicles/blob/master/26.%20Total%20Vehicles%20by%20Model%20Year%206.png?raw=true) 
  
  It means that they have been merged on each other. After that synchronize the axis and you can do some formatting
  
  ![image alt](https://github.com/Biancaninna/Tableau-Documentation-Electric-Vehicles/blob/master/27.%20Total%20Vehicles%20by%20Model%20Year%207.png?raw=true) 
  
  Add Labels and do some formatting, then convert into thousands
  
  ![image alt](https://github.com/Biancaninna/Tableau-Documentation-Electric-Vehicles/blob/master/29.%20Total%20Vehicles%20by%20Model%20Year%209.png?raw=true)
  
  ![image alt](https://github.com/Biancaninna/Tableau-Documentation-Electric-Vehicles/blob/master/30.%20Total%20Vehicles%20by%20Model%20Year%2010.png?raw=true)
  
  Add an average line. Go to Analytics, select Average Line and drag it into Table Reference Line and do some formatting
  
  ![image alt](https://github.com/Biancaninna/Tableau-Documentation-Electric-Vehicles/blob/master/31.%20Total%20Vehicles%20by%20Model%20Year%2011.png?raw=true) 
  
  > Total Vehicles by State
    
  Whenever we have to draw some geographical, we have to use the Latitude and Longitude. Drag Latitude into Rows and Longitude into Columns. Drag State into Detail
    
  ![image alt](https://github.com/Biancaninna/Tableau-Documentation-Electric-Vehicles/blob/master/32.%20Total%20Vehicles%20by%20State.png?raw=true) 
  
  ![image alt](https://github.com/Biancaninna/Tableau-Documentation-Electric-Vehicles/blob/master/33.%20Total%20Vehicles%20by%20State%201.png?raw=true) 

  for unknown locations, double click on it and edit location and format it into Shape Map
  
  ![image alt](https://github.com/Biancaninna/Tableau-Documentation-Electric-Vehicles/blob/master/34.%20Total%20Vehicles%20by%20State%202.png?raw=true) 
  
  Show different values on the map, just take Total Vehicles into Color. Then do some formatting. Give the number over the Map, drag Total Vehicles and add it into Label and do some formatting
  
  ![image alt](https://github.com/Biancaninna/Tableau-Documentation-Electric-Vehicles/blob/master/35.%20Total%20Vehicles%20by%20State%204.png?raw=true) 
  
  To give a different color to each state, then drag the state in the first Marks to Color and you can do some formatting.
  
  >Top 5 Total Vehicles by Manufacturer
    
  Create a New Sheet, take Manufacturer and add it into Rows, Take Total Vehicles and add it into Columns and sort in descending order
  
  ![image alt](https://github.com/Biancaninna/Tableau-Documentation-Electric-Vehicles/blob/master/36.%20Top%205%20By%20Manufacturers.png?raw=true) 
  
  Do some filtering, drag Manufacturer into Filters Tab. We have to use Top Condition by Field.
  
  ![image alt](https://github.com/Biancaninna/Tableau-Documentation-Electric-Vehicles/blob/master/37.%20Top%205%20By%20Manufacturers%201.png?raw=true) 
  
  In this project, we will visualize the "top n" manufacturers dynamically, so we need to create the parameters.
  
  ![image alt](https://github.com/Biancaninna/Tableau-Documentation-Electric-Vehicles/blob/master/38.%20Top%205%20By%20Manufacturers%202.png?raw=true) 
  
  Next create a Label, just drag Total Vehicles into Label and do some filtering.
  
  Visualize the total vehicles in percentage form
  
  ![image alt](https://github.com/Biancaninna/Tableau-Documentation-Electric-Vehicles/blob/master/39.%20Top%205%20By%20Manufacturers%203.png?raw=true) 
  
  If you want to visualize the original total value as well, just drag Total Vehicles into Label as well. Then right click on Parameter and select Show Parameter and do some formatting.
    
  Create a dynamic title, just double click on title and do formatting.
  
  Create Parameters for State and Electric Vehicle Type as well as for CAFV Eligibility, just drag State into Filters, right click on it and select Show Filter. Do the same steps to create the other two parameters.
  
  If you are using Top n filter, then you should add it into context, so whichever filters we are using should be used under context filter. It means that it is passing all the other filters through that particular context and then it is showing up the results
  
  ![image alt](https://github.com/Biancaninna/Tableau-Documentation-Electric-Vehicles/blob/master/40.%20Top%205%20By%20Manufacturers%206.png?raw=true) 
  
  fyi: Manufacturer is not added to the context because it is already used in the first top n.
    
  >Total Vehicles by CAFV Eligibility
    
  Drag Clean Alternative Fuel Vehicle Eligibility into Rows and replace the Marks into Pie. That way three pie charts are created. We just need one Pie Chart, so take Clean Alternative Fuel Vehicle Eligibility in Rows and drag into color. Now there is only one Pie Chart.
  Add an angle, drag Total Vehicles and add it into Angle. Convert into a Donut Chart. Then double click in that particular Rows and write the calculation, and then enter then one axis will be created on our Pie Chart
  
  ![image alt](https://github.com/Biancaninna/Tableau-Documentation-Electric-Vehicles/blob/master/41.%20CAFV%201.png?raw=true) 
  
  Duplicate Calculation Rows like before, just press Ctrl on keyboar and drag it into sideways and two Marks will be created
  
  i![image alt](https://github.com/Biancaninna/Tableau-Documentation-Electric-Vehicles/blob/master/42.%20CAFV%202.png?raw=true) 
  
  Go to second Marks chart and remove everyting. Right click on second Rows and select Dual Axis, then these two will merged on each other. Go to first Marks, click on Size and increase the size. Go to second Marks and dothe same. Afer that you can do some formatting.
  Drag Total Vehicles and add into Label in the First Marks chart and do some formatting.
  
  ![image alt](https://github.com/Biancaninna/Tableau-Documentation-Electric-Vehicles/blob/master/43.%20CAFV%203.png?raw=true) 
  
  Convert CAFV Eligibility into Alias format
  
  ![image alt](https://github.com/Biancaninna/Tableau-Documentation-Electric-Vehicles/blob/master/44.%20CAFV%205.png?raw=true) 
  
  After that do some formatting
    
  > Total Vehicles by Model
    
  Drag Model, Manufacturer, and Electric Vehicle Type into Rows
  
  ![image alt](https://github.com/Biancaninna/Tableau-Documentation-Electric-Vehicles/blob/master/46.%20Total%20Vehicles%20by%20Model%201.png?raw=true) 
  
  Take Total Vehicles and add it into Text and convert it into percentage format using Quick Table Calculation like before.
  To visualize the original Total Value, just double-click on Total Vehicles from Table and it will automatically display both in percent and original.
  
  ![image alt](https://github.com/Biancaninna/Tableau-Documentation-Electric-Vehicles/blob/master/47.%20Total%20Vehicles%20by%20Model%202.png?raw=true) 
  
  Then you can do some formatting, change the color just drag Total Vehicles into Color then change it into Shape. Then you can change the color as you want
    
##### _Now we have designed all of our charts and now we just need to visualize the Electric Vehicles dashboard_
Just do drag and drop to build Tableau Dashboards.


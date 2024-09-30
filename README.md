# US States Population and GDP Dashboard

## Overview
This Power BI dashboard presents a comprehensive visualization of the population and GDP data for US states, enabling dynamic exploration and analysis. The dashboard allows users to view state-level data across census regions, explore population growth trends over time, and analyze growth rates between customizable time periods.

## Dashboard Features

### 1. Dashboard
**Shape Map Visualization**
   - Displays all US states, categorized by **Census Region**.
   - Clicking on a state highlights the state in all other charts and tables, reflecting relevant data.

**Bar Chart: States by Census Region**
   - Shows the breakdown of states per **Census Region** and **Division**.

**Population Table (2015)**
   - A table displaying the **2015 population** figures categorized by **Census Region**, **Division**, and **State**.

<img width="1330" alt="Dashboard" src="https://github.com/user-attachments/assets/a9b78536-4ad4-430a-b06e-adb55716087d">

### 2. **Ribbon Chart: Population Growth (1950 onwards)**
   - Visualizes the population growth trends for each state from **1950 to the present**.
   - Ranks the states dynamically based on population changes over time.

<img width="647" alt="PopulationGrowth" src="https://github.com/user-attachments/assets/9f304b19-4e75-43ce-867b-b1952627336d">

### 3. **State Selection Synchronization**
   - Charts, maps, and tables are interlinked. Selecting a state on the **Shape Map** updates the data across all visualizations.

<img width="1331" alt="Dashboard1" src="https://github.com/user-attachments/assets/53cbc8b7-19eb-498c-8572-892a4f0e406b">

### 4. **Census Region and Division Filter**
   - A **filter/slicer** enables users to filter data by **Census Region** and **Division**, automatically reflecting the selection in all visuals.

<img width="1325" alt="Filter" src="https://github.com/user-attachments/assets/6f5c2334-c71f-4f0b-921b-7d1a5783eaad">

### 5. **State Population Growth Tooltip**
   - Hovering over any state in the **Shape Map** triggers a tooltip with a **line chart**, showing population growth through the years for that particular state.

<img width="610" alt="Tooltip" src="https://github.com/user-attachments/assets/1c0db3e1-835c-46e4-823b-14b507745a2b">

### 6. **Customizable Population Growth Report**
   - A report with a **slicer** allows users to select a **starting** and **ending year**, generating a table that displays the **population growth rate** between those years.

<img width="1145" alt="PopulationGrowthRate" src="https://github.com/user-attachments/assets/6dbe24f1-3421-411c-9af5-b1f4cef60c5a">

## How to Use
1. **Interactive State Selection**: Click on any state in the Shape Map to view its specific data reflected across all charts.
2. **Region and Division Filter**: Use the filter to select specific **Census Regions** or **Divisions**.
3. **Population Growth Exploration**: Hover over the states to see the population growth line chart for that state.
4. **Year Range Report**: Use the slicer in the report to customize the **start** and **end year**, and view the calculated population growth rate.

# Global Population and GDP Dashboard

## Overview
This Power BI dashboard provides insights into global population and GDP data, with an interactive feature allowing users to drill through and explore detailed information for individual countries. The dashboard visualizes population density, GDP per capita, and annual growth trends for multiple regions and countries.

## Dashboard Features

### 1. Dashboard
**Map Visualization: Countries by Region**
   - A world map using **iso2Code** to display countries, color-coded by **region**.
   - Regions include: 
     - East Asia & Pacific
     - Europe & Central Asia
     - Latin America & the Caribbean
     - Middle East & North Africa
     - North America
     - South Asia
     - Sub-Saharan Africa
   - Clicking on a country highlights it across all other charts and tables.

**Country Population and GDP Table**
   - A table displaying:
     - **2020 Population**
     - **2020 GDP**
     - **2020 Population Density**
     - **GDP Per Capita**
     - Option to view GDP by year via line chart.

<img width="915" alt="Dashboard" src="https://github.com/user-attachments/assets/ffc3b492-a738-47ac-bf5a-bebfaac70fb0">

### 3. **Drill Through: Country Details**
   - Users can right-click on a country from the overview and **drill through** to see detailed data specific to that country.
   - **Country-specific page** displays:
     - **GDP Annual Growth %**: Shows the year-on-year GDP growth.
     - **GDP Per Capita** and **Population**: For each year.
     - A combination chart with **Bar Chart**: GDP annual growth percentages, **Line Chart**: GDP over time for the selected country.

<img width="1329" alt="DrillThroughCountry" src="https://github.com/user-attachments/assets/c72a548b-03a3-4c87-9fab-0ed87c205d92">

### 4. **Interactive Country Selection**
   - All visual elements are interconnected. Selecting a country on the world map or in the table updates the data across the visuals to reflect details of the selected country.

<img width="926" alt="Selection" src="https://github.com/user-attachments/assets/aba4e92f-4a06-4f0c-907e-232933a8ebeb">

### 5. **Filter Panel**
   - Side filter panel allows filtering by region, making it easier to explore a specific area of interest.

## How to Use
1. **Drill Through to Country Details**: Right-click on any country from the overview map or table to drill through to a detailed report for that country.
2. **Explore Regional Data**: Filter by region using the filter pane to explore population and GDP data for specific parts of the world.
3. **Interactive Visualization**: Click on any country in the map or table, and the related visuals will update to display more specific data.


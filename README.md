# Regional Sales Analysis with Tableau

This project focuses on descriptive analytics, analyzing sales and profitability data for a large retail chain. The data used is the Sample - Superstore dataset provided by Tableau, which includes four years of sales data for various products across different regions. It contains detailed information on sales, profit, order dates, categories, sub-categories, and geographic details such as country, state, and city.

# Project Workflow

Step 1: Connecting to My Data I begin by launching Tableau Desktop. On the Start page, I select the connector for "Sample - Superstore" under Saved Data Sources to connect to the sample dataset.

Step 2: Creating a Basic View To start building a foundational view, I drag "Order Date" from the Data pane to the Columns shelf. Then, I drag "Sales" to the Rows shelf, generating a line chart that displays total aggregated sales for each year. To further break down the sales data, I drag "Category" and "Subcategory" to the Rows shelf.

Step 3: Focusing My Results To narrow down my analysis, I add filters by right-clicking on "Order Date" and "Sub-Category" in the Data pane and selecting "Show Filter." I then drag "Profit" to Color on the Marks card to visualize profitability. By filtering for specific sub-categories like Bookcases, Machines, and Tables, I can identify unprofitable products.

Step 4: Exploring Geographical Data Next, I delve into geographical insights by creating a new worksheet. I double-click "State" to add it to Detail on the Marks card, resulting in a map view. I filter this map view to focus on the South region. By dragging "Sales" to Color on the Marks card and adjusting the colors using the Red-Green Diverging palette, I can better visualize the data. Additionally, I drag "Profit" to Color on the Marks card to see profitability by state.

Step 5: Drilling Down into Details For a more detailed analysis, I create a bar chart by duplicating the Profit Map worksheet. I filter this view to focus on states with negative profit, such as Tennessee, North Carolina, and Florida. Applying a Top N Filter allows me to display the bottom 5 performers by city. To ensure accurate data representation, I add context to these filters.

Step 6: Building a Dashboard To create a comprehensive dashboard, I drag the "Sales in the South" and "Profit Map" worksheets onto a new dashboard. I clean up the view by hiding unnecessary headers and filter cards. By enabling interactivity, I use the Profit Map as a filter for the bar chart.

Step 7: Building a Story Finally, I present my findings by creating a new story. I start by adding the "Sales in the South" worksheet to the story. To highlight machine sales, I filter the Sub-Category. Using the Regional Sales and Profit dashboard, I showcase underperforming items in the South. I focus specifically on North Carolina by selecting it on the map and presenting detailed profit information.



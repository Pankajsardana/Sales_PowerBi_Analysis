# Sales_PowerBi_Analysis
Step 1: Connect to OData Source
**Open Power BI Desktop.**
Get Data: Click on the "Home" tab and then click "Get Data".
Select OData Feed: In the "Get Data" window, select "OData Feed" and click "Connect".
Enter OData URL: In the OData Feed dialog box, enter the URL of the OData service you want to connect to and click "OK".(**https://services.odata.org/v2/northwind/northwind.svc**/)
Select Data: Browse through the available data sets in the OData feed, select the ones you need, and click "Load".


**Step 2: Data Transformation **
Power Query Editor: If needed, use the Power Query Editor to clean and transform the data.
Data Cleaning: Remove unnecessary columns, handle missing values, and format data types.
Close and Apply: Once the data is cleaned and transformed, click "Close & Apply" to load the data into Power BI.
Step 3: Create Data Model
Relationships: Go to the "Model" view to define relationships between different tables if necessary.
Measures: Create measures using DAX (Data Analysis Expressions) to perform calculations needed for your analysis.
Step 4: Design Report
Report View: Switch to the "Report" view.
Add Visualizations: Add visualizations to your report by dragging fields onto the canvas. Use charts like bar charts, line charts, pie charts, etc.
Create Measures: Define measures for calculations such as Total Sales, Sales Targets, and Income.
DAX
Copy code
Total Sales = SUM(Sales[Amount])
Sales Target = SUM(Targets[TargetAmount])
Income = SUM(Income[IncomeAmount])
Step 5: Customize Visuals
Formatting: Customize the look of your visuals by adjusting colors, labels, and other formatting options.
Slicers and Filters: Add slicers and filters to make the report interactive.
Step 6: Publish Report
Save Report: Save your Power BI file.
Publish: Click on "Home" > "Publish" and choose your Power BI workspace to publish the report.
**Step 7: Create Dashboard **
Power BI Service: Open the Power BI Service in your browser.
Navigate to Workspace: Go to the workspace where you published your report.
Create Dashboard: Click "New" > "Dashboard".
Pin Visuals: Go back to your report, hover over a visual, and click the pin icon to add it to your dashboard.
Customize Dashboard: Arrange and customize the dashboard layout.
**Example Visualizations**
Sales vs. Target Bar Chart: Compare actual sales figures against sales targets.
Income Line Chart: Show income trends over time.
KPIs: Display key performance indicators such as total sales, target achievement percentage, and total income.
**Summary**
Connect to OData Feed.
Transform and Clean Data (if necessary).
Build Data Model with relationships and measures.
Create and Customize Report with visualizations.
Publish and Share the report and dashboard.

### Housing Rental Analysis for San Francisco

In this analysis, we will be using Python libraries such as Pandas, hvPlot, and GeoViews to visualize and analyze the real estate data for San Francisco. We will be working with the sfo_neighborhoods_census_data.csv file from the Resources folder to create a DataFrame that we will use for our analysis.

Steps to Perform Analysis
Calculate and Plot the Housing Units per Year
Load the sfo_neighborhoods_census_data.csv file into a Pandas DataFrame.
Group the data by year using the groupby function and aggregate the results by the mean of the groups.
Use the hvplot function to create a bar chart with the x-axis representing the years and the y-axis representing the housing units.
Style and format the bar chart to ensure a professionally styled visualization.
Calculate and Plot the Average Sale Prices per Square Foot
Group the data by year using the groupby function and average the results.
Find the lowest gross rent reported for the years included in the DataFrame.
Create a new DataFrame named prices_square_foot_by_year by filtering out the "housing_units" column and including the averages per year for only the sale price per square foot and the gross rent.
Use hvplot to create a line plot with two lines representing the sale price per square foot and the gross rent.
Style and format the line plot to ensure a professionally styled visualization.
Compare the Average Prices by Neighborhood
Load the sfo_neighborhoods_census_data.csv file into a Pandas DataFrame.
Group the data by neighborhood using the groupby function and aggregate the results by the mean of the groups.
Create a bar chart using hvplot to compare the average prices by neighborhood.
Style and format the bar chart to ensure a professionally styled visualization.
Build an Interactive Neighborhood Map
Load the sfo_neighborhoods_census_data.csv file into a Pandas DataFrame.
Use GeoViews to create an interactive map of San Francisco with neighborhood boundaries and color-coded average sale prices per square foot.
Style and format the map to ensure a professionally styled visualization.
Compose Your Data Story
Analyze the findings from the previous steps and create a data story that includes the main insights and conclusions drawn from the visualizations.
Use markdown cells in Jupyter notebook to create a narrative that presents the findings in a clear and concise manner.
Include any additional insights, observations, or recommendations for potential real estate investment opportunities in San Francisco.

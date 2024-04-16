# Project1Bootcamp

Mobile homeparks and Tornadoes risk in USA


Description

This project assesses the risk of tornado occurrences for mobile home parks in the US. It analyzes historical tornado data and the spatial distribution of mobile home parks to identify high-risk areas and provide mitigation recommendations.

Usage

Run the provided Python scripts to clean and analyze the data.
Follow the code comments for specific instructions on data processing and visualization.4

Data Sources
Tornado data: Retrieved from www.kaggle.com
Mobile home parks data: Retrieved from www.kaggle.com

Analysis
Cleaned and processed tornado and mobile home parks data.
Analyzed tornado frequency, severity, and spatial distribution.
Classified tornado risk categories for mobile home parks based on historical data.

Steps in the code:
Step 1: Imported Libraries: Pandas, geopandas, shapely, matplotlib, geoviews, hvplot, numpy and scipy
Step 2: Define file paths and read data from both CSV's
Step 3: Cleaning and renaming the data for both CSV files
Step 4: Merging data from both data sets, based on coordinates.
Step 5: Plot the number of tornadoes vs years
Step 6: Calculate and plot the distribution of tornadoes based on the Fujita Scale Category.
Step 7: Count tornado occurrences by state and visualize top 10 most affected states.
Step 8: Calculate the total number of victims by state and visualize the top 10 states.
Step 9: Calculate the tornado count for matching locations
Step 10: Define risk thresholds for Mobile Home Park locations based on tornadoes frequency and classify accordingly with yearly average.
Step 11: Filter and display all 'Low Risk' Mobile Home Park locations, based on tornadoes risk thresholds.
Step 12:tep 12: Filter and display all 'Moderate, High and Very High risk' Mobile Home Park locations, based on tornadoes risk thresholds.


Results
Identified high-risk areas for mobile home parks.

Overall, the analysis helps to better understand the relationship between tornadoes and mobile home parks, informing decision-making processes for disaster risk reduction and management.
# Project1Bootcamp
Mobile homeparks and Tornadoes risk in USA
## Project 1 - Mobile Home Parks and Tornadoes Risk Assessment in the US.

### Objective: 

#### Assess the risk of tornado occurrences for mobile home parks in the US. Tornadoes pose a significant threat to mobile home parks due to their vulnerability to high winds and flying debris. By analyzing historical tornado data and the spatial distribution of mobile home parks, the project aims to identify high-risk areas and provide recommendations for mitigation strategies.

### Step 1: Imported Libraries: Pandas, geopandas, shapely, matplotlib, geoviews, hvplot, numpy and scipy

### Step 2: Define file paths and read data from both CSV's

### Step 3: Cleaning and renaming the data for both CSV files (for later merging)

### Step 4: Merging data from both data sets, based on coordenates.

### Step 5: Plot the number of tornadoes vs years

### Step 6: Calculate and plot the distribution of tornadoes based on the Fujita Scale Category, scale for rating tornado intensity, 
### based primarily on the damage tornadoes inflict on human-built structures and vegetation.

![image-2.png](attachment:image-2.png)

### Step 7: Count tornado ocurrences by state and visualize top 10 most affected states.

### Step 8: Calculate the total number of victims by state and visualize the top 10 states.

### Step 9: Calculate the tornado count for matching locations (Mobile Home Parks and Tornadoes)

### Step 10: Define risk thresholds for Mobile Home Park locations based on tornadoes frequency and classify accordingly with yearly average.
 
###Low Risk: 0 to 1 tornado per year
###Moderate Risk: 1 to 3 tornadoes per year
###High Risk: 3 to 6 tornadoes per year
###Very High Risk: More than 6 tornadoes per year

### Step 11: Filter and display all 'Low Risk' Mobile Home Park locations, based on tornadoes risk thresholds.

### Step 12: Filter and display all 'Moderate, High and Very High risk' Mobile Home Park locations, based on tornadoes risk thresholds.

### Conclusions and posible uses for this info.

#### 1. There are numerous mobile home parks that are in a moderate to very high tornado ocurrance risk, even though most of them have a low risk threshold.
#### 2.- Florida is the state with the highest risk of experiencing a tornado according to the historical annual average.
#### 3.- This data can be useful for government use for requesting resources against disasters and have contingency plans prepared.
#### 4.- The data can help select an appropriate place to vacation or live in a mobile home. 
#### 5.- The data can also be used by insurers to offer insurance against natural disasters on high tornado risk sites.


###Final note: We used code that we see in class but laso we us Chatgpt as reference to solve some points of the code.



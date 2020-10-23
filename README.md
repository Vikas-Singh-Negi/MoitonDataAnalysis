# Motion Data Analysis and Visualization using Spatial Data Science

Application of open source resources to visualize movement data obtained from GPS

#Business Use cases :

1 . For reduction in the total downtime of a network node caused due to a power failure mobile generator are triggered to power sites.Challenge is to track this movement and analyze this movement of vehicle from the perspective of route taken and speed at which the vehicle was running towards desitnation,etc.

2 .Fleet management and logistics field also need to have a movement data analytics to improve their model of operations and enhance Opex saving for example fuel saving by optimizing the route making use of movement data visualization 

#Approach : 

1. Make use of gpxy package to import gps data and then pandas and gepopandas to clean and transform data into geo dataframe
2. Create trajectory collection using movingpandas package to further analysis on moving data
3. Use hvplot parameter to visualize trajectory data to explore and properties like speed variation,direction of flow,star-end point,etc
4. Tracking vehicle making use of Folium HeatMapWithTime approach.It's was quite interesting to make use of heatmap with time approach to visualzie a vehicle movement

#Benefits:

1. A fully opensource solution that can address problem related to fleet management which is domain agnostic
2. A very easy but powerful solution that gives business a data visualization which can be custmized as per their expectation



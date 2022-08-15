# PyBer_Analysis
analyze all the rideshare data from January to early May of 2019 and create a compelling visualization for the CEO, V. Isualize.

#Overview of Analysis 

For this mod I will be preforming analysis and creating a summary dataframe that will show side share data by city type (Rural, Urban, Suburban). 

Once we get this summery dataframe we will be crateing a maultible line graph that shows the total weekly fares by each city type.

the Pandas groupby() function along with the count() and sum() to get the total number of drivers, rides, and fares by city type.

Once we pulled this information and assigned it to functions we were able to calculate our average fare per ride and driver. 

Once we had all this information toghther, I formated the dataframe into a new dataframe with reformated columns. 

Now that I have a summery dataframe, I will be using the Pivot() and resample functions to create multiple line graphs that show total fares for each week by city type between the months of January april 2019. 

Results by city type. 
![alt text](http://url/to/img.png)

Rural cities has the least amount of drivers, rides and total fares, this is to be expected due to the population differences between city types. 

Urban Cities have the most amount of drivers, rides, and total fares, urban cities populations are very dense for its area making it the most active city type. 

Suburban cities are middle between rural and urban cities for the secound most drivers, rides and total fares. 

Rural cities has the highest average fare per driver with far less total drivers then the other two city types. This is becouse there are less people willing to become drivers becouse the pool of aplicents is smaller. The average fare per driver was so large in rural areas becouse 

Urban cities dominated the total driver,Total fares, and total rides but the average fare per driver was much lower then the other two groups. 

#Chart showing the Total Fare by city type between January & April of 2019 
![alt text](http://url/to/img.png)

#Summary 

We are able to see what kind of fares will be commanded based on the city the ride is in. 
Instead of looking at each city individualy we can look at the types of cities and get a good look at what fares look like on a week to week basis based on city type. We can use this information to decide what rates will need to be changed based on the users city type. we can safly say that rural cities will require higher fares becouse of the amount of time it takes to get from location to location is much longer. The amount of workers in rural areas is also much less and will cause demand for drivers to increase. 

#Recommendations 

1. Make ajustments to the fare rates based on how many riders are in the city at a certian time 
2.Have drivers work in there city type to deturmine rates and if they switch cities re-assin city type based off geomap. 
3. Char







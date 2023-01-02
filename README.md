# Bikesharing

## Overview

The purpose of this analysis is to determine how often and for how long bikes are being checked out to riders. To do this, the Citi Bike tripdata file for August 2019 file (Not included due to size of file) was used as the base information since people would be more likely to be biking during the summer. One aspect of this, the tripduration values, needed to be converted to a more appropriate datatype, as seen in the [NYC_Citibike_Challenge](https://github.com/stwpf01/Bikesharing/blob/main/NYC_CitiBike_Challenge.ipynb) file. This information was then visualized using Tableau. Results from this data will be shown below.

## Results
![Checkout Times by Users](https://github.com/stwpf01/Bikesharing/blob/main/Images/CheckoutTimeUsers.png)

The majority of users only checkout bikes for approximatly ten minutes. After forty minutes the amount of people still using the bikes is practically imperceptible on the graph. Note that there are still people using them for longer than forty minutes.

![Checkout Times by Gender](https://github.com/stwpf01/Bikesharing/blob/main/Images/CheckoutTimesGender.png)

This graph follows a similar trajectory to the previous graph. The main difference is that it is now visible which gender uses these bikes, in this case male, more frequently.

![Trips by Weekday per Hour](https://github.com/stwpf01/Bikesharing/blob/main/Images/TripsWeekdayHour.png)

(NOTE: The darker the color the more people are riding at that time.) During the weekdays people tend to start early in the morning around 8:00 am or late afternoon at 5:00 pm. Weekends they more frequently start a little later at 10:00 am but are more consistently takings trips until 5:00 pm.  

![Trips by Gender (Weekday per Hour)](https://github.com/stwpf01/Bikesharing/blob/main/Images/TripGenderWeekday.png)

Similar findings to the previous graph with the genders split between three graphs. One somewhat noticible difference, even when taking the skewed demographics into account, is that males are more likely to ride during the hours of 12:00 am and 4:00 am compared to females.   

![User Trips by Gender by Weekday](https://github.com/stwpf01/Bikesharing/blob/main/Images/UserTripGenderWeekday.png)

Subscribers are far, far more likely to use the City Bike service compared to the nonsubscibed customers. This is most likely due to a subscription denoting higher necessity for the product, such as people who live in the city, compared to people who may only need the service once, such as tourists.   

![August Peak Hours](https://github.com/stwpf01/Bikesharing/blob/main/Images/PeakHours.png)

This graph shows similar information as the "Trips by Weeday Per Hour" graph, albeit in a different, more easily interpreted format, and only showing the start time of trips. 

![Demographics by Age and Gender](https://github.com/stwpf01/Bikesharing/blob/main/Images/Demographics.png)

This graph shows the ages of people using the service. The most obvious point about this graph is the incredibly high amount of people born in 1969 with Unknown as their gender. This most likely means that the birthyear 1969 and gender Unknown are the generic attributes when checking out a bike and people are not filling out said information. It is unclear how much that would change the gender/birthyear parameters if all forms were filled out with the correct information, however the disparities of the graphs would most likely not change in any significant way (females using the bikes more frequently than males, etc.)  


## Summary

If an assumption were to be made, peope check out these bikes to get to and from work during the weekdays, while on the weekends the bikes are used more for leisure. This is assumed due to the three heatmap graphs showing the average times for starting work, around 8:00 am, and leaving work, around 5:00 pm, are peak trips times during the week. Also, since peope don't often work the weekends, people can start a trip that better suits their preferred time, hence the more generalized start/stop times on the weekends. For future analysis, it would be interesting to see the areas bikes are checked out by gender and birthyear to better cater to their needs.  

## Tableau Link

[Tableau Story](https://public.tableau.com/app/profile/stwpf/viz/Module15_16726403698440/Story1#1)
#  Project 3: Plate Tectonics

# Infomation location:

  Code URL:
  
  README URL: 
  
# Problem Statement:

  This project was given to better undersand tectonic plate motion and the effects this motion has on earthquakes. For this prject 
  we will use the Juan de Fuca plate, which is off the west coast of the United states and Canada, and the differnet boundary conditions this
  plate comes with. Using data from a Ocean Bottom Seismometer we are able to analyze the Juan de Fuca plate movement over the past 10 years.
  The code is writen in python and will inform the user of seismic activity in this plate. 

# Results:
  In Figures 1a and 1b the data for rain rates are ploted agenst wind speeds. Four circumstances implemented in the background of the plots to show times in which there is only rain, only wind, both rain and wind, or neither rain nor wind. 
  In the following garphs the following assumptions were made: 
  
    Rainy Days: >0.1mm/hr
    Windy Days: >2.5mm/hr 
    
  
  ![alt text](https://github.com/stephenscharkov/Project-2/blob/master/Fig1a.PNG)
  
  Figure 1a: Rain and Wind Rates for Oregon Offshore Surface Mooring

  ![alt text](https://github.com/stephenscharkov/Project-2/blob/master/Fig1b.png)
  
  Figure 1b: Rain and Wind Rates for Oregon Offshore Surface Mooring
  
  
  Comparing the two site in the cross colleaction graphs bellow we can see that both the sides have a strongly correlated. We can see that the max correlation will be approximately around .715 at lag 1. We can reason that there is such a strong correlation between the data becasue of the low interference the wind will have over the water. From this low interference the wind is allowed to move at relativly high speeds and move to the other location with ease. The relactionship of the wind correlation can be seen in Figure 2a. The justification why the time lag is at one and there is not lag can be shown in the difference in time measurements of each site. With the timestaps of both cites being measured every 8 hours we can see that most time are recoded below an 8 hour differnce and will cause a insignificant lag. 
  
  Similar conections can be made with the rain correlation as the wind. Seen in Figure 2.b the max rains's correlaciton is at lag 1 with slightly lower value of 0.634. This is still a strong correlation in data and shows that the two site act quie similarly. Seeing as rain normally forms as a change in atmosheric pressure which is seen more over large masses of water these result hold truth.

  Both data sets of rain and wind have a strong correlation between the sites with a low lag, the wind is slighly favored for the crrelation. 
  ![alt text](https://github.com/stephenscharkov/Project-2/blob/master/Fig2a.png)
  
  Figure 2.a: Wind Correlation Data
  
  ![alt text](https://github.com/stephenscharkov/Project-2/blob/master/Fig2b.png)
  
  Figure 2.a: Rain Rate Correlation Data


  In the final figure (Figure 5) the average monthly data is ploted to check the overall data. From this figure we can see that the rainest mounth is going to be December and the month that sees the least will be Augest. THe windiest day in the year is going to be January with the calmist month being August. This follows suite with the general patterns seen on the west coast forcast over several year, in which the winder parts of the year are in the winter as well as rainer.
  
  ![alt text](https://github.com/stephenscharkov/Project-2/blob/master/Fig3.png)
  
  Figure 5: Monthly Averages
  
  
  # Conclusion:
  
  Accurate measurements of large scale weather systems can be made by widely space data collection devices due to the low lag rates and the strong correlation of data seen above. 
  
  # References:
  
    https://ooinet.oceanobservatories.org/ 
    https://www.noaa.gov/ 
    https://earthquake.usgs.gov/earthquakes/map/
    https://datalab.marine.rutgers.edu/explorations/geology/activity1.php
    http://geoviews.org/
  

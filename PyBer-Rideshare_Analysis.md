#Analysis of PyBer Data Sets and Graphs

#Overview of the Analysis   
    #The purpose of this python database and matplotlib analysis was to determine different characteristics and trends between cities, drivers, and their respective fare prices for a Ridesharing company.  This was done in order to efficiently communicate large .csv files into key metrics and visualized graphs that will provide the CEO with the correct route of action moving forward.  The key metrics observes are of ridership and rfare pricing by the types of cities (urban, suburban, or rural).  This may hopefully provide the CEO with key metrics determining the affordability and availability of his ride share application.  

#Results
    #By various merging and grouping techniques we came with some interesting resutls. We find that there is the a relationship between fare revenue according to city type is higher the larger the number of drivers compared to passengers.  
    ##On Average Urban Cities have the highest demand while rural cities have the least demand, with suburban sitting at below the 50th percentile.  
    ##Rural areas have the highest average fare, likely based upon the number of drivers and average fare per ride, if one considers the possibility for longer rides in rural areas as well.
    ##This trend is peculair in suburban cities where revenue is 4.5x the rural revenue with nearly seven times the numebr of riders.  This could show a possible area for improvement for the ceo or a place to reevaluate serving.  

 #Summary
    ##There are a few routes of action when approaching the CEO.  One approach is to say, based solely average fare per ride per city that there needs to be a reinforcement of rural drivers.  Though this may present an issue.  Rural areas are covering longer distances- if there are limited numbers of drivers and, in the unforuntate circumstance, that there are more requests than rides available, PyBer will lose revenue.  On the other hand if the supply of rural drivers increases a measured amount and not to critical mass, potentially utiliziting optimization techniques or introducing a nquist control variable, one could maximize the amount of revenue per ride per driver in every respective area.  Barring this extensive mathematical approach, recommending an incremental approach to supplying more drivers in rural areas while closely mintoring average fare per ride will maximize revenue.  In urban and suburban areas similar techniques may be approached but it may require different time frames for rideshare data and could require certain drivers to be nixxed or overall driver supply to diminsih to increase demand and thus maximimize potential revenue.  

check image pyber_fare_summary
#check ride share summary.png for supporting documents (sorry i couldn't link them in vscode while writing this readme!)
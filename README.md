# BoxBox
This notebook analize one of the most important moment and choice in Formula 1, the pit stops.  
The dataframe is from http://ergast.com/mrd/db/#csv and https://theoehrly.github.io/Fast-F1/ where there are a lot of record since 1950 untill 2022 about races, qualifing session, free practice, lap times, drivers etc. Races between 2011 and 2022 are used for the analisis due to the tyre rules in 2011.
The mysql format of fastf1 is used for this notebook.  
You can:
* calculate the average number of pit stops for the Grand Prix;
* calculate in which lap the pit stops are made;
* plot specific drivers in specific GrandPrix.  
  
Discaimer: it was created for practice using mysql, python and libraries like pandas, matplotlib and ipywidgets.  
The mysql format is not the best for this analisis. You can use Fastf1's api which contains more information (like tyres' compound), https://theoehrly.github.io/Fast-F1/. 

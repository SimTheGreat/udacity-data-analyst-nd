# Data-Visualization-Project<br>
udacitys last data analyst project<br>
<img src='download-1.jpg' alt="Image" height="300" width="500">
<h1>the data</h1><br>
 I used the usa flight data of april 2020 to analysise<br>
 you can find this data here:http://stat-computing.org/dataexpo/2009/the-data.html<br>
 <strong>data structure:</strong>
 <ol>
<li>year
<li>month
<li>carrier unique airline company code
<li>carrier_name airline company name
<li>airport destination airport, airport ID
<li>airport_name destination airport, airport name
<li>arr_flights number of flights arrived to airport (for given month)
<li>arr_del15 number of flights delayed at least 15 min (for given month)
<li>carrier_ct number of flights delayed due to air carrier, e.g. maintenance or crew problems, aircraft cleaning, baggage loading, fueling, etc. (for given month)
<li>weather_ct number of flights delayed due to weather conditions (for given month)
<li>nas_ct number of flights delayed due to National Aviation System, e.g. non-extreme weather conditions, airport operations, heavy traffic volume, and air traffic control (for given month)
<li>security_ct number of flights delayed due to security, e.g. evacuation of a terminal or concourse, re-boarding of aircraft because of security breach, inoperative screening equipment and/or long lines in excess of 29 minutes at screening areas (for given month)
<li>late_aircraft_ct number of flights delayed due to a previous flight using the same aircraft being late (for given month)
<li>arr_cancelled number of calcelled flights (for given month)
<li>arr_diverted number of diverted flights (for given month)
<li>arr_delay total delay time of arrived flights (in minutes)
<li>carrier_delay total delay time of arrived flights due to air carrier (in minutes)
<li>weather_delay total delay time of arrived flights due to weather (in minutes)
<li>nas_delay total delay time of arrived flights due to National Aviation System (in minutes)
<li>security_delay total delay time of arrived flights due to security (in minutes)
<li>late_aircraft_delay total delay time of arrived flights due to a previous flight using the same aircraft being late (in minutes)

<ol>
<h1>my questions:</h1><br>
<strong>1.	most common carrier name in moth 4 of 2020</strong><br>
Where I found SkyWest airlines the be most common in my data set and Hawaiian airlines to be the least common one<br>
<br>
<strong>2.ct reasons</strong><br>
Interesting is that security can be barley seen since I did not expect it to be like this<br>
<br>
<strong>3.most frecount carrier for cancellations</strong><br>
Here you can see that Hawaiian airlines does not have the least count of cancelled airline even dough it was the least common<br>
<br>
<strong>4.what the correlation between delays are</strong><br>
In the 4-delay variable each one had a positive correlation. Some were stronger some not, but each delay had a correction with another

<h1>Process</h1>
<ul>
<li>first I assest my dataset<br>
      1) Understanding your variables and data types<br>
      2) checking for data quality issues and tidyness issues<br>
      3) noting all these issues to be cleaned in the next step<br>
<li> data wrangling<br>
      1)first step was to create a copy of the original data set<br>
      2)then I defined each issue as listed in the assessing summary<br>
      3)coded the solution<br>
      4)tested the solution to check if it worked<br>
<li>data exploratiation<br>
       1)understand one variable using Univariate exploration<br>
       2)understand the corrolation using 2 variables using Bivariate exploration<br>
       3)understand th corrolation of 3 or more variables using Multivariate exploration<br>
   
</ul>
<h1>accsessing my code</h1>
you couls either download it or accsess my html code here:<br>
the explanetory slidedeck here:(https://codepen.io/simsalabim1/pen/jOWXqYr)<br>

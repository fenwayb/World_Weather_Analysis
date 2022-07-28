<h1 Align="Center">
  
  World Weather Analysis

  # Overview
  
  <p>For this project we were tasked with using a handful of Google APIs as well as the OpenWeather API to make a program that would allow the user to put in preferred weather parameters and get recommended travel destinations based on those parameters.</p>
  
  ## Results
<p>The program worked successfully and to test it I generated my own trip. I personally hate hot weather so I set my parameters to 50 and 75 degrees fahrenheit. That map looked like this: </p>

![WeatherPy_vacation_map](https://user-images.githubusercontent.com/106105597/181635553-2e06280f-4666-4340-83b0-223d81a9256c.png)

<p>I was looking for a trip where I could go to a couple different locations in the same country, which led me to Northern Canada. I ended up planning out the following trip:</p>

![WeatherPy_travel_map](https://user-images.githubusercontent.com/106105597/181635714-daaad954-08bd-4fd5-a13f-884c244b3f6b.png) 

<p>For this trip I would: 
  
  * start in Whitehorse, YT, then go to
  * Fort Nelson, BC, then go to
  * High Level, AB, then go to
  * Yellowknife, NT then back to
  * Whitehorse, YT</p>
  
<p> Had I chosen warmer parameters I would likely had gotten less remote recommendations </p>

## Conclusion and Potential Improvement
<p> This program was a success as it was able to draw from Google maps and the OpenWeather API to get day by day weather parameters for cities around the world. One major flaw with this method that ideally would be improved in future updates is that it only makes the weather call once (when the user runs the program), which will only show what the weather is like right now, and might not be an accurate prediction of the average weather conditions of a location. The fact that my "cold" map has many locations that would generally be considered hot are likely because it was nighttime in those regions when I ran my program and therefore the weather was colder than what it would be during the typical day. More advanced versions of the OpenWeather API allow for more predictive calls and therefore implenting one of those paid versions could solve this problem. </p>

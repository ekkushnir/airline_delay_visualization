
# Write-up for the Data Visualization Project using Tableau

#### Link to the first version:

https://public.tableau.com/profile/katie3180#!/vizhome/flights_delays/delays

#### Link to the final version: 

https://public.tableau.com/profile/katie3180#!/vizhome/flights_delays_final/ArrivalDelays

## Summary

With thousands of flights arriving at U.S. airports every day, delays are unfortunately a common thing. Delays statistics vary across airports and airlines and over time. Delay causes are classified into delays due to air carrier, National Aviation System (NAS), late-arriving aircraft, extreme weather and security with the first three being the most common causes of delays. Weather on the other hand is not one of the main cause of delays contrary to what one might think.

## Design

**Initial design choices** were as following:

- I used pie charts to show the proportions of shares of delayed and on-time flights counts and delay causes in comparison to each other. 

- For the timeline of flights and delays I used a line chart in order to illustrate the development of flights over time as well as seasonal differences throughout the year.

- For pointing out differences between airlines I used a treemap indicating overall airline size by the size of each airline block and the delay percentage from all flights by the color (ascending from yellowish brown to redish brown). Allongside with the airline treemap I used a sorted bar chart for delay percentages with the same color palette.     

- For illustrating the differences between airports I used a map with circles sized to illustrate overall traffic going through the airport and the size of the circles indicating delay percentage from all flights.

- I used bubbles of different sizes for airlines to indicate their shares of delays attributed to carrier and color to illustrate different average length of delays. Alongside the bubble chart I added two barcharts revealing the same information but in a different form so you can have a list of airlines instead of looking for them in the bubble chart.

- For showing seasonality effects in weather delays I used bar charts in addition to box plots (to eliminate the effect of outliers) with trend lines (for better understanding of month differences).

- I tried to use grey scale colors as much as possible to keep data-to-ink ratio high as well as color blind palete for pie charts where using different colors was necessary.

- When choosing a layout I tried to optimize visual appeal of charts and information flow.


**After collecting feedback** I made following changes to the visualizations:

- Break down of the first milestone in two steps: first one shows overall flights distribution and includes all airlines, airports and dates, the second shows an extreme case with the highest share of delays. Also improved layout, the broken link fixed.
- Since it was difficult to detect trends from the the timeline chart, I reduced the frequency of the chart from months to years. Also improved layout for the monthly grouped shares of delays, on-time arrivals etc.  
- Improved layout of the story step where the pie chart with delay causes is shown: the defintions are shown first, then the illustration to improve it's understanding.
- The color bar for different delay length is shown above the bubble chart similar to comparable charts to improve readability of the visualization.
- Improved scale captions.

## Feedback

Feedback quote:

> Every chart was easy to understand. Sometimes the order of introduction and chart and defintions and chart could have been different (in case of two pie charts). Box plot might not be that easy to understand if you are not a statistician. I was surprised that such a big share of delays persists over time. It was also interesting for me that the biggest and busiest airports are not those which have highest number of delays. From all the airlines presented Hawaiian Airlines has the highest share of delays. There are minor design changes which can be implemented e.g. the order of charts on story milestones where more than one chart is presented at once and a more clear definition for some chart variable names. The timeline chart is somewhat difficult to understand because of many line jumps. However, overall, illustrations are engaging and informative.

## Resources


Data sets and glossaries

https://www.transtats.bts.gov/OT_Delay/OT_DelayCause1.asp?pn=1

https://www.bts.dot.gov/explore-topics-and-geography/topics/airline-time-performance-and-causes-flight-delays

https://www.transtats.bts.gov/DL_SelectFields.asp?Table_ID=236

https://opendata.socrata.com/dataset/AirportLocations/ia9d-4ymt

https://aspmhelp.faa.gov/index.php/Types_of_Delay

Supporting materials

https://pandas.pydata.org/pandas-docs/stable/

https://www.youtube.com/user/tableausoftware

https://stackoverflow.com/questions/51722864/reshaping-pandas-dataframe-python-3-x?noredirect=1&lq=1

Data Set used : USA Air Transport Department. Airline Flight Delay database. Date Range : Jan 2012-Dec 2015. 

#### Summary
There are two visualizations I have created.

1. Airline Coverage of USA cities. 
This shows the coverage of various cities in USA by all the domestic airlines. Also shows the number of flights at airports to highlight major and minor airports. 
The default visualization shows all the cities, their location on the map, the major airline at each airport and the number of flights operating. 
Using the filters provided, we can then look at individual airlines and their coverage. 

2. On Time Performance Trend of Flights at top 10 US Airports. 
This shows the trend of On Time Performance of Airlines by top 10 Airports(Top 10 by total flights). This can be used to see which airports perform 
better compared to others. One or multiple airports can be selected to see and compare their trends closely. 

#### Design - 
##### Airline coverage of USA Cities.
Since the data had cities, thought it would be great to plot it on a map. Extracted the Latitude and Longitude of USA Cities from the internet and combined with 
the airline data to come up with the dataset. The initial visualization created had all the flights for all airlines together.
It had ability to filter individual airline and see its coverage. After feedback, made changes to the initial screen to color the circles of the airport
by the major airline operating at that airport. The size of the circle denotes the number of flights and easily shows which are bigger airports. When we filter
the visualization by an airline, we can see the major airports for that airline and the coverage. 

###### On Time Performance Trend of Flights at top 10 US Airports
Since the idea was to show the trend of on time performance over time, line chart was the obvious choice. Made the thickness of the line to denote the 
number of flights to encode another factor. Made the lines a little transparent so that we can see the trends easily as most of the lines were
overlapping. To make it much more easier to see the trend of one airport, added highlight option on hover. After getting feedback, added options to 
enable selection of one or multiple airports to highlight them more clearly. 

#### Resources 

1. https://d3js.org
2. https://github.com/d3/d3/wiki/Arrays
3. http://bl.ocks.org/mbostock/3884955
4. http://bl.ocks.org/natemiller/20f9bd99d1795e3a0b1c
5. https://bl.ocks.org/mbostock/4342045
6. http://bl.ocks.org/mapsam/6090056
7. http://www.frankcleary.com/making-an-interactive-line-graph-with-d3-js/
8. http://www.d3noob.org/2014/04/using-html-inputs-with-d3js.html
9. https://bl.ocks.org/mbostock/5872848
10. http://bl.ocks.org/Caged/6476579 D3 Tool Tip
11. http://bl.ocks.org/ZJONSSON/3918369 D3 Legend. 

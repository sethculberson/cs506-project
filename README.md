# Boston Game Day Transit Analysis Proposal
Authors: Amanda Atlas, Owen Lennox, Seth Culberson

## Description
Major sporting events at high capacity arenas in Boston (TD Garden for the Bruins and Celtics, Fenway Park for the Red Sox) cause significant spikes and congestion in transit use. Game days can create unpredictable demand in ridership, which leads to delays, overcrowding, and increased travel times. 

## Timeline
| Weeks | Task | Milestone |
|-------|------|-----------|
| 1-2 | Data Collection | Clean and QA datasets for correctness. Variables to scrape data for include: weather, day of week, concerts, sporting events, transit/bluebike data. |
| 3-4 | Clustering | Have our 1st check in. Complete clustering of stations (most/least/partially) affected by sporting events. |
| 5-6 | Data visualization/model training | tbd |
| 7-8 | Create demo/Final Report/Presentation | Create user-friendly interface (PowerBI or Streamlit) |

## Goal(s)
Our project goals are to identify transit stations and areas most affected by sporting events in Boston and estimate delays and demand for Boston public transit (MBTA)/bluebikes caused by game day congestion. 

## Data Collection
We will collect data from four sources. The first  dataset is called City of Boston's streets hourly bike count, which record hourly counts of bikes, cars, buses, and trucks on streets around the city. We can download this as a CSV and filter to only include days that coincide with games in Boston. The MBTA ridership and performance data sets contains performance and passenger usage data hourly for busses, trains, ferries, and the commuter rail. We can use this for  demand and traffic data on game days, and cam be downloaded as a csv. The weather data set will allow us to consider weather which may impact service and passenger demand, and can be downloaded as a CSV. Finally, Red Sox, Bruins, and Celtics home game schedule with date and start time, will be collected by scraping Ticketmaster or live Nation to label each day as a game day. 

* [Boston Open Data Sets](https://bostonopendata-boston.opendata.arcgis.com/search?collection=dataset)
* [MBTA Data Sets](https://mbta-massdot.opendata.arcgis.com)
* [Weather](https://www.weather.gov/wrh/climate?wfo=box)

## Data Modeling
Density-Based Clustering: We are thinking this approach because transit lines are not circular and this accounts for that. We predict that core points will be closer to sporting venues. TBD on how we will estimate delays. 

## Data Visualization
TBD

## Test Plan
TBD

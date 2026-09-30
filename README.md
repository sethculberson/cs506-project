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
Just links for now, need to add more here
* [Boston Open Data Sets](https://bostonopendata-boston.opendata.arcgis.com/search?collection=dataset)
* [MBTA Data Sets](https://mbta-massdot.opendata.arcgis.com)
* [Weather](https://www.weather.gov/wrh/climate?wfo=box)

## Data Modeling
Density-Based Clustering: We are thinking this approach because transit lines are not circular and this accounts for that. We predict that core points will be closer to sporting venues. TBD on how we will estimate delays.

## Data Visualization
TBD

## Test Plan
TBD
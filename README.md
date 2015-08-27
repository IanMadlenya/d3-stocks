# Stock/Search
## Synopsis

This is the second project of the senior phase at Fullstack Academy of Code. It is a stock-analysis tool for visualizing data not traditionally associated with stocks. Utilizes D3 to show the relationship between a stock price and a Google keyword search volume over time.

## Motivation

The purpose of this project is to allow each student to develop their own idea for an application. I learned and utilized D3 for this project, which was not part of the curriculum at Fullstack Academy.

## Challenges
There is no Google Trends API to gather data from.
I figured out that the data was available in an HTML script tag at the bottom of a particular Google URL. I was able to turn the data into something usable for my d3 visualization. Essentially I turned a particular Google URL into an API I could make cross-site requests to.

## Code Structure

The repository is split into two folders: 

####_browser_
Frontend application (Angular and D3).

####_server_
Backend (Node, Express) application.

## External Libraries and Technologies Used

We have used many open source technologies for completion of this project as follows:
* Frontend Application
  * Angular
  * D3
* Backend Server
  * Node
  * Express


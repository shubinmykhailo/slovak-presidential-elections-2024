# Slovak Presidential Elections 2024 – Power BI Dashboard
Interactive Power BI dashboard analyzing the 2024 Slovak presidential election results across both rounds, built using official data from volby.statistics.sk.

## Dashboard Overview

The dashboard consists of 3 pages:
- **Round 1** – Results by district and region with candidate filter
- **Round 2** – Results with dynamic map modes (vote share, turnout, winner by district)
- **Comparison** – Side-by-side turnout and vote comparison across both rounds

## Features
- Interactive Shape Map with custom TopoJSON (49 districts, 8 regions)
- Dynamic map coloring via Field Parameters
- Custom tooltip pages for district and region maps
- Drill-through pages for both geographic levels
- Bookmark-based map type switcher

## Data Source
Official Slovak election data: [volby.statistics.sk](https://volby.statistics.sk)

## Tools
- Power BI Desktop
- DAX
- Custom TopoJSON/GeoJSON
- Custom Power BI theme (Slovak flag colors)

## Key Insights
- Voter turnout increased from 51.92% to 61.15% between rounds
- Korčok won Round 1 but lost Round 2 to Pellegrini
- Pellegrini dominated central, eastern and northern Slovakia
- Korčok's stronghold was Bratislava and western districts
- Turnout was lowest in southern and southeastern districts

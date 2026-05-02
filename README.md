# Slovak Presidential Elections 2024 – Power BI Dashboard
Interactive Power BI dashboard analyzing the 2024 Slovak presidential election results across both rounds, built using official data from volby.statistics.sk.

## Dashboard Overview

The dashboard consists of 3 pages:
- **Round 1** – Results by district and region with candidate filter
- **Round 2** – Results with dynamic map modes (vote share, turnout, winner by district)
- **Comparison** – Side-by-side turnout and vote comparison across both rounds

## Live Demo
[View Dashboard](https://app.powerbi.com/groups/me/reports/95ebee39-925d-4b3a-8eea-054bc5291d7c/9eb934369664c5908b9e?experience=power-bi)

**Round 1 – District view with custom tooltip**
<img width="1428" height="798" alt="Screenshot 2026-05-01 225157" src="https://github.com/user-attachments/assets/eb9ea7e2-6da7-4e9e-8af9-dd425ba097ff" />

**Round 2 – Vote count by region**
<img width="1422" height="802" alt="Screenshot 2026-05-01 230237" src="https://github.com/user-attachments/assets/16f3a5e7-0514-4ce3-9d7c-bfe92af36326" />

**Comparison page – Bratislava selected**
<img width="1430" height="804" alt="Screenshot 2026-05-01 225234" src="https://github.com/user-attachments/assets/268614cd-1193-41e5-b7c0-ec06c8a14b6b" />

## Features
- Interactive Shape Map with custom TopoJSON (49 districts, 8 regions)
- Dynamic map coloring via Field Parameters
- Custom tooltip pages for district and region maps
- Drill-through pages for both geographic levels
- Bookmark-based map type switcher

## Tools
- Power BI Desktop
- DAX
- Custom TopoJSON/GeoJSON
- Custom Power BI theme (Slovak flag colors)

## Key Questions & Answers

**Who won Round 1 and why did the result change in Round 2?**  
Korčok won Round 1 with 42.5% vs Pellegrini's 37%. In Round 2, Pellegrini won 53% — he secured endorsements from Forró (4th place, 2.9%), Kubiš, Náhlik and Danko, plus open support from PM Fico. Korčok was backed by Dubovský and Matovič. Pellegrini successfully  won 61 out of 79 districts.

**How did voter turnout change between rounds?**  
Turnout increased significantly from 51.92% to 61.15%, suggesting higher voter engagement in the decisive round.

**Where were each candidate's strongholds?**  
Korčok dominated Bratislava and western districts. Pellegrini dominated central, eastern and northern Slovakia.

**Where was turnout lowest?**  
Southern and southeastern districts consistently showed the lowest turnout in both rounds.

## Data Source
Official Slovak election data: [volby.statistics.sk](https://volby.statistics.sk)
[Wikipedia](https://en.wikipedia.org/wiki/2024_Slovak_presidential_election), [Geopolitique.eu](https://geopolitique.eu/en/articles/presidential-election-in-slovakia-march-april-2024/)*

---
title: Initial Setup and Data Sources
date: 2026-11-02
---

# Initial Setup and Data Sources

- Project repo: https://github.com/DamienFS/public-transport-analysis
- Tools: VS Code, Jupyter, Python, GitHub Pages

## Goal

To assess whether lower-income suburbs in Brisbane have lesser access to public transport services.

## Data Sources

- Public transport stops: Queensland Government Open Data Portal - SEQ general transit feed specification - https://www.data.qld.gov.au/dataset/general-transit-feed-specification-gtfs-translink/resource/e43b6b9f-fc2b-4630-a7c9-86dd5483552b
- Suburb boundaries: ABS/ASGS SA2 shapefiles - https://www.abs.gov.au/statistics/standards/australian-statistical-geography-standard-asgs/edition-4-july-2026-june-2031/access-and-downloads/digital-boundary-files
- Socioeconomic data: ABS Census SEIFA Indexes by SA2 area - https://www.abs.gov.au/statistics/people/people-and-communities/socio-economic-indexes-areas-seifa-australia/2021#data-downloads

## Next Steps (Anticipated)

- Data exploration and cleaning as required - likely need to trim ASGS to match Brisbane area
- Initial data merge - joining the stop data and SA2 data
- Calculate the public transport coverage for each SA2 area - metric to be defined, likely will be the percentage of the SA2 within 500m of a stop
- Merge in the SEIFA indexes
- Visualisation / interpretation
- Final polish7
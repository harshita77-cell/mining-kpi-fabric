# Mining KPI Tracker — Microsoft Fabric + Power BI

## Project Overview
An end-to-end KPI analytics project tracking global mining 
production performance across 80 countries and 80 materials 
(2000–2021), built using Microsoft Fabric and Power BI.

## Business Questions Answered
- Which countries produce the most minerals by volume?
- What is the year-over-year production growth per material?
- Which mines generate the highest waste ratio?
- What are the regional production trends over 20 years?

## Tech Stack
| Tool | Purpose |
|---|---|
| Microsoft Fabric Lakehouse | Data storage and pipeline |
| T-SQL | Data transformation and modelling |
| Power BI | Dashboard and visualisation |
| DAX | KPI measures and time intelligence |
| REST API | Secondary data ingestion |

## Data Sources
See [data/sources.md](data/sources.md) for full details.
- Global coal and metal mine production (Zenodo)
- Global mine production by mineral (Our World in Data)

## Project Structure

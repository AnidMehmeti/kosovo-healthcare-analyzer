# Kosovo Healthcare Access Analyzer

## Overview
This project focuses on finding underserved municipalities in Kosovo regarding primary healthcare (hospitals, clinics, doctors). It compares 27 municipalities with each other, establishes a baseline ratio of primary care per 1000 population, and analyzes the findings through four different visual representations.

## Key Findings
- 46.8% of the analyzed population (708,685 residents) lives in municipalities below the 0.162 baseline
- There is a capital/proximity divide where cities (Mitrovica, Ferizaj, Podujeva) near Prishtina are among the most underserved despite being urban
- Larger municipalities like Gjakova and Peja have a similar, but lesser gravity pull of that of Prishtina, with nearby smaller underserved municipalities

## Data Sources
[List all three sources with URLs]

## Tech Stack
Python (Pandas, Geopandas, Matplotlib, Seaborn)
Jupyter Notebook
GitHub

## Project Structure
kosovo-healthcare-analyzer/
├── data/
│   ├── raw/          
│   └── processed/    
├── notebooks/        
├── outputs/          
├── insights.md       
└── README.md         

## Limitations
This research does not take into cnsideraton the 11 excluded Serb-majority municipalities due to the lack of data and the political reality of the situation (potential parallel healthcare institutions). There is also a gap regarding recent private clinic data which might affect the ratio of larger municipalities like Mitrovica and Ferizaj, currently labeled as underserved.

## Author
Anid Mehmeti, RIT Kosovo, 2026
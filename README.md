# Global Technology and Internet Adoption Analysis (1990–2025)

## Project Overview
This project analyzes global technology and internet adoption trends using the **World Bank World Development Indicators (WDI)** dataset. The goal is to examine how internet usage, digital infrastructure, and technology-related indicators have evolved across countries and over time.
An interactive Power BI dashboard was developed to visualize trends, compare countries, and provide actionable insights for policymakers, researchers, and other stakeholders.

## Project Objectives
* Analyze global internet adoption trends.
* Compare technology indicators across countries.
* Examine the relationship between internet usage and high-tech exports.
* Develop an interactive Power BI dashboard for data-driven decision-making.
* Generate insights and recommendations based on the analysis.
  
## Dataset

**Source:** World Bank – World Development Indicators (WDI)
The dataset contains development indicators for over 200 countries and territories covering multiple sectors such as technology, economy, education, health, trade, and environment.

### Indicators Used
* Individuals using the Internet (% of population)
* Mobile cellular subscriptions (per 100 people)
* Fixed broadband subscriptions (per 100 people)
* Secure Internet servers (per 1 million people)
* High-technology exports (% of manufactured exports)
* Population, total

## Tools Used
* Microsoft Excel
* Power BI Desktop
* Power Query
* DAX (Data Analysis Expressions)
* GitHub
  
## Data Cleaning Process
The following data preparation steps were performed:
* Imported the WDI dataset into Power BI.
* Filtered the dataset to technology-related indicators.
* Removed unnecessary columns.
* Unpivoted yearly columns into **Year** and **Value**.
* Corrected data types.
* Removed blank and null values where appropriate.
* Created DAX measures for KPI calculations.
  
## Dashboard Features
The dashboard contains:
* KPI Cards
* Internet Usage Trend Analysis
* Top 10 Countries by Internet Usage
* Top 10 Countries by Mobile Subscriptions
* Internet Usage vs High-Tech Exports Scatter Plot
* Global Internet Usage Map
* Interactive Year and Country slicers
  
## Key Findings
* Internet usage has increased significantly over time.
* Countries with higher internet penetration often exhibit stronger high-tech export performance.
* Mobile subscriptions have grown rapidly across most countries.
* Significant differences in internet adoption exist across countries and regions.
* Secure internet infrastructure continues to improve globally.
  
## Recommendations
* Expand broadband infrastructure in underserved regions.
* Improve affordable internet access.
* Invest in digital literacy and technology education.
* Encourage innovation and research to boost high-tech exports.
* Continue monitoring digital development using reliable global indicators.

## Repository Structure
Global-Technology-and-Internet-Adoption-Analysis/
│
├── Dashboard.pbix
├── Final Report.pdf
├── Dashboard Screenshot.png
├── README.md
└── Dataset 

## Dashboard Preview
<img width="868" height="508" alt="global" src="https://github.com/user-attachments/assets/9522e27b-1945-46cc-ab84-880baab5f20c" />

## How to Use
1. Download or clone this repository.
2. Open the `.pbix` file using **Power BI Desktop**.
3. Use the **Year** and **Country** slicers to interact with the dashboard.
4. Explore the visualizations and KPI cards to understand global technology trends.

## Author
**Peter Samuel Covenant**
AnalystLab Africa Data Analytics Internship – Capstone Project

## Acknowledgements
Special thanks to **AnalystLab Africa** for providing the internship opportunity and practical learning experience.
Data Source: **World Bank – World Development Indicators (WDI)**

## License
This project was developed for educational purposes as part of the **AnalystLab Africa Data Analytics Internship Capstone Project**.

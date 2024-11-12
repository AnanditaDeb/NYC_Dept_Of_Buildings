# NYC DOB Permit Issuance Analysis

This project analyzes the DOB Permit Issuance dataset provided by the City of New York, offering valuable insights into the construction activities across the city. The dataset includes detailed information on permits, construction sites, and individuals involved in the permitting process, providing a comprehensive overview of New York City's construction landscape.

Through data profiling, cleaning, validation, and visualization, the project highlights trends in permit issuance and construction activities, such as identifying the most active boroughs and the most common types of work permitted. The analysis is presented in an interactive dashboard for enhanced data-driven decision-making.

## Project Overview

- **Dataset**: NYC DOB Permit Issuance
- **Data Source**: [City of New York Open Data Portal](https://data.cityofnewyork.us)
- **Objective**: To analyze construction activity trends, identify patterns in permit issuance, and create data visualizations to aid city planning and management.

## Key Highlights

- **Data Profiling**: Performed thorough profiling to understand dataset characteristics and distribution.
- **Data Cleaning & Transformation**: Cleaned data for inconsistencies and transformed it for analysis.
- **Data Validation**: Utilized Great Expectations for validating data quality after transformation.
- **System Integration & Testing**: Conducted system integration and UAT (User Acceptance Testing) to ensure data accuracy and reliability in the final output.
- **Data Visualization**: Developed an analytical dashboard using Tableau to visualize trends and patterns in permit issuance across New York City.
- **Graph Analysis**: Leveraged Neo4j for graph-based analysis, representing relationships between permits, locations, and personnel (e.g., owners, superintendents, permittees).

## Use Cases

The analysis enables insights such as:
- **Most Active Boroughs**: Identify which boroughs have the highest volume of permit issuances.
- **Common Work Types**: Analyze which types of construction work are most frequently permitted.
- **Permit Status Trends**: Monitor the distribution of permit statuses to track project completion rates or delays.

## Tech Stack

- **Database**: Neo4j for graph-based data relationships and analysis
- **Data Validation**: Great Expectations for ensuring data quality
- **Visualization**: Tableau for creating an interactive dashboard
- **Testing**: System integration and UAT to validate outputs

## Getting Started

To set up and run this project locally:

### Prerequisites

- **Neo4j** installed and running locally or accessible on a server.
- **Tableau** for dashboard creation and visualization.
- **Great Expectations** for data validation (install via `pip install great_expectations`).

### Setup Instructions

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/NYC-DOB-Permit-Issuance.git
   cd NYC-DOB-Permit-Issuance

2. **Data Preparation:
Download the DOB Permit Issuance dataset from the NYC Open Data Portal.
Run the scripts in scripts/ for data cleaning and transformation.

3. **Data Validation:
Use Great Expectations to validate data quality.
Run validation checks in data_validation/.

4. **Graph Database Setup:
Import data into Neo4j and run Cypher queries from the neo4j/ folder to create relationships and analyze data.

5. **Dashboard Visualization:
Load cleaned data into Tableau.
Use the tableau/ workbook to explore and interact with the data.

6. **Results & Insights
Explore trends in NYC’s construction activities with the analytical dashboard. Key insights include:

- The distribution of permit issuances by borough and work type.
- Patterns in permit status, indicating activity levels and possible delays.

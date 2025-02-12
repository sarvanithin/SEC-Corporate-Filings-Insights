# SEC-Corporate-Filings-Insights
# SEC Corporate Filings Analysis Project

## Overview
This project analyzes SEC Financial Statement Data Sets to extract insights about corporate financial health, reporting patterns, and executive networks. Using advanced data analytics and graph database technologies, the project demonstrates capabilities in processing and analyzing large-scale financial data.

## Technologies Used
- **Neo4j**: Graph database for storing and analyzing corporate relationships
- **Python**: Primary programming language
  - PySpark/Pandas: Data processing and analysis
  - Matplotlib: Data visualization
- **GraphRAG**: Natural language querying of financial data
- **Google Colab**: Development environment
- **yfiles_jupyter_graphs_for_neo4j**: Graph visualization

## Data Source
- SEC Financial Statement Data Set (2013-2023)
- Dataset components:
  - Submission Data Set (SUB): XBRL submission records
  - Number Data Set (NUM): Numeric values from financial statements
  - Tag Data Set (TAG): Metadata about submission tags
  - Presentation Data Set (PRE): Financial statement structure information

## Key Features

### 1. Financial Statement Analysis
- Comparative analysis of company financial statements
- Performance benchmarking across different companies
- Trend analysis of key financial metrics

### 2. Financial Health Clustering
- Company clustering based on revenue and debt metrics
- Identification of financially healthy vs. at-risk companies
- Pattern recognition in financial performance

### 3. Anomaly Detection
- Identification of unusual reporting patterns
- Analysis of significant deviations from historical data
- Potential fraud or misrepresentation detection

### 4. Corporate Network Analysis
- Mapping of executive and board member connections
- Centrality analysis of corporate networks
- Integration of Form 8-K and 10-K data for relationship mapping

### 5. Natural Language Querying
- Implementation of GraphRAG for conversational financial queries
- Generation of financial reports from natural language input
- Trend and metric analysis through simple English queries

## Technical Implementation

### Database Setup
```python
# Neo4j Aura configuration with limitations:
# - 200,000 Node limit
# - 400,000 Relationship limit
```

### Data Processing Pipeline
1. Data loading from SEC sources
2. Preprocessing and cleaning
3. Graph database ingestion
4. Analysis and visualization
5. Natural language query processing

## Results and Insights
- Financial health patterns across companies
- Network centrality metrics for corporate relationships
- Anomaly detection findings
- Comparative financial performance metrics

## Future Enhancements
- Real-time data integration
- Advanced machine learning models for prediction
- Enhanced visualization capabilities
- Expanded network analysis features

## Setup Instructions

1. Clone the repository
2. Set up Neo4j Aura account
3. Configure Google Colab environment
4. Install required Python packages
5. Load data into Neo4j
6. Run analysis notebooks

## Usage

```python
# Example query using GraphRAG
query = "Show me companies with increasing revenue trends in the tech sector"
```

## Dependencies
- Neo4j Aura account
- Google Drive (for data storage)
- Python 3.x
- Required Python packages listed in requirements.txt

## Notes
- Free tier limitations in Neo4j Aura should be considered when loading data
- Data should be filtered based on analysis requirements
- Regular updates may be needed as new SEC filings are released


## Acknowledgments
- Project completed as part of the Introduction to Big Data and Analytics course at George Washington University
- SEC for providing the financial statement dataset
- Neo4j for the graph database platform

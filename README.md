# US Consumer Financial Complaints Analysis

An end-to-end data analytics portfolio project using the **CFPB Consumer Complaint Database**. The project will explore consumer complaints submitted about financial products and services in the United States.

> **Project status:** In progress

## Project goals

- Collect and inspect publicly available CFPB complaint data.
- Clean, validate, and prepare data with Python, Pandas, and NumPy.
- Explore complaint trends by product, issue, company, geography, and time.
- Answer business questions using SQL Server.
- Build an interactive Power BI report with a documented data model and measures.
- Communicate findings and limitations clearly.

## Technology stack

| Area | Tools |
|---|---|
| Data preparation | Python, Pandas, NumPy |
| Database and analysis | Microsoft SQL Server |
| Visualization | Power BI |
| Version control and documentation | Git, GitHub, Markdown |

## Data source

- **CFPB Consumer Complaint Database:** https://www.consumerfinance.gov/data-research/consumer-complaints/
- **Data download and API information:** https://www.consumerfinance.gov/data-research/consumer-complaints/

The CFPB publishes complaints after sending them to companies for response, subject to its publication process. Complaint data is not a statistically representative sample of all consumers or all experiences. Complaint counts should not be interpreted as company failure rates or used to compare companies without appropriate market-size and exposure context.

## Planned repository structure

```text
data/
  raw/          # Local source files; large raw data is not committed to Git
  processed/    # Cleaned and transformed outputs
  sample/       # Small, non-sensitive sample files for reproducibility
notebooks/      # Step-by-step exploration and analysis notebooks
python/         # Reusable Python scripts
sql/            # SQL Server schema, loading scripts, and analysis queries
powerbi/        # Power BI report files and supporting assets
reports/        # Findings, charts, and project outputs
documentation/  # Data dictionary, methodology, and project notes
```

## Data handling

The full source CSV is large and is intentionally kept outside GitHub. It will be processed locally, using memory-conscious techniques such as chunked reading where appropriate. Only code, documentation, and small illustrative samples will be version-controlled.

## Current progress

- [x] Create public GitHub repository
- [x] Set up initial project structure
- [ ] Document dataset fields and scope
- [ ] Inspect raw data and validate file structure
- [ ] Clean and prepare data with Python
- [ ] Perform exploratory data analysis
- [ ] Load curated data into SQL Server
- [ ] Build Power BI data model and dashboard
- [ ] Document insights, limitations, and recommendations

## Disclaimer

This is an independent learning and portfolio project using publicly available data. It is not affiliated with or endorsed by the Consumer Financial Protection Bureau (CFPB).

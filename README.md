# **nova-heat**

## Urban Heat Index Analysis Pipeline
An end to end data engineering pipeline built on **Databricks Lakehouse** architecture to analyze and predict heat stress zones in an area.

### Architecture
- **Bronze:** Raw data ingestion from IMD/OpenWeather via Spark Auto Loader simulation.
- **Silver:** Data cleaning, outlier removal, and 
- **Gold:** Aggregated heat metrics by zones for dashboarding.
- **ML:** Linear Regression model to predict UHI trends.

### Tech Stack
- **Language:** Python (PySpark), SQL
- **Platform:** Databricks
- **Storage:** Delta Lake
- **Tracking MLflow**
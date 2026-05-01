# Orders Analytics Pipeline

Production-grade data engineering pipeline with Bronze-Silver-Gold architecture.

## Features
- Automated deployment via GitHub Actions
- Environment-based configuration (dev, preprod, prod)
- Delta Lake tables with Unity Catalog
- Star schema analytics (10,000+ orders)

## Architecture
- Bronze: Raw data ingestion
- Silver: Data cleaning & validation
- Gold: Star schema (DimCustomers, DimProducts, DimRegion, FactOrders)

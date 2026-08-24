# azure-databricks-realtime-health-platform
End-to-end real-time health data platform built with Azure Databricks, Kafka, ADLS Gen2, Unity Catalog, Medallion Architecture, CDC, streaming, testing and CI/CD.
# Azure Databricks Real-Time Health Platform

End-to-end Data Engineering project built with Azure Databricks.

## Architecture
- Azure Data Lake Storage Gen2
- Azure Databricks
- Unity Catalog
- Kafka
- Medallion Architecture
- Bronze / Silver / Gold
- Batch and Streaming
- CDC
- CI/CD
- Integration Testing

## Project Goal
Build a real-time health data platform for wearable devices.

The platform ingests:
- Device registration data
- User profile CDC events
- Heart-rate BPM streams
- Gym login/logout events
- Workout session events

## Gold Layer Outputs
- Workout BPM Summary
- Gym Summary

# SleepCare — Clinical AI Platform for CPAP Patient Monitoring

> ⚠️ Code is private — academic-industrial partnership  
> DISP Lab (Université Lyon 2) × Linde Homecare France

## Overview
Clinical platform for remote monitoring and therapeutic follow-up  
of sleep apnea patients. Integrates data from multiple medical devices,  
computes ML-based risk scores, and enables medical teams to prioritize  
interventions.

**International demo: Berlin, June 2026**

## My Role — Backend & Data Engineering Intern (5 months)
- Designed and built full REST API backend — 32 endpoints across 3 portals (Physician · Technician · Patient)
- Architected 3-database schema (19 tables) with strict GDPR data separation
- Built multi-source data ingestion pipelines from 6 medical devices
- Integrated ML models for patient risk scoring and dropout prediction
- Developed automated alert engine (SMS · video coaching · technician visit)
- Migrated infrastructure from PostgreSQL to SQL Server 2025
- Set up CI/CD pipeline with Docker and GitHub Actions
- Coordinated API contracts with ML, frontend, and infrastructure teams

## Tech Stack
| Layer | Technology |
|---|---|
| Backend | Python · FastAPI · SQLAlchemy 2.0 |
| Database | SQL Server 2025 · PostgreSQL · SQLite |
| Auth | JWT · OAuth2 · RBAC |
| Data Sources | Linde CPAP · Withings · Masimo · Hexoskin · Somno-Art |
| ETL | Pentaho Data Integration |
| DevOps | Docker · GitHub Actions · CI/CD |
| API | REST · OpenAPI · Postman |

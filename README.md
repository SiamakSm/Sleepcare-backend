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
- Designed and built full REST API backend — 35 endpoints across 3 portals (Physician · Technician · Patient)
- Architected 3-database schema (20 tables) with strict GDPR data separation
- Built multi-source data ingestion pipelines from 6 medical devices (CPAP · Withings · Masimo · Hexoskin · Somno-Art)
- Integrated ML models for patient risk scoring and dropout prediction
- Developed automated alert engine with clinician override gate (SMS · video coaching · technician visit)
- Implemented JWT authentication with role-based access control across all endpoints
- Migrated infrastructure from PostgreSQL to SQL Server 2025 on-premise
- Coordinated API contracts with ML, frontend, and infrastructure teams

## Tech Stack
| Layer | Technology |
|---|---|
| Backend | Python 3.14 · FastAPI · SQLAlchemy 2.0 |
| Database | SQL Server 2025 · PostgreSQL |
| Auth | JWT · RBAC (3 roles) |
| Data Sources | Linde CPAP · Withings · Masimo · Hexoskin · Somno-Art |
| ETL | Pentaho Data Integration |
| DevOps | Docker · CI/CD |
| API | REST · OpenAPI · Postman |

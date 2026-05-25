# System Architecture

# Overview

The system collects marketing data from multiple platforms using APIs and displays unified insights through a centralized dashboard.

---

# Architecture Flow

Marketing Platforms
↓
API Connectors
↓
Data Processing Layer
↓
Central Database
↓
Dashboard UI
↓
Analyst/User

---

# Data Sources

- Google Ads API
- Meta Ads API
- LinkedIn Ads API
- Google Analytics 4

---

# Backend Responsibilities

- Fetch marketing data
- Normalize metrics
- Handle API failures
- Generate summary insights
- Serve dashboard data

---

# Frontend Responsibilities

- Display dashboards
- Show KPIs
- Provide filtering
- Export reports

---

# Database Responsibilities

- Store normalized marketing data
- Maintain historical records
- Support reporting queries

---

# Suggested Tech Stack

Frontend:
- React

Backend:
- Python FastAPI

Database:
- BigQuery or PostgreSQL

Cloud:
- Google Cloud Platform

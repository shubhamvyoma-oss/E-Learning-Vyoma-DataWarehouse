# E-Learning-Vyoma-DataWarehouse
## Welcome

This repository contains the complete data warehouse pipeline for **E-Learning Vyoma** (sanskritfromhome.org), built on the **Medallion Architecture** (Bronze → Silver → Gold).

The pipeline ingests data from the **Edmingle LMS platform** via webhooks and REST APIs, stores it in **PostgreSQL**, and serves **Power BI dashboards** for student retention analysis and attendance tracking.

---

## Project Overview

| Property | Detail |
|---|---|
| Organisation | Vyoma Samskrta Pathasala |
| Platform | Edmingle LMS |
| Architecture | Medallion Architecture — Bronze → Silver → Gold |
| Database | PostgreSQL (`edmingle_api_data`) |
| Data Sources | Edmingle Webhooks (16 events) + REST API |
| BI Tool | Power BI (live PostgreSQL connection) |
| Language | Python + SQL |

---

## Architecture

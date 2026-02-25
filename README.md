# Data Engineering & Governance Pipeline

Automated data governance tools for enterprise data lakes.

## 🎯 What This Does

Helps companies understand what's in their data and who's accessing it:
- Detects PII (emails, credit cards, personal info)
- Finds unauthorized AI usage (Shadow AI)
- Validates data quality (data contracts)
- Tracks where data comes from and goes

## 🛠️ Tech Stack

- Python, Presidio, spaCy (PII detection)
- dbt, Great Expectations (data quality)
- Apache Airflow (orchestration)
- PostgreSQL (metadata storage)

## 💡 Why I Built This

At Purplescape, I analyzed sales datasets for enterprise clients and built analytics dashboards that increased profitability by 30%. This project extends that experience to automated data governance - a critical need for enterprises handling sensitive customer data.

## 📊 Project Status

**Day 1** - Setting up infrastructure and PII detection scanner

### Roadmap
- [x] Project setup
- [ ] Basic PII detection
- [ ] Australian PII patterns (Medicare, TFN)
- [ ] Shadow AI detection
- [ ] Data contracts with dbt
- [ ] Data lineage tracking
- [ ] Airflow orchestration
- [ ] Dashboard

## 🚀 Coming Soon

Installation and usage instructions once the scanner is working.
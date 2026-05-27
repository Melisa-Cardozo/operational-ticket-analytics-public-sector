# Operational Ticket Analytics – Public Sector Case Study

## Project Overview

This project presents an operational analytics case study developed from a real-world collaboration with a public sector digital services organization in Tierra del Fuego, Argentina.

The objective was to analyze operational performance within a citizen ticket management system, focusing on:

- ticket volume
- response efficiency
- resolution times
- backlog behavior
- operational workload distribution across categories
- service performance trends over time

The analysis combined data cleaning, exploratory data analysis (EDA), KPI generation and operational performance analysis using Python.

---

## Business Problem

Public service organizations process a large volume of citizen requests every day.

Understanding how tickets are distributed, resolved and accumulated over time is critical to:

- monitor operational performance
- identify service bottlenecks
- improve workload allocation
- support decision-making with data

This project explored ticket behavior using operational data extracted from the internal management platform.

---

## Dataset

The project was based on anonymized JSON exports from a ticket management system.

The original data included:

- Tickets metadata
- Categories information
- Internal notes
- Users and agents information
- Customer-related records

Due to privacy and confidentiality considerations, the raw datasets are not publicly available in this repository.

Only anonymized methodology, aggregated KPIs and selected visualizations are included.

---

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook / Google Colab

---

## Main Analysis Performed

### Data Preparation
- JSON data loading
- Data validation
- Missing values analysis
- Datetime conversion
- Operational metric creation

---

### KPI Summary
Main indicators calculated:

- Total tickets processed
- Closed vs open tickets
- Resolution rate
- Median resolution time
- Median first response time

---

### Operational Analysis
Main analytical views included:

- Ticket volume by category
- Resolution time distribution
- Backlog analysis
- Monthly operational evolution

---

### Focus Case Analysis
Specific category-level analysis was performed for:

- **Haberes**
- **SUNA & GEN**

These categories were selected due to their operational relevance and stakeholder interest during the project.

---

## Key Findings

### High operational volume with strong closure performance
More than **40,000 tickets** were processed with an overall resolution rate above **96%**.

---

### Workload concentrated in a small number of categories
A limited number of categories generated most of the operational demand, especially:

- Mesa de Ayuda AIF
- Sistema SUNA

---

### Backlog concentration in selected operational areas
Unresolved workload accumulated mainly in specific categories, highlighting possible operational bottlenecks.

---

### Strong differences in resolution times across categories
Operational cycles varied significantly depending on category complexity and workflow type.

---

### Operational demand evolved with organizational change
Monthly ticket evolution reflected changes in platform adoption, onboarding of users and stabilization of operational demand over time.

---

## Repository Structure

```bash
├── README.md
├── operational-ticket-analytics-public-sector.ipynb
└── images/
```

---

## Project Outcome

This project demonstrates how operational service data can be transformed into actionable insights for:

- performance monitoring
- service optimization
- operational reporting
- evidence-based decision-making

It also reflects a real-world end-to-end analytics workflow, from raw data preparation to business insights communication.

---

## Author

**Melisa Cardozo**

Economist | MSc Data Science 
Data Analytics • Operational Analytics • AgTech • Sustainability

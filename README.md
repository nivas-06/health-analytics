# Health Insurance Analytics Dashboard

An interactive Health Insurance Analytics Dashboard built using Microsoft Power BI to analyse policyholder demographics, insurance premiums, claims distribution, insurer performance, and regional insurance trends.

## Project Overview

The Health Insurance Analytics Dashboard transforms insurance data into meaningful business insights through interactive visualisations and key performance indicators.

The project focuses on understanding policyholder distribution, premium revenue, claim amounts, claim statuses, and insurance policy performance across different states, insurers, and policy types.

The dashboard uses a synthetic Indian health insurance dataset containing 500 records, designed for academic and analytical demonstration purposes.

## Tech Stack

| Component | Technology |
|---|---|
| Business Intelligence | Microsoft Power BI |
| Data Processing | Power Query |
| Data Modelling | Power BI Data Model |
| Calculations | DAX |
| Dataset Format | CSV / Excel |

## Dataset Description

The project uses a synthetic health insurance dataset containing 500 records and 20 columns.

The dataset includes information related to:

- Policyholder details
- Indian names and locations
- Insurance providers
- Policy types
- Annual premiums in INR
- Sum insured amounts
- Pre-existing medical conditions
- Claim amounts
- Hospital and diagnosis categories
- Claim status

**Note:** The dataset is artificially generated and does not contain actual policyholder records or represent real-world insurance statistics.

## Repository Structure

```text
Health-Insurance-Analytics/
│
├── 01_Raw_Data/
│   └── Indian_Health_Insurance_Sample_Dataset.csv
│
├── 02_Cleaned_Data/
│   └── (Cleaned dataset, if applicable)
│
├── 03_PowerBI_Dashboard/
│   └── Health_Insurance_Analytics_Final.pbix
│
├── Screenshots/
│   └── Dashboard screenshots
│
└── README.md
```

## Dashboard Features

### 1. Insurance Overview

Provides a high-level summary of insurance performance through key metrics and visualisations.

- Total Policyholders
- Total Premium
- Total Claims
- Average Premium
- Claims Filed
- Premium Revenue by Insurer
- Claims Distribution by Status
- Policyholders by State
- Premium Revenue by Policy Type

### 2. Interactive Filtering

The dashboard includes interactive slicers that allow users to explore insurance data based on:

- State
- Insurance Provider
- Policy Type

These filters enable dynamic analysis of policyholders, premiums, and claims.

### 3. Claims Analysis

Analyses insurance claims based on their status, including:

- Approved
- Rejected
- Under Review

Provides insights into claim distribution and the overall claims landscape within the dataset.

### 4. Insurance Provider Analysis

Compares premium revenue across different insurance providers to identify differences in premium contribution.

## Key Performance Indicators (KPIs)

| KPI | Description |
|---|---|
| Total Policyholders | Distinct number of policyholders |
| Total Premium | Sum of annual insurance premiums |
| Total Claims | Total claim amount |
| Average Premium | Average annual insurance premium |
| Claims Filed | Number of records with a filed claim |

## Data Preparation

The data preparation workflow includes:

1. Generating a synthetic Indian health insurance dataset.
2. Importing the dataset into Power BI.
3. Inspecting and validating the dataset.
4. Preparing data types and columns.
5. Creating DAX measures for analytical calculations.
6. Designing interactive visualisations and KPI cards.
7. Applying consistent formatting and dashboard styling.

## How to Run

### Prerequisites

- Microsoft Power BI Desktop

### Steps

1. Clone this repository.
2. Navigate to `03_PowerBI_Dashboard`.
3. Open `Health_Insurance_Analytics_Final.pbix` using Power BI Desktop.
4. Configure the data source if required.
5. Refresh the dataset to explore the dashboard.

## Project Objectives

- Analyse health insurance policyholder distribution.
- Understand premium revenue across insurance providers.
- Evaluate claim amounts and claim statuses.
- Compare insurance performance across states.
- Identify premium distribution across different policy types.
- Build an interactive business intelligence dashboard for insurance data analysis.

## Data Disclaimer

This project uses entirely synthetic data generated for educational and demonstration purposes. The dataset does not represent actual insurance companies, policyholders, medical records, claims, or industry statistics.

All names, providers, and figures are illustrative.

## Author

**Nivas I**

BE Computer Science and Engineering

KCG College of Technology

---

*Health Insurance Analytics Dashboard — Turning Insurance Data into Meaningful Insights.*

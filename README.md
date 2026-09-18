# AI-Powered Healthcare Support Intelligence

## Business Problem
The 2025 year-end report showed that diabetes spending increased by 20% compared with 2024. However, the report did not explain whether the increase was caused by inpatient, outpatient, or professional claims. The organization needs to identify high-cost claimants and understand which members contributed most to the increase.

## Key Business Questions
1. How did total diabetes-related spending change between 2024 and 2025?
2. Was the increase driven primarily by inpatient, outpatient, or professional claims?
3. List members who contributed to the increase the most?
4. How was the increase distributed among high-claimants?
5. Which diagnoses, procedures, or places of service generated the additional spending?
6. Which members are most likely to become high-cost diabetes claimants in 2026?

## Project Architecture
This project combines historical data from 2024 and 2025 to identify the members and services that contributed to the increase in diabetes-related spending and predict which members may become high-cost claimants in 2026.
```mermaid
flowchart TD
    A["Member Eligibility"] --> G["SQL Data Preparation"]
    B["Medical Claims"] --> G
    C["Diagnosis Reference"] --> G
    D["Procedure Reference"] --> G
    E["Place of Service Reference"] --> G
    F["Provider Reference"] --> G

    G --> H["Validated Diabetes Claims Dataset"]

    H --> I["Historical Cost Driver Analysis"]
    H --> J["Member Level Feature Engineering"]

    I --> K["Cost Drivers and High Cost Claimants"]
    K --> O["Power BI Dashboard and Recommendations"]

    J --> L["Predictive Model Training"]
    L --> M["Model Evaluation"]
    M --> N["2026 High Cost Risk Scores"]
    N --> O
```
## Dataset

## Data Model

## SQL Data Preparation

## Historical Cost-Driver Analysis

## Member-Level Feature Engineering

## Predictive Modeling

## Model Evaluation

## Power BI Dashboard

## Findings and Recommendations

## Limitations and Responsible AI

# Healthcare Operations: Appointment Wait Time Analysis

## Overview
This project analyzes appointment wait times across hospital departments to identify operational bottlenecks and opportunities for improvement. Using a realistic synthetic dataset, the analysis focuses on how staffing levels, time of day, and wait duration impact delays and appointment cancellations.

## Objectives
- Identify departments with the longest average wait times
- Examine how wait times vary by time of day
- Analyze the relationship between long waits and appointment cancellations
- Provide data-driven operational recommendations without increasing costs

## Dataset
- **Type:** Synthetic (realistic, non-sensitive)
- **Size:** 6,000 appointment records
- **Key Features:**
  - Department
  - Scheduled hour
  - Staff on shift
  - Wait time (minutes)
  - Time block (Morning / Afternoon / Evening)
  - Appointment status (Completed / Cancelled)

The dataset was intentionally generated to reflect realistic hospital behavior while avoiding privacy or compliance risks.

## Methodology
- Data generation and analysis performed in **Python**
- Libraries used: `pandas`, `numpy`, `matplotlib`
- Validation checks ensured:
  - Realistic value ranges
  - Higher wait times in emergency services
  - Increased cancellation likelihood for long waits

## Key Findings
- Emergency services experience the highest average wait times
- Afternoon periods show increased congestion
- Higher staffing levels are associated with lower wait times
- Appointments with waits longer than 45 minutes are significantly more likely to be cancelled

## Recommendations
- Reallocate staff toward afternoon peak hours
- Prioritize staffing adjustments in emergency services
- Introduce soft scheduling buffers to reduce long waits
- Optimize existing resources without increasing operational costs

## Files
- `main.py` – Data generation, validation, and analysis
- `data/` – Synthetic dataset (CSV)
- `visuals/` – Generated charts and figures

## Tools
Python · Pandas · NumPy · Matplotlib

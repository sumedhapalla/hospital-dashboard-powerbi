# Hospital Dashboard Project

A comprehensive data analysis and visualization dashboard for hospital operations and patient care metrics.

## Overview

This project analyzes key hospital performance indicators including patient demographics, admissions, billing, outcomes, and doctor utilization. It provides actionable insights through data visualizations and statistical metrics.

## Project Structure

```
├── hospital_dashboard.ipynb    # Main analysis notebook
├── patients.csv                # Patient demographic data
├── admissions.csv              # Hospital admission records
├── doctors.csv                 # Doctor availability and utilization
├── billing.csv                 # Patient billing information
├── outcomes.csv                # Patient outcome and readmission data
└── README.md                   # This file
```

## Data Files

- **patients.csv**: Contains patient ID, age, gender, insurance type, and hospital branch
- **admissions.csv**: Admission ID, patient ID, department, admission/discharge dates, and emergency status
- **doctors.csv**: Doctor ID, department, available hours, and booked hours
- **billing.csv**: Billing information including room, procedure, and medicine costs
- **outcomes.csv**: Patient outcome status and readmission information

## Key Metrics Analyzed

- **Average Length of Stay (ALOS)**: Mean duration of patient hospitalization
- **Readmission Rate**: Percentage of patients requiring readmission
- **Doctor Utilization Rate**: Percentage of available hours booked by doctors
- **Admissions by Department**: Distribution of admissions across hospital departments
- **Emergency vs Non-Emergency Admissions**: Breakdown of emergency cases

## Visualizations

The dashboard includes the following charts:
- Admissions count by department
- Average length of stay by department
- Emergency admissions pie chart

## Requirements

- Python 3.x
- pandas
- matplotlib
- seaborn

## Installation

Install required packages:
```bash
pip install pandas matplotlib seaborn
```

## Usage

Open and run the `hospital_dashboard.ipynb` notebook in a Jupyter environment to execute the analysis and view the visualizations.

## Features

- Data loading and preprocessing
- Statistical analysis of hospital metrics
- Department-wise performance analysis
- Doctor utilization tracking
- Patient outcome analysis
- Interactive visualizations with seaborn and matplotlib

## Author

Hospital Analytics Team

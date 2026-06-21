# Fleet Airworthiness Planning Dashboard

## Overview

The Fleet Airworthiness Planning Dashboard is an Excel-based CAMO (Continuing Airworthiness Management Organisation) planning tool developed to support aircraft maintenance forecasting and airworthiness monitoring.

This project began as a maintenance forecasting system based on Flight Hours (FH) and Flight Cycles (FC) and has since been expanded into a fleet-level planning dashboard with maintenance prioritization, KPI monitoring, and governing limit determination.

The objective is to simulate real-world CAMO planning activities by providing maintenance forecasts, due-date calculations, aircraft prioritization, and management-level fleet visibility.

---

## Features

### Maintenance Forecasting

* Flight Hour (FH) based maintenance forecasting
* Flight Cycle (FC) based maintenance forecasting
* Remaining life calculations
* Estimated days remaining calculations
* Forecast maintenance due dates

### Maintenance Prioritization

Aircraft are automatically classified into:

* Normal
* Plan
* Urgent
* AOG Risk

based on remaining maintenance life and forecasted due dates.

### Aircraft Master Consolidation

The Aircraft Master module consolidates:

* FH maintenance status
* FC maintenance status
* Overall aircraft priority
* Governing maintenance driver

The most restrictive maintenance limit automatically determines the aircraft's overall status.

### Fleet KPI Dashboard

The dashboard provides a fleet-level overview including:

* Fleet Size
* Aircraft Due Within 30 Days
* Urgent Checks
* AOG Risks
* Priority Distribution
* Remaining FH Visualization

### Governing Driver Logic

The system identifies whether an aircraft's maintenance requirement is driven by:

* Flight Hours (FH)
* Flight Cycles (FC)

allowing planners to quickly identify the controlling maintenance parameter.

---

## Dashboard Preview

### Fleet Airworthiness Planning Dashboard

* KPI Cards
* Priority Distribution Chart
* Aircraft Master Summary
* Remaining FH Analysis
* Maintenance Priority Monitoring

---

## Project Structure

```text
Fleet Airworthiness Planning Dashboard
│
├── Aircraft Master
├── FH Maintenance Forecasting
├── FC Maintenance Forecasting
├── Fleet KPI Dashboard
├── Priority Classification Logic
├── Governing Driver Determination
└── Auto Forecast Calculations
```

---

## Technologies Used

* Microsoft Excel
* Excel Tables
* Structured References
* XLOOKUP
* COUNTIF
* IF / IFS Logic
* Conditional Formatting
* Dashboard Design
* Data Visualization

---

## CAMO Applications

This project demonstrates practical concepts used within Continuing Airworthiness Management, including:

* Maintenance Planning
* Maintenance Forecasting
* Fleet Monitoring
* Airworthiness Status Tracking
* Maintenance Prioritization
* Fleet-Level Decision Support

---

## Future Enhancements

Planned future upgrades include:

* Component Life Tracking
* Maintenance Cost Forecasting
* Aircraft Utilization Trend Analysis
* Power BI Integration
* VBA Automation
* Python/Pandas Version
* Automated Maintenance Reporting

---

##Added Fleet Airworthiness Planning Dashboard (v2.0)

- Added KPI cards
- Added Aircraft Master sheet
- Added Overall Priority calculation
- Added Governing Driver logic
- Added FH visualization charts
- Improved CAMO planning workflow
---

## Author

Faraz Ahmed

Aeronautical Engineering Student

Focused on CAMO, Maintenance Planning, and Aviation Data Analytics.

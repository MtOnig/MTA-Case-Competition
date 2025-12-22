# General Dataset Overview

**Unit of observation:** Race-, driver-, and lap-level Formula 1 performance data  

**Competition:** Formula 1 World Championship  

**Scope:**  
- Drivers  
- Constructors  
- Race results  
- Qualifying results  
- Race schedules  
- Driver pricing data  

Temporal coverage: Multiple F1 seasons (as provided in source datasets)

---

### Intended Use

These datasets serve as the **raw input layer** for the project’s data pipeline and are used to:

- construct cleaned and analysis-ready datasets  
- generate race and driver-level performance metrics  
- support downstream modelling, ranking, and visualization  
- feed Power BI dashboards and analytical summaries  

This folder represents the foundational data source for all subsequent analysis in the project.

---

## Datasets

### 1. `Drivers.csv`

Contains driver-level reference information.

Includes:
- Driver identifiers  
- Driver names  
- Nationality and biographical metadata  

Used as the primary lookup table for merging performance, results, and pricing data.
---

### 2. `Constructors.csv`

Contains constructor (team) reference information.

Includes:
- Constructor identifiers  
- Team names  
- Nationality  

Used to associate drivers with teams across races and seasons.

---

### 3. `RaceSchedule.csv`

Contains race calendar and event metadata.

Includes:
- Race identifiers  
- Season and round information  
- Circuit and race date  

Used to structure time-series analysis and season-level aggregation.

---

### 4. `RaceResult.csv`

Contains final race classification data.

Includes:
- Driver and constructor identifiers  
- Grid position  
- Finishing position  
- Points scored  
- Race status (finished, DNF, etc.)

Used to evaluate race-level performance and outcomes.

---

### 5. `QualificationResult.csv`

Contains qualifying session results.

Includes:
- Driver identifiers  
- Qualifying position  
- Session times (Q1, Q2, Q3 where applicable)

Used to assess qualifying performance and starting-grid advantages.

---

### 6. `DriverPrice.csv`

Contains driver pricing and valuation information.

Includes:
- Driver identifiers  
- Price or cost-related metrics  

Used to support cost-efficiency and value-based comparisons between drivers.

---

## Notes

- All files in this folder represent raw data as obtained from source datasets  
- Minor inconsistencies (naming, formatting, duplicates) are corrected in downstream processing steps  
- Cleaned and transformed versions of these datasets are used for modelling and visualization but are not stored here to preserve a clear raw-data boundary  
- Provided for academic and portfolio purposes only  



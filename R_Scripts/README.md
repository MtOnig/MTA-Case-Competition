# RMarkdown Analysis file

This RMarkdown file contains the **core quantitative analysis** for the **MTA Case Competition**.  
It implements the project’s scoring, aggregation, and modeling logic and produces all analytical outputs used in the final case submission.

---

## File overview

### `MTA Case Competition.Rmd`

End-to-end analytical notebook used to:
- Construct race-level driver performance metrics
- Aggregate driver outcomes across races
- Compute value-based performance scores
- Estimate fixed-effects models
- Export analysis-ready datasets

---

## Scope of Analysis

The notebook performs the following tasks:

- Applies a custom race-level points framework
- Computes driver-level summary statistics (expected performance and variability)
- Normalizes performance metrics by driver price
- Estimates driver fixed effects while controlling for team and event factors
- Generates tabular outputs for reporting and visualization

This file documents the full computational workflow used in the analysis.

---

## Outputs

The notebook exports multiple `.csv` files, including:
- Race-level performance calculations
- Driver-level performance summaries
- Value-based scoring metrics
- Driver fixed-effects estimates

These outputs are used directly in the final written submission and supporting visuals.

---

## Role in the Project

This RMarkdown file serves as the **analytical backbone** of the MTA Case Competition project.  
It centralizes all data processing, scoring, and modeling steps and ensures reproducibility of the project’s quantitative results.


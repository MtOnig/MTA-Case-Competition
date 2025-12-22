# Power BI – Driver Performance & Value Analysis Dashboard
This folder contains an interactive Power BI dashboard developed to visualize, compare, and evaluate Formula 1 driver performance relative to a standardized baseline. The dashboard integrates expected performance, cost efficiency, and composite scoring to support data-driven driver valuation and comparison.

# Dashboard Overview
The dashboard is organized into three connected views that guide the user from league-wide exploration to individual driver analysis:

1. Landing Page (League Overview)
Presents a league-wide view of all drivers and allows users to select one or multiple drivers directly for comparison.

3. Driver Drill-Down Page (Individual Analysis)
Presents a detailed breakdown of a selected driver’s performance, including Year trends, round-level point contributions, and performance volatility.

# Dashboard Structure

## Landing Page – League Overview
The landing page serves as the primary interaction point and is designed for rapid exploration and comparison.

Key visuals include:

* Points above baseline average by driver, highlighting over- and under-performers
* Position relative to baseline average, ranking drivers ordinally
* Expected points vs cost, enabling value-for-money assessment
* Composite performance score by driver, summarizing multi-dimensional performance

Users can select one or multiple drivers directly from this page to compare metrics across all visuals.

# Driver Drill-Down Page – Individual Performance Analysis
The drill-down page provides a detailed, driver-specific view focused on performance consistency and point generation.

Key components include:

* Summary metrics (cost, expected points, score, standard deviation, points above baseline)
* Total points by round and year
* Breakdown of points by round, decomposed into:
  * Status points
  * Position points
  * Positions gained
  * Qualification points
This page contextualizes the summary rankings observed in the landing and comparison views.

# Purpose

The Power BI dashboard is designed to complement the econometric and scoring analyses presented in the main report. While the regression models establish statistical baselines and residual-based insights, the dashboard focuses on interpretability, comparison, and decision support.

The visuals do not replace the underlying econometric framework; rather, they provide transparency into performance drivers and enable exploratory analysis.

# File Information
* F1_Driver_Performance_Dashboard.pbix
Power BI Desktop file containing all visuals, measures, calculated fields, and interactive functionality.

# Usage Notes

To view the dashboard, open the .pbix file using Power BI Desktop.
Methodological details, variable definitions, and data construction steps are documented in the accompanying report and data sections of this repository.

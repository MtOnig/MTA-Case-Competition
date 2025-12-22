# Formula 1 Driver Cost–Performance Analysis
## MTA Data Series Case Competition

A data-driven sports analytics project that evaluates Formula 1 driver performance relative to cost and recommends an optimal hiring strategy that maximizes expected points per dollar spent.

This project simulates a real-world consulting and decision-making problem, combining predictive modeling, cost-efficiency analysis, and strategic reasoning under uncertainty.

## Project Summary
This project evaluates Formula 1 driver performance relative to cost to support efficient data-driven driver selection decisions.

Using historical race and qualifying data, we developed a statistical framework to:

* Estimate expected points per driver under official scoring rules
* Benchmark drivers against a baseline average
* Quantify points above baseline, consistency, and variability
* Compare performance outputs directly against fixed driver costs

The analysis is implemented through:

* A reproducible RMarkdown pipeline for scoring and benchmarking
* An interactive Power BI dashboard designed for driver comparison and decision support

Rather than selecting drivers purely on raw performance, this approach emphasizes value efficiency, allowing decision-makers to identify drivers who deliver strong results relative to their cost.

## Individual Contributions
My work focused on the core analytical and decision-support components of the project, including:
- Building the RMarkdown analysis pipeline used to compute:
  - Expected points per driver
  - Baseline performance benchmarks
  - Points above baseline and relative rankings
  - Driver-level variability and consistency metrics
- Designing the composite driver score used to evaluate cost–performance tradeoffs
- Developing the Power BI dashboard, including:
  - Expected points vs. cost comparisons
  - Driver rankings and baseline positioning and comparison
  - Drill-down driver profiles with season-level and round-level breakdowns
- Translating raw race results into interpretable metrics that directly support hiring decisions

## Personal report and reflection
The full written analysis, including:
- methodology and modeling decisions
- interpretation of results
- limitations of the data and approach
- reflections on what could be improved in future iterations
is available here:

➡️ **[MTA Driver Recommendation Report (PDF)](./Final_Report_and_Reflection.pdf)**

This reflection focuses on both the technical challenges (data quality, modeling assumptions, variance in race outcomes) and the strategic lessons learned when translating statistical analysis into real-world decision-making.

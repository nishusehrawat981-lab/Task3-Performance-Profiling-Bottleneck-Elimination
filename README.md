# Task 3 - Performance Profiling & Bottleneck Elimination

## Objective

This project analyses system performance from the user's perspective.

The main goal is to understand whether latency and errors are associated with conversion and abandonment, quantify potential revenue impact, and identify where performance improvements deserve engineering effort.

## Key Metrics

- Latency
- Error rate
- Conversion rate
- Abandonment rate
- Revenue impact
- Performance by page or application step

## Analysis Approach

1. Load real production performance data.
2. Clean timestamps and missing values.
3. Check duplicate and invalid records.
4. Analyse latency distributions.
5. Analyse errors by step.
6. Compare latency groups with conversion and abandonment.
7. Quantify revenue exposure using a clearly defined baseline.
8. Prioritize performance bottlenecks.
9. Document data sources and assumptions.
10. Validate findings before making causal claims.

## Important Principle

Correlation between latency and conversion does not automatically prove that latency caused the conversion change.

Any causal performance claim should be validated using an appropriate experiment or controlled analysis.

## Data

The CSV template contains the required fields for the analysis.

Real production data should be inserted before final measured results are reported.

## Expected Output

The final analysis should identify:

- Major latency bottlenecks
- Important error points
- Conversion/abandonment relationships
- Revenue exposure
- Recommended engineering priorities

## Tools

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab

## Conclusion

Performance should be prioritized using measurable user impact and financial impact rather than latency alone.

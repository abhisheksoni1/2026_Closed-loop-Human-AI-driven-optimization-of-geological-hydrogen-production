# Geological Hydrogen Optimization - Data Visualizations

The Python script in Data_analysis_Part1.ipynb provides a comprehensive suite of visualization tools to support the analysis and interpretation of data from closed-loop optimization experiments on geological hydrogen production. It generates publication-quality plots used in the manuscript titled:

"Closed-loop, Human-AI-driven-optimization-of-geological-hydrogen-production."

__Overview__
## Data Visualization Part 1 (Bayesian Optimization Progression Analysis)
The script includes multiple functions for visualizing:

1. Search space complexity by dimensionality (Figure 1B).
2. Trends in hydrogen concentration across experiments (Figure 2A).
3. Relationships between operating reaction parameters and performance metrics (Figure 2B and Supplementary Figure S10).
4. Combined subplot panels used in figure generation (Figure 2).

__Key Visualizations__
1. Search Space Plot: Number of optimization points vs. number of variables.
2. Hydrogen Concentration Trends: Concentration evolution over experiments with annotations by optimization method.
3. Multi-panel Figures: Input parameters colored by hydrogen concentration.

## Data Visualization Part 2 (Variable Interaction Analysis)

This notebook includes functions for analysing the importance of respective experimental variables for Geo-H2 production, and their interaction effects. This includes 2D partial dependence plots (Figure 2D, S12, S13), SHAP (Fig. 2C) and SHAP-IQ analyses (Fig. 3), along with generation of Figures, S11-18 and S24.




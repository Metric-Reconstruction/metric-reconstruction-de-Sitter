[![arXiv number here](IMG link here)](arXiv link here) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/Metric-Reconstruction/metric-reconstruction-de-Sitter/blob/main/LICENSE)
# Gravitational Waves on Kerr Black Holes II #

A suite of Mathematica notebooks containing analytic expressions for the metric perturbations of a Kerr–(anti-)de Sitter black hole.

## Notebook Descriptions

**MetricPerturbations.nb** 

This notebook provides analytic expressions for the metric perturbations of a Kerr–(anti-)de Sitter black hole. The metric components are given in Boyer-Lindquist, ingoing, and outgoing coordinates and in two gauges: ingoing radiation gauge (IRG) and outgoing radiation gauge (ORG). These explicit expressions are saved in the directory `metric-perturbations/`.

_______
**deSitterEinsteinFieldEquations.nb** 

This notebook: 
1. Computes the linearized Einstein tensor associated with an arbitrary perturbation of the Kerr background and saves its components in the directory `linearized-Einstein-tensor/`. This step takes about 10 minutes of runtime on a laptop.
2. Imports the components of the metric perturbations from `deSitterMetricPerturbations.nb` and verifies that they solve the linearized Einstein vacuum equations. Checking most components takes about 2 minutes of runtime on a laptop, but one particular component in each gauge may take about 10 minutes.

This check is carried out for both radiation gauges (IRG and ORG) but only in Boyer-Lindquist coordinates.  A simple coordinate transformation is then sufficient to establish correctness of the components in ingoing and outgoing coordinates.
_______
**ExampleUsage.nb** 

This notebook showcases how the explicit expressions from `deSitterMetricPerturbations.nb` can be used for symbolic or numeric computations. As an example, we display plots of metric perturbation components.

______________
R. Berens, T. Gravely, and A. Lupsasca, “Gravitational Waves on Kerr Black Holes II: Metric Reconstruction with Cosmological Constant,” 2025. [arXiv number here](arXiv link here)
______________

# Spare Parts Inventory: MCDM and Deep Learning

Code accompanying the study:

**Integrating Multi-Criteria Decision Making and Deep Learning for Spare Parts Inventory**

## Contents

The notebooks cover multicriteria prioritization, feature engineering,
graph construction, forecasting, baseline comparisons, ablation,
and permutation feature importance.

## Installation

Install dependencies using:

    pip install -r requirements.txt

Use a PyTorch installation suitable for your operating system
and hardware. Validate package compatibility before execution.

## Suggested notebook sequence

1. `01_criteria_aggregation_normalization_critic.ipynb`
2. `02_wsm_topsis_fuzzy_topsis.ipynb`
3. `03_monthly_features_causal_score.ipynb`
4. `04_historical_windows.ipynb`
5. `05_spatiotemporal_graph.ipynb`
6. `06_gcn_training_evaluation.ipynb`
7. `07_gat_training_evaluation.ipynb`
8. `08_tft_training_evaluation.ipynb`
9. `09_baselines_extended_comparison.ipynb`
10. `10_comparative_evaluation.ipynb`
11. `11_gcn_ablation.ipynb`
12. `12_gcn_permutation_importance.ipynb`

Confirm execution order from the files consumed and generated
by each notebook.

Check input and output paths before running the notebooks.
Renaming notebooks does not update paths inside their cells.
Set the working directory expected by those paths.

## Data confidentiality

The source data are confidential and are not included.
Execution requires locally supplied input files.
See docs/data_description.md for the input schemas.

Notebook outputs, attachments and execution metadata were removed
from this distribution. Code and Markdown contents were preserved.

## Implementation provenance

This repository organizes the available implementation of the study.
Correspondence between notebook versions and article results
should be documented using the applicable configurations
and execution records.

## Environment

requirements.txt lists dependencies detected in notebook imports.
docs/current_environment.md records current package versions.
The dependency list requires review and is not an environment lock file.

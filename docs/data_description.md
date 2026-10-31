# Input data description

No real observations are included in this repository.

## Source inventory file

Expected fields include:

- Reference: item identifier stored as text.
- Entry_Date: date field defined by the study protocol.
- Quantity: quantity variable defined by the data owner.
- Unit_Margin: unit margin.
- Total_Purchase_Cost: purchase cost.
- Constructor and Designation: required if used for grouping.

Document units, currency, date availability, and missing-value rules
for the actual input dataset.

## Monthly forecasting file

Expected fields:

- Month
- Quantity
- Unit_Margin
- Total_Purchase_Cost
- Quantity_Next_Month

The target definition, temporal coverage and treatment
of missing months must match the evaluation protocol.

## Additional files

Document the schemas of engineered panels, historical windows,
graphs and other intermediate files required by the notebooks.
These private or generated files are not included.

## Access

Access conditions are governed by the data owner's authorization.
This repository does not grant access to the underlying dataset.

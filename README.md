# HERMES
HERMES: A Health Resources Econometric Analysis Tool

## Introduction

HERMES is an open-source R package for economic analysis in OMOP-CDM/OHDSI (https://ohdsi.github.io/CommonDataModel/index.html), including healthcare costs analysis, resource utilization analysis, and time-series with comparing cohorts.
HERMES is implemented using OMOP-CDM 5.0 version, R 4.3.1.
More functions will be updated, including economic evaluation (cost-effectiveness, budget impact analysis, etc.) (expected in 2024).

This GitHub repository has purposes:
 1. Publish code
 2. Develop and collaborate on HERMES packages together

## License
HERMES is licensed under MIT license.

## Development
HERMES is being developed in R Studio.

## Development status
Beta. Use at your own risk.

## Caution
There is an error in the COST CONCEPT ID because the English and Korean names of the COST variables do not match in the database used. 
The current variable is 
cost concept id 31980: total medical cost 
cost concept id 2000000040: total medical cost
cost concept id 2000000041: reimbursement cot
cost concept id 2000000042: non-reimbursement cost
cost concept id 31991: out-of-pocket cost
cost concept id 31974: medical cost covered by insurance
cost concept id 31976: medical cost covered by employer

If you have any comments or questions, please don't hesitate to contact us (kyungseon.choi@khu.ac.kr).

*Note: This README provides an overview of the HERMES package. For detailed implementation codes, examples, and documentation of R functions, please refer to the appropriate sections in the package documentation.*

## Reference
 1. https://www.ohdsi.org/2022showcase-55/
 2. https://www.valueinhealthjournal.com/article/S1098-3015(22)00504-6/fulltext
 3. https://www.valueinhealthjournal.com/article/S1098-3015(22)03085-6/fulltext

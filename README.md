
# BPI Challenge 2019 - Business Information Systems Project

## Overview
This project is part of the BPI Challenge 2019, which involves data from a large multinational company in the coatings and paints industry. The goal of the project was to analyze the provided event log data, identify patterns, and answer three key business questions related to process modeling, throughput time analysis, and deviations in the invoicing process.

## Objective
The challenge is divided into three phases:
1. **Challenge 1**: Data exploration, preprocessing, and process model discovery using process mining techniques.
2. **Challenge 2**: Throughput time analysis to measure the performance of the invoicing process.
3. **Challenge 3**: Identifying deviations from the standard process and quantifying their severity.

## Data
The dataset consists of anonymized purchase order information, including purchase document IDs, item IDs, and various event attributes like goods receipt, invoice receipt, and vendor information. The data also includes different types of purchase items and their associated invoicing processes.

You can access the dataset [here](https://data.4tu.nl/articles/_/12715853/1).

## Requirements
- Python 3.x
- PM4Py (for process mining)
- Pandas (for data manipulation)
- Matplotlib / Seaborn (for data visualization)

## Methodology
### Phase 1: Data Exploration and Preprocessing
- Cleaned and filtered the data based on business rules (compliance, completeness, and time frames).
- Performed clustering and variant analysis to understand the different purchasing and invoicing processes.

### Phase 2: Throughput Time Analysis
- Calculated the throughput time for invoicing processes (from goods receipt to invoice receipt and payment).
- Analyzed the average throughput time for each type of process (e.g., 3-way match, 2-way match).

### Phase 3: Deviations Detection
- Identified deviations from the standard process using predefined rules.
- Calculated the severity of these deviations based on event counts and compliance with the rules.

## Results
- Multiple process models (BPMNs) were generated for different types of purchase items.
- Throughput time for different process categories was computed and compared.
- Deviations from the expected process flows were identified, with severity metrics to highlight critical issues.

## Conclusion
This project successfully answered the three challenges of the BPI Challenge 2019 by preprocessing the data, discovering process models, calculating throughput times, and detecting deviations. These insights provide valuable information for improving business processes and addressing inefficiencies in the invoicing procedure.


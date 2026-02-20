# Process Mining and Bottleneck Analysis: BPI 2017 Loan Application Dataset

## Project Overview

This project focuses on analyzing loan application process efficiency using process mining techniques on the BPI 2017 event log dataset. The objective was to discover the actual process flow, identify operational bottlenecks, measure process performance, and detect inefficiencies contributing to delays.

The analysis was conducted on a large-scale event log dataset containing over 1.2 million events, enabling deep insights into process behavior, cycle times, and rework patterns.

---

## Objectives

* Analyze real-world loan application event log data
* Discover actual business process flow using process mining techniques
* Identify bottlenecks and process inefficiencies
* Measure cycle time and process performance metrics
* Detect rework loops and process deviations
* Generate actionable insights to improve operational efficiency

---

## Dataset Description

The dataset contains event log data from a financial institution’s loan application process.

Key attributes include:

* Case ID – Unique identifier for each loan application
* Activity – Process step performed
* Timestamp – Date and time of activity execution

Dataset scale:

* 1,202,267 event records
* 31,509 unique cases
* 15,930 process variants

Source: BPI 2017 Loan Application Event Log Dataset

---

## Tools and Technologies Used

* Python – data processing and analysis
* Pandas, NumPy – data cleaning and transformation
* PM4Py – process mining and process discovery
* Google Colab – analysis environment
* Matplotlib – data visualization

---

## Process Mining Techniques Applied

### Data Preprocessing

* Cleaned and structured event log data
* Converted timestamps into analyzable format
* Prepared dataset for process mining analysis

### Process Discovery

* Applied Inductive Miner algorithm using PM4Py
* Generated process model representing real process flow

### Variant Analysis

* Analyzed 15,930 process variants
* Evaluated process fragmentation and behavioral deviations

### Performance Analysis

Measured key performance indicators:

* Cycle time
* Activity frequency
* Waiting time
* Rework frequency

---

## Key Findings and Insights

* Approximately 6.5% of cases exceeded the 30-day SLA threshold
* Long-duration cases showed 74% higher incomplete-file follow-up frequency
* Identified major bottlenecks in validation and follow-up stages
* Detected rework loops contributing to process delays
* Waiting time between activities significantly impacted total cycle time

---

## Performance Metrics Designed

* Average cycle time per case
* Activity frequency distribution
* Rework rate
* SLA compliance rate
* Waiting-time bottleneck identification

---

## Business Impact and Recommendations

The analysis revealed that incomplete-file rework loops were a major contributor to process delays.

Reducing rework and improving validation efficiency could potentially reduce overall cycle time by approximately 10–20%, improving process efficiency and SLA compliance.

---

## Skills Demonstrated

* Process mining and workflow analysis
* Large-scale data processing (1.2M+ records)
* Data cleaning and preprocessing
* Process discovery using PM4Py
* Performance analysis and KPI design
* Bottleneck detection and root cause analysis
* Analytical thinking and business insight generation

---

## Conclusion

This project demonstrates the application of process mining techniques to analyze real-world business processes, identify inefficiencies, and generate actionable insights. It highlights the importance of data-driven process optimization in improving operational efficiency.

---

## Author

Vandana
B.Tech Graduate
Aspiring Data Analyst and ESG Analyst

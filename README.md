# Process Mining & Bottleneck Analysis
Objective

Analyze real-world event log data to discover process flow and identify operational bottlenecks.

 Dataset

BPI Challenge 2017 Loan Application Event Log
31,509 cases analyzed.

 Tools Used

Python

PM4Py

Pandas

Matplotlib

 Key Findings

6.49% of cases exceeded 30 days

Long cases had 74% more repeated incomplete file calls

W_Call incomplete files was primary bottleneck driver

Significant rework loops observed in validation stage

Techniques Applied

Event log preparation

Variant analysis

Activity frequency comparison

Bottleneck detection

Process model discovery (Inductive Miner)

 Business Insight

Reducing repeated incomplete-file calls could significantly reduce cycle time and improve process efficiency.

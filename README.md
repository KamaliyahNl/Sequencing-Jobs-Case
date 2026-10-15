# Sequencing-Jobs-Case
Excel for implementation of job sequencing rules (FCFS, SPT, EDD, LPT) with a dynamic decision to evaluate and select the optimal schedule based on minimum mean flow time, tardiness, and makespan.

# Problems & Data Structure
The following jobs are waiting to be processed at the same machine center. Jobs are logged as they arrive.
<img width="376" height="194" alt="image" src="https://github.com/user-attachments/assets/212eb2ef-7390-4124-b0e1-583411ddf22c" />

In what sequence would the jobs be ranked according to the following decision rules: (a) FCFS, (b) EDD, (c) SPT, and (d) LPT? All dates are specified as manufacturing planning calendar days. Assume that all jobs arrive on day 275. Which decision is best and why? 

# Executive Summary
The analysis compares four job sequencing rules — FCFS (First Come, First Served), SPT (Shortest Processing Time), EDD (Earliest Due Date), and LPT (Longest Processing Time) — using four performance metrics: average completion time, utilization, average number of jobs, and average lateness.
The results indicate that SPT (Shortest Processing Time) is the best overall strategy when the primary objective is to reduce completion time and the average number of jobs in the system while maintaining relatively high utilization.
Key Insights:
- SPT delivers the shortest average completion time. At 41.4, it performs better than FCFS, EDD, and LPT, making it suitable for improving workflow speed.
- SPT achieves the highest utilization metric. Its value of 0.35 (35%) is the highest among the four rules, although the interpretation depends on how utilization was calculated.
- SPT minimizes the average number of jobs in the system. With 2.88 jobs, it outperforms FCFS (3.29), EDD (2.92), and LPT (4.25).
- EDD offers a strong alternative. It achieves an average completion time of 42.0 and average lateness of 10.4, making it a reasonable choice when due-date considerations are important.
- LPT achieves the lowest average lateness. Its value of 9.4 is the best among the four rules, but it also has the longest average completion time (61.2), the highest average number of jobs (4.25), and the lowest utilization metric (24%).
- FCFS is straightforward but less efficient in this comparison. It has a higher average completion time and average lateness than SPT and EDD.

# Recommendation: 
SPT is the strongest overall choice when the goal is to improve operational efficiency, reduce the time jobs spend in the system, and minimize work-in-process levels.

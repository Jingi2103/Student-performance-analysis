# Student-performance-analysis
Analysis of student performance using T-test and graphs
## Overview
This project analyse the performance of DG alumni vs Non-DG alumni studying in government school and Private school using T-test.

## Dataset
The dataset contains the marks of 53 students, including both DG alumni and Non-DG students, who are participating in the DG after-school program. The sample comprises students from both private and government schools.

## Methodology
- T-test assumptions
- Steps for analysis

## Results
Include screenshots of graphs or summarize findings.

## Conclusion
Key takeaways from the analysis:

**Case 1**:_**DG Private vs DG Govt**_ :
t = 4.4, df = 15
Critical t ≈ ±2.13
Two-tailed p ≈ 0.0006
Rejects the null hypothesis
Conclusion : The chance that the observed difference is due to random sampling is about 0.06 %, providing very strong evidence that ,DG-private students consistently outperform DG-government students in this ASER assessment.
Factors including resources, or teaching quality should be improved which will contribute to the difference.

**Case 2**: _**DG vs Non-DG**_ :
t = 0.75, df = 47
Critical t ≈ ±2.01
Two-tailed p ≈ 0.46
Fail to reject the null hypothesis
Conclusion : A 46 % probability of seeing this difference by chance means there is no meaningful statistical evidence that DG alumni and Non-DG student differs  in  marks.
Any small observed difference is likely just random variation.

**Case 3**: _**Private vs Govt (All)**_ :
t = 6.02, df = 38
Critical t ≈ ±2.02
Two-tailed p ≈ 1e-06
Rejects the null Hypothesis
Conclusion : Such a low probability highlights a consistent performance advantage among private-school students
Factors determining such a huge difference : socioeconomic status, resources,  teaching quality etc..

## Code
All code is available in the notebook `Student_performance-ANALYSIS.ipynb`.

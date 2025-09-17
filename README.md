# Student-performance-analysis
Analysis of student performance using T-test and graphs
## Overview
This project analyse the performance of DG alumni vs Non-DG alumni studying in government school and Private school using T-test.

## Dataset
The dataset contains the marks of 53 students, including both DG alumni and Non-DG students, who are participating in the DG after-school program. The sample comprises students from both private and government schools.
The dataset is available in `T-test data.csv`

## Methodology
- T-test assumptions
- Steps for analysis

## Results
**Case 1:**
<img width="906" height="678" alt="image" src="https://github.com/user-attachments/assets/2968483e-27fb-4f72-a742-a9a74d3fcb84" />

**Case 2:**
<img width="998" height="690" alt="image" src="https://github.com/user-attachments/assets/1532a39f-57e5-42b4-bd6f-12c9a25ea826" />

**Case 3:**
<img width="923" height="694" alt="image" src="https://github.com/user-attachments/assets/f65826a3-8f67-41a3-845a-2b4797438b5d" />


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

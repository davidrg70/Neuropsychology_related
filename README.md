# Neuropsychology_related
Deal with normative scores and others

"dg_PR_Zscore_Tscore_converter.m" Converts Percentile ranks (PR) to Z-scores or T-scores, as indicated. 
Written according to Iverson, G.L. (2011). Z Scores. In Kreutzer, J.S., DeLuca, J., & Caplan, B. (Eds.), Encyclopedia of Clinical Neuropsychology.(pp. 2739-2740). Springer. https://doi.org/10.1007/978-0-387-79948-3

"dg_compare_cognitive.m" Compares Z-scores or PRs of two groups of subjects (i.e., patients vs. controls) using the Wilcoxon rank test (equivalent to the Mann-Whitney-U test). Additionally, the script applies an FDR correction (https://www.mathworks.com/matlabcentral/fileexchange/27418-fdr_bh) for multiple comparisons. An implementation of t-tests for bigger samples can be added if required. Lastly, in the future, I can easily add a normality test (Shapiro-Wilk) to calculate either Wilcoxon rank test or t-test.

# Table1 Generation and Group Comparison with Statistical Tests
This code is an adaptation based on the tailbone package, allowing for the creation of tables with inter-group comparison statistics and p-values. The code automatically detects the distribution of data to choose the appropriate statistical test. For example, when comparing a continuous variable between two groups, it checks for normality and selects either the t-test or the Wilcoxon rank-sum test accordingly.

Files included:

temp_data.Rdata: Demonstration data.
table1_generation_code.R: Main code for generating the table. Users can modify parameters as needed.
Table1.R: Underlying code for table1.

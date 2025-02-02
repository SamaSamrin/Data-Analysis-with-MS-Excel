# 5 Main Steps of Data Analysis

### 1. Define the questions that you want to answer through the analysis

- clearly define the problem

- make hypothesis or research questions

- identify what types of data you will need and where it'll come from

### 2. Collect the Data

- primary sources: internal data that the company already has (eg: CRM software, email marketing tools etc.)

- secondary sources: public/external data (eg: government, Google Trends, WHO etc.)

### 3. Clean the Data

- remove duplicates

- handle anomalies and missing data

### 4. Analyze the Data

- regression analysis

- cluster analysis

- time-series analysis

### 5. Interpret and share the results

- visualization

# Terms

- ETL = Extract, Transform, Load

- Dax = Data analyst expressions

- Copilot = Feature in Excel, like ChatGPT powered by Microsoft

# Notes

### 1. Concatenate values from 2 string columns:

**=A2&B2**` `if A2='x' and B2='y', then this will produce "xy"

**=A2&"-"&B2**` `adds a hyphen (-) between the two cell values

- the quotation marks are necessary to put text characters between two values

### 2. Range = collection of cells

# Functions

1. <span style="text - decoration: underline;">Logical</span>

1. IF(condition, returned_value_if_true, returned_value_if_false)

2. AND(condition1, condition2)

3. OR(condition1, condition2)

4. IFS(condition1, value1_if_cond1_is_true, condition2, value2_if_cond2_is_true)

2. <span style="text - decoration: underline;">Math</span>

5. COUNT(B:B) - counts all non-blank NUMERICAL cells of the given range (column B)

6. COUNTA(B:B) - counts all non-blank cells of the given range

7. COUNTIF(B:B, $A2) - counts how many values of B is equal to the value of A2

8. COUNTIFS(range1, condition1, range2, condition2)

- counts how many cells of range1 match condition1 & how many cells of range 2 match condition2

9. SUM(B:B)

10. SUMIF(range_to_assess, condition_to_assess, range_to_add)

11. SUMIFS(range_to_add, range1_to_assess, condition1_to_assess, range2_to_assess, condition2_to_assess)

12. AVERAGE(B:B)

13. AVERAGEIF

14. AVERAGEIFS

15. MIN(B:B)

16. MAX(B:B)

3. <span style="text - decoration: underline;">Statistical</span>

### Median

It is the number in the middle of the sorted set (smallest to largest)

Median is better than average for statistics because average is affected by the outliers in the dataset

### Standard Deviation (?)

= how much the data point deviates from the standard (mean)

= how spread out the data is

If SD is low, that means the data is closely clustered around the mean/average

If SD is high, that means the data is dispersed over a wider range of values

SD is used to understand if a specific data point is standard and expected, or unusual and unexpected

A data point?s distance from the mean can be measured by the number of standard deviations (i.e. if it is above or below the mean)

1? = 68% = 68% of data fall within 1 SD of the mean

2? = 95%

3? = 99.7%

SD is used when the distribution of data is approximately normal (like a bell curve)

SD calculation:

![](/images/0B1_Image_1.png)

### Quartile

25% = 25th percentile = 1st Quartile = first 25% of the sorted data or the histogram?

50% = 50th percentile = 2nd Quartile = Median

75% = 75th percentile = 3rd Quartile

100% = 100th percentile = 4th Quartile

**Interquartile Range = Q3-Q1**

17. MEDIAN(B:B)

18. STDEV.P(B:B) - standard deviation of the population

19. STDEV.S(B:B) - standard deviation of a sample

20. QUARTILE.INC(range, quartile_value)

1. eg: QUARTILE.INC(A:A, 2) = 2nd quartile (median)

2. Inclusive (percentile range of 0 to 1 inclusive)

3. Considers the median

4. Used often for odd-numbered sample size

21. QUARTILE.EXC(range, quartile_value)

5. Exclusive (percentile range of 0 to 1 exclusive)

6. Doesn?t consider the median

7. Used for even-numbered sample size


22. RANK(value_to_rank, entire_range, 0)

9. 0 = descending order, 1 = ascending order, this is optional argument

23. MODE(A:A)

10. The most frequently occurring value in the given range

4. <span style="text - decoration: underline;">Array</span>

5. <span style="text - decoration: underline;">Lookup</span>

6. <span style="text - decoration: underline;">Text</span>

7. <span style="text - decoration: underline;">Date & Time</span>

8. <span style="text - decoration: underline;">V</span>

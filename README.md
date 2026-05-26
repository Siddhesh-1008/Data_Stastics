
---

# 🟢 SECTION 1 : NUMPY

---

## Q1. What is NumPy?

### Answer

NumPy is a Python library used for numerical computing and efficient array operations.

### Easy Way

```text
Python List ka super-fast version
```

### Why NumPy Faster?

```text
Continuous Memory

Written in C

Vectorized Operations
```

### Interview Follow-up

```text
Why not use Python List?
```

Answer:

```text
Lists are slower and consume more memory.
NumPy performs operations much faster.
```

---

## Q2. Difference Between List and NumPy Array?

| List               | NumPy         |
| ------------------ | ------------- |
| Multiple Datatypes | Same Datatype |
| Slow               | Fast          |
| More Memory        | Less Memory   |

---

## Q3. What is ndarray?

### Answer

```text
N-dimensional array

Main object of NumPy
```

Example:

```python
np.array([1,2,3])
```

---

## Q4. What is Vectorization?

### Answer

Performing operations on entire arrays without loops.

Example:

```python
a+b
```

instead of

```python
for i in range(n)
```

### Why Important?

```text
Much Faster
```

🔥 Very Common

---

## Q5. What is Broadcasting?

### Example

```python
arr + 5
```

### Meaning

NumPy automatically expands smaller arrays.

### Interview Answer

```text
Broadcasting allows arithmetic operations
between arrays of different shapes.
```

---

## Q6. reshape() vs resize()

### reshape()

```text
Returns new shape
```

### resize()

```text
Modifies original array
```

---

## Q7. copy() vs view()

### copy()

```text
Independent Memory
```

### view()

```text
Shared Memory
```

🔥 Frequently Asked

---

## Q8. What is Axis?

### axis=0

```text
Rows
```

### axis=1

```text
Columns
```

---

## Q9. How to find Mean?

```python
np.mean()
```

---

## Q10. Why Vectorization Faster than Loops?

### Answer

```text
Uses optimized C implementation.

Avoids Python loop overhead.
```

🔥 Favorite Question

---

# 🐼 SECTION 2 : PANDAS

---

## Q11. What is Pandas?

### Answer

Python library for data manipulation and analysis.

---

## Q12. Series vs DataFrame?

### Series

```text
Single Column
```

### DataFrame

```text
Multiple Columns
```

---

## Q13. How to Read CSV?

```python
pd.read_csv()
```

---

## Q14. How to Check Null Values?

```python
df.isnull().sum()
```

---

## Q15. How to Remove Null Values?

```python
df.dropna()
```

---

## Q16. How to Fill Null Values?

```python
df.fillna()
```

Methods:

```text
Mean

Median

Mode
```

---

## Q17. Why Median Better than Mean for Missing Values?

### Answer

```text
Median less affected by outliers.
```

🔥 Common

---

## Q18. What is GroupBy?

### Example

```python
df.groupby('department')['salary'].mean()
```

### Meaning

```text
Split

Apply

Combine
```

---

## Q19. What is Aggregation?

Examples:

```python
mean()
sum()
count()
max()
min()
```

---

## Q20. loc vs iloc?

### loc

```text
Label Based
```

### iloc

```text
Position Based
```

---

## Q21. merge() vs concat()

### merge()

```text
SQL Join
```

### concat()

```text
Stack Tables
```

---

## Q22. What is Pivot Table?

### Answer

Summary table using rows and columns.

---

## Q23. What is apply()?

Apply function to rows/columns.

---

## Q24. apply() vs map()

### map()

```text
Series Only
```

### apply()

```text
Series/DataFrame
```

---

## Q25. How to Remove Duplicates?

```python
df.drop_duplicates()
```

---

# 📊 SECTION 3 : DATA VISUALIZATION

---

## Q26. Why Visualization?

### Answer

```text
Understand Trends

Patterns

Outliers

Relationships
```

---

## Q27. Histogram Use?

### Answer

```text
Distribution Analysis
```

---

## Q28. Bar Chart Use?

### Answer

```text
Compare Categories
```

---

## Q29. Scatter Plot Use?

### Answer

```text
Relationship Between Variables
```

---

## Q30. Line Chart Use?

### Answer

```text
Time Series Trends
```

---

## Q31. Box Plot Use?

### Answer

```text
Outlier Detection

Median

Quartiles
```

---

## Q32. Heatmap Use?

### Answer

```text
Correlation Matrix
```

---

## Q33. Histogram vs Bar Chart?

### Histogram

```text
Numerical Data
```

### Bar Chart

```text
Categorical Data
```

🔥 Very Common

---

## Q34. Matplotlib vs Seaborn?

### Matplotlib

```text
More Control
```

### Seaborn

```text
Better Visualization
```

---

## Q35. Which Plot for Correlation?

### Answer

```text
Scatter Plot

Heatmap
```

---

# 📈 SECTION 4 : STATISTICS

---

## Q36. Mean vs Median?

### Mean

Average

### Median

Middle Value

### When Median?

```text
Outliers Present
```

🔥 Most Asked Question

---

## Q37. What is Outlier?

Value far away from other values.

---

## Q38. How Outlier Affects Mean?

### Answer

```text
Strongly Affects Mean
```

---

## Q39. How Outlier Affects Median?

### Answer

```text
Very Little Effect
```

---

## Q40. What is Variance?

Average squared distance from mean.

---

## Q41. What is Standard Deviation?

Typical distance from mean.

---

## Q42. Difference Between Variance and SD?

### Variance

Squared Units

### SD

Original Units

---

## Q43. What is Normal Distribution?

### Properties

```text
Mean = Median = Mode
```

Bell Shape

---

## Q44. What is Skewness?

### Right Skew

```text
Mean > Median
```

### Left Skew

```text
Mean < Median
```

---

## Q45. Why Mean Used in Normal Distribution?

### Answer

```text
No Outliers

Symmetric Distribution
```

---

## Q46. Why Median Used in Skewed Data?

### Answer

```text
Less Sensitive to Outliers
```

🔥 Very Common

---

## Q47. What is Z-score?

### Formula

[
Z=(x-\mu)/\sigma
]

### Meaning

Distance from mean in SD units.

---

## Q48. Why Use Z-score?

```text
Outlier Detection

Comparison

Feature Scaling
```

---

## Q49. What is Correlation?

Direction + Strength.

Range:

```text
-1 to +1
```

---

## Q50. Correlation vs Causation?

### Answer

```text
Correlation shows relationship.

Does not prove cause-effect.
```

Example:

```text
Ice Cream Sales ↑

Drowning ↑
```

Reason:

```text
Summer
```

🔥 Very Important

---

# 🎯 TOP 10 QUESTIONS MOST LIKELY IN YOUR INTERVIEW

```text
Mean vs Median

Outlier

Variance

Standard Deviation

Normal Distribution

Z-score

Correlation

Correlation vs Causation

GroupBy

loc vs iloc
```

---

# 🔥 QUESTIONS THAT IMPRESS INTERVIEWERS

```text
Why Vectorization Faster?

Why Median Better for Salary Data?

Correlation ≠ Causation

Why Standard Deviation Needed?

Histogram vs Bar Chart

Why Mean = Median = Mode in Normal Distribution?

Why Use GroupBy?

copy vs view

merge vs concat

apply vs map
```

---

# 🚀 2-MINUTE FINAL REVISION

```text
NumPy → Fast Numerical Computing

Vectorization → No Loops

Broadcasting → Different Shape Operations

Pandas → Data Analysis

Series → One Column

DataFrame → Multiple Columns

GroupBy → Split Apply Combine

loc → Label

iloc → Position

Histogram → Distribution

Bar Chart → Categories

Scatter → Relationship

Boxplot → Outliers

Mean → Average

Median → Middle

Mode → Most Frequent

Variance → Spread

SD → Typical Distance

Normal Distribution → Mean=Median=Mode

Z-score → Distance from Mean

Correlation → Direction + Strength

Correlation ≠ Causation
```


🔥 **Top Tricky Interview Questions (NumPy + Pandas + Visualization + Statistics)**

Ye questions freshers ko confuse karte hain aur interviewers dekhte hain ki concept clear hai ya ratta maara hai.

---

# 1. Mean = Median = Mode kab hota hai?

### Answer

```text
Perfectly Normal Distribution
```

### Why?

Distribution symmetric hoti hai.

---

# 2. Mean aur Median dono same ho sakte hain kya?

### Answer

```text
Yes
```

Normal distribution me.

---

# 3. Correlation 0 hai. Kya iska matlab relationship nahi hai?

### Answer

```text
No
```

Means:

```text
No Linear Relationship
```

Non-linear relationship ho sakta hai.

Example:

[
y=x^2
]

Correlation near 0 aa sakta hai.

🔥 Very favorite question

---

# 4. Correlation 1 hai. Kya causation prove ho gaya?

### Answer

```text
No
```

Correlation ≠ Causation.

---

# 5. High Correlation hamesha good hota hai?

### Answer

```text
No
```

Feature redundancy ho sakti hai.

Multicollinearity create kar sakta hai.

---

# 6. Can Mean Be Outside Dataset?

### Answer

```text
Yes
```

Example:

```text
1 2 10
```

Mean:

```text
4.33
```

Dataset me exist nahi karta.

---

# 7. Can Median Be Outside Dataset?

### Answer

```text
Yes
```

Even observations me.

Example:

```text
1 2 3 4
```

Median:

```text
2.5
```

---

# 8. Which is More Affected by Outliers?

### Answer

```text
Mean
Variance
Standard Deviation
```

Median least affected.

---

# 9. Why Variance Squares Values?

### Answer

Without square:

```text
Positive + Negative deviations
cancel out
```

---

# 10. Can Standard Deviation Be Negative?

### Answer

```text
Never
```

Because:

[
SD=\sqrt{Variance}
]

---

# 11. Can Variance Be Negative?

### Answer

```text
Never
```

Squared values always positive.

---

# 12. Standard Deviation = 0 Means?

### Answer

All values identical.

Example:

```text
5 5 5 5 5
```

---

# 13. If Mean Increases, SD Also Increases?

### Answer

```text
Not Necessary
```

Independent concepts.

---

# 14. Why Median Used for Salary?

### Answer

Salary distribution right-skewed.

Few rich people pull mean.

Median gives typical salary.

---

# 15. What if Dataset Has No Outliers?

### Answer

Use Mean.

---

# 16. Why Histogram Not Bar Chart?

### Answer

Histogram:

```text
Continuous Numerical Data
```

Bar Chart:

```text
Categorical Data
```

---

# 17. Can Histogram Detect Outliers?

### Answer

```text
Yes
```

Extreme bins indicate outliers.

---

# 18. Which Plot Best For Outliers?

### Answer

```text
Box Plot
```

---

# 19. Difference Between Covariance and Correlation?

### Covariance

```text
Direction Only
```

### Correlation

```text
Direction + Strength
```

Range:

```text
-1 to +1
```

---

# 20. Why Correlation Preferred?

### Answer

Easy interpretation.

Standardized scale.

---

# 21. What if Correlation = -1?

### Answer

Perfect negative relationship.

---

# 22. Why p-value < 0.05?

### Answer

Convention.

Not a magic number.

Could use:

```text
0.01

0.10
```

depending on problem.

🔥 Advanced question

---

# 23. p-value = 0.04 means H₀ false?

### Answer

```text
No
```

Means evidence against H₀.

Does NOT prove H₀ false.

---

# 24. p-value = 0.20 means H₀ true?

### Answer

```text
No
```

Means insufficient evidence.

---

# 25. Why Not Say "Accept H₀"?

### Correct

```text
Fail To Reject H₀
```

Because we don't prove H₀ true.

🔥 Interview favorite

---

# 26. Z-Test vs T-Test Fast Answer

### Z-Test

```text
Population SD Known
```

### T-Test

```text
Population SD Unknown
```

---

# 27. Why T Distribution Wider Than Z?

### Answer

Extra uncertainty because population SD unknown.

---

# 28. Why Use ANOVA Instead of Multiple T-tests?

### Answer

Multiple T-tests increase Type-I Error.

---

# 29. ANOVA Says Difference Exists. Which Group Different?

### Answer

Need:

```text
Post-Hoc Tests
```

Example:

```text
Tukey Test
```

🔥 Very good answer

---

# 30. Chi-Square For Numerical Data?

### Answer

```text
No
```

Used for categorical variables.

---

# 31. Why Chi-Square Uses Frequencies?

### Answer

It compares observed counts and expected counts.

---

# 32. What is Degrees of Freedom?

### Answer

Independent values free to vary.

Formula:

```text
n-1
```

---

# 33. Why n-1?

### Answer

One value becomes fixed when mean known.

---

# 34. Why NumPy Faster Than List?

### Answer

```text
Contiguous Memory

C Implementation

Vectorization
```

---

# 35. Broadcasting Failure Kab Hota Hai?

### Answer

Shapes incompatible.

Example:

```python
(3,2)

+

(4,2)
```

Error.

---

# 36. copy() vs view()

### copy()

Independent memory.

### view()

Shares memory.

🔥 NumPy favorite

---

# 37. loc vs iloc

### loc

Label based.

### iloc

Position based.

---

# 38. apply() vs map()

### map()

Series only.

### apply()

Series/DataFrame.

---

# 39. merge() vs concat()

### merge()

SQL join.

### concat()

Stack rows/columns.

---

# 40. Why GroupBy Important?

### Answer

Aggregate data efficiently.

Example:

```python
Department-wise salary
```

---

# ⭐ 10 QUESTIONS THAT IMPRESS INTERVIEWERS

```text
Correlation ≠ Causation

Why n−1 in Variance

Why Not Accept H₀

p-value ≠ Probability H₀ True

ANOVA vs Multiple T-tests

Correlation 0 ≠ No Relationship

Mean Outside Dataset

Median Outside Dataset

Why Salary Uses Median

Why T Distribution Wider Than Z
```


# Alcohol Consumption and Academic Performance Analysis

## Project Overview
This analysis explores the relationship between alcohol consumption, social activities, and academic performance among students. The primary aim is to determine if and how drinking habits and socialization frequency affect students' academic outcomes.

### Objectives
1. **Analyze** the correlation between alcohol consumption and academic performance.
2. **Investigate** the impact of social activities on students' GPA.
3. **Examine** factors influencing absenteeism related to alcohol use.

---

## Steps in the Analysis

### Step 1: Data Loading and Preparation
- Load the dataset using `pandas`.
- Rename columns for easier manipulation.
- Perform basic checks:
  - Data types of each column
  - Missing values in each column
  - Unique values count for each column
- Convert `Timestamp` column to `datetime` format.

### Step 2: Exploratory Data Analysis (EDA)
- **Statistical Summary**: Generate descriptive statistics for numeric variables.
- **Unique Values**: For columns `Sex`, `Accommodation`, and `Monthly_Allowance`, count unique values and their frequencies.
- **Key Visualizations**:
  - Histogram and boxplot for `Yearly GPA` to identify extreme values.
  - Bar chart showing the count of male vs. female students.

#### Hypotheses for Exploration
1. **Alcohol Consumption and Academic Performance**: Explore if there’s a relationship between alcohol intake and GPA.
2. **Social Activities and Academic Performance**: Assess how often social activities correlate with GPA.
3. **Alcohol Consumption and Absenteeism**: Analyze if higher alcohol consumption leads to more missed classes.

### Step 3: Data Cleaning
- Remove records missing monthly allowance information.
- Map text ranges in `Monthly_Allowance` to integers using median values.
- Exclude students with `Postgraduate` status.

### Step 4: Visualizations and Findings
1. **Scatter Plot**: Relationship between alcohol consumption (`Drinks_Per_Night`) and `Yearly GPA`.
2. **Box Plot**: Impact of `Socialising_Frequency` on `Yearly GPA`.
3. **Bar Plot**: Average missed classes by `Drinks_Per_Night` level.

### Step 5: Correlation Analysis
- Correlate alcohol consumption, social activity frequency, and academic performance.
- Results are shown in a correlation matrix to interpret possible relationships.

---

## Results and Insights
### Key Findings
- Detailed findings on the effects of alcohol consumption and social activities on students' academic performance.
- Statistical insights into absenteeism due to alcohol-related reasons.

### Conclusion
Based on the results, the analysis provides insights into how drinking habits and social behaviors potentially influence academic success, guiding further investigation or policy-making.

---

## Instructions to Reproduce Analysis
1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/repository-name.git

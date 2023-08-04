# Statistics For Data Science 
#### Ritwik Ganguly
---
![Stat For DS](https://www.superheuristics.com/wp-content/uploads/2018/05/Basic-Statistics-for-Data-Science.jpg)


# Descriptive Statistics

Descriptive statistics is a branch of statistics that involves summarizing and describing the main features of a dataset. It provides a way to simplify and present complex data in a more understandable form, enabling researchers and analysts to gain insights and make informed decisions. Descriptive statistics focus on the organization, interpretation, and presentation of data, without making inferences about the larger population.

### Key Aspects of Descriptive Statistics

1. **Measures of Central Tendency**: These statistics describe the central or average value of a dataset.

   - **Mean (Average)**: Sum of all values divided by the number of values.
   - **Median**: Middle value when data is arranged in ascending order.
   - **Mode**: Most frequently occurring value.

2. **Measures of Dispersion**: These statistics indicate how spread out or clustered the data points are.

   - **Range**: Difference between the maximum and minimum values.
   - **Variance**: Average of squared differences from the mean.
   - **Standard Deviation**: Square root of the variance.
   - **Interquartile Range (IQR)**: Range between the first and third quartiles.

3. **Skewness and Kurtosis**: These statistics describe the shape of the data distribution.

   - **Skewness**: Measures the asymmetry of the distribution.
   - **Kurtosis**: Measures the "tailedness" of the distribution.

4. **Percentiles**: Values below which a given percentage of observations fall.

### Why Descriptive Statistics Matters

Descriptive statistics offer several benefits:

- **Simplicity**: Complex datasets are simplified into understandable values.
- **Comparisons**: Data can be compared and contrasted more easily.
- **Visualizations**: Descriptive statistics aid in creating informative graphs.
- **Initial Insights**: They provide preliminary insights into the dataset.
- **Data Cleaning**: Outliers and errors can be identified through these stats.

### Example

Consider a dataset of exam scores: 75, 85, 90, 78, 92, 88, 70, 82.

- Mean: (75 + 85 + 90 + 78 + 92 + 88 + 70 + 82) / 8 = 82.5
- Median: When arranged in order: 70, 75, 78, 82, 85, 88, 90, 92 → Median = 82.5
- Mode: No repeated values, so no mode.
- Range: 92 - 70 = 22
- Variance: Calculate squared differences from the mean, average them.
- Standard Deviation: Square root of the variance.
- Skewness: Evaluate the symmetry of the distribution.
- Kurtosis: Evaluate the "tailedness" of the distribution.

## Key Points - 
Some Importants keywords of descriptive statistics need to be known...

1. **Data**: Data refers to raw and unprocessed facts, figures, or values collected from various sources. It can take the form of numbers, text, images, or any other format that can be stored and analyzed. For example, a list of temperatures recorded over a week is data.

2. **Difference between Data and Information**: Data becomes information when it is processed, organized, and interpreted in a meaningful context. Information provides insights and understanding. For instance, if we analyze the temperatures recorded over a week and calculate the average temperature, maximum temperature, and minimum temperature, this processed data becomes valuable information.

3. **Skewness in Statistics**: Skewness measures the asymmetry of the probability distribution of a real-valued random variable. It indicates the extent to which a distribution is not symmetric around its mean. A positively skewed distribution has a longer tail on the right, while a negatively skewed distribution has a longer tail on the left. 

   Example: Consider a dataset of exam scores where most students scored well, but a few scored very low. This would result in a positively skewed distribution.

4. **Variance**: Variance measures the spread or dispersion of a set of data points. It quantifies how much the data points deviate from the mean.

   Formula: Variance (σ²) = Σ(xi - μ)² / N

   Example: Let's say we have exam scores: 85, 90, 78, 92, and 88. Mean (μ) = (85 + 90 + 78 + 92 + 88) / 5 = 86.6. Variance = ((85-86.6)² + (90-86.6)² + (78-86.6)² + (92-86.6)² + (88-86.6)²) / 5 = 24.96.

5. **Standard Deviation**: Standard deviation is the square root of variance. It measures the average deviation of each data point from the mean.

   Formula: Standard Deviation (σ) = √Variance

   Example: Using the previous example, Standard Deviation = √24.96 = 4.996.

6. **Coefficient of Variation**: The coefficient of variation (CV) is a relative measure of variability, calculated as the ratio of the standard deviation to the mean.

   Formula: CV = (Standard Deviation / Mean) * 100

   Example: If the mean is 50 and the standard deviation is 10, CV = (10 / 50) * 100 = 20%.

7. **Covariance**: Covariance measures the degree to which two variables change together. A positive covariance indicates that the variables tend to increase or decrease together, while a negative covariance indicates they move in opposite directions.

   Formula: Cov(X,Y) = Σ((xi - X̄) * (yi - Ȳ)) / (N - 1)

   Example: Consider data pairs X: [2, 3, 5, 7] and Y: [8, 9, 10, 12]. Mean of X (X̄) = 4.25, Mean of Y (Ȳ) = 9.75. Covariance = ((2-4.25) * (8-9.75) + (3-4.25) * (9-9.75) + (5-4.25) * (10-9.75) + (7-4.25) * (12-9.75)) / (4-1) = 4.25.

8. **Correlation**: Correlation is a standardized measure of the strength and direction of the linear relationship between two variables. It ranges from -1 to 1.

   Formula: Correlation (ρ) = Cov(X,Y) / (σX * σY)

   Example: Using the previous data, if σX = 1.87 and σY = 1.96, Correlation = 4.25 / (1.87 * 1.96) = 1.14.

9. **Correlation Coefficient**: The correlation coefficient is a numerical value that quantifies the correlation between two variables. It's calculated using specific formulas and ranges from -1 to 1, just like correlation.

   Formula: Correlation Coefficient (r) = Cov(X,Y) / (√(Var(X) * Var(Y)))

   Example: Continuing from the previous data, if Var(X) = 3.50 and Var(Y) = 3.84, Correlation Coefficient = 4.25 / (√(3.50 * 3.84)) = 0.617.

---
# Inferential Statistics

Certainly! Here's an explanation of inferential statistics in Markdown format, along with a comparison to descriptive statistics:

---

## Inferential Statistics

Inferential statistics is a branch of statistics that involves drawing conclusions or making inferences about a population based on a sample of data. Unlike descriptive statistics, which focus on summarizing and describing the characteristics of a dataset, inferential statistics aim to generalize and make predictions about larger populations using sample data. Inferential statistics plays a crucial role in decision-making, hypothesis testing, and making predictions based on limited data. It's an essential tool for researchers and analysts aiming to make broader conclusions from their observations.

### Key Aspects of Inferential Statistics

1. **Population and Sample**: 

   - **Population**: The entire group that the researcher wants to study.
   - **Sample**: A subset of the population used to draw conclusions.

2. **Hypothesis Testing**:

   - **Null Hypothesis**: A statement of no effect or no difference.
   - **Alternative Hypothesis**: A statement of an effect or a difference.
   - **Significance Level (α)**: The probability of rejecting a true null hypothesis.
   - **P-value**: The probability of observing a test statistic as extreme as the one computed, assuming that the null hypothesis is true.

3. **Confidence Intervals**:

   - A range of values that is likely to contain the population parameter with a certain level of confidence.
   - Example: A 95% confidence interval for the average height of a population might be 165 cm to 170 cm.

4. **Regression Analysis**:

   - Used to model the relationship between a dependent variable and one or more independent variables.
   - Helps in predicting the value of the dependent variable based on the values of the independent variables.

5. **Sampling Methods**:

   - Techniques for selecting a representative sample from a population.
   - Common methods include random sampling, stratified sampling, and cluster sampling.

### Differences from Descriptive Statistics

1. **Focus**:

   - **Descriptive Statistics**: Focuses on summarizing and describing the characteristics of a dataset.
   - **Inferential Statistics**: Focuses on making inferences and predictions about populations based on sample data.

2. **Purpose**:

   - **Descriptive Statistics**: Provides insights and understanding of the dataset.
   - **Inferential Statistics**: Aims to generalize findings to a larger population and draw conclusions.

3. **Scope**:

   - **Descriptive Statistics**: Deals with data within the sample.
   - **Inferential Statistics**: Deals with making broader conclusions about the entire population.

4. **Examples**:

   - **Descriptive Statistics**: Mean, median, mode, standard deviation.
   - **Inferential Statistics**: Hypothesis testing, confidence intervals, regression analysis.

5. **Goal**:

   - **Descriptive Statistics**: Summarize and simplify data for easier interpretation.
   - **Inferential Statistics**: Make predictions, test hypotheses, and provide insights about populations.

---


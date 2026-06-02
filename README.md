# teaching-methods-analysis
# Statistical Analysis: Evaluation of School Teaching Methods

## Statistical Techniques & Methodology
To evaluate the effectiveness of the teaching methods, this project followed a structured statistical workflow:

* **Descriptive Statistics:** Utilized NumPy to calculate metrics like mean and standard deviation to summarize and compare student performance across both groups.
  
* **Hypotesis Testing (T-Test Histogram):** Conducted an Independent Two-Sample T-Test using SciPy. Instead of just checking a p-value, the analysis plots the studet grades distribution alongside the calculated statistical boundaries:

* **T-calculated (t-calculado):** The actual test statistic derived from the sample data.
* **T-critical (t-critico):** The threshold value determined by the significance level and degrees of freedom, defining the the rejection region.

### Hypotesis Setup:

* **Null Hypothesis:** There is no significant difference in the average grades between the teaching methods.
* **Alternative Hypothesis:** There is a statistically significant difference in the average grades between the teaching methods.

## Technologies Used
* **Python** (Core language)
* **NumPy** (Array manipulation and descriptive statistics)
* **SciPy** / **scipy.stats** (Statistical testing and T-Test variables)
* **Matplotlib** (Data visualization and statistical plotting)

## Key Insights and Conclusions 
After analysing the dataset and running the statistical pipeline, here are the main findings:

* **Descritptive Analysis:** The average grade for Teaching Method A was higher than the average grade for Teaching Method B.
* **Statistical Significance:** By plotting and comparing t-calculated against t-critical on the distibution graph, we visually and mathematically determined whether the performance gap between the tow methods is large enough to reject the null hypothesis.

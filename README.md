# A/B Testing: Work Environment and Mental Health Analysis

## Overview
This project explores the relationship between work environments (Remote vs. Office) and mental health scores using A/B testing techniques. The analysis leverages statistical methods to determine whether remote work environments significantly affect employees' mental health compared to traditional office settings.

## Dataset
The dataset is simulated and consists of 100 employees with the following features:
- **Employee_ID**: Unique identifier for each employee.
- **Work_Environment**: Categorical variable indicating "Remote" or "Office".
- **Mental_Health_Score**: A numerical score reflecting mental well-being, simulated from a normal distribution with some bias for remote workers.

## Objective
The main goal is to test the hypothesis:
- **Null Hypothesis (H₀)**: There is no significant difference in mental health scores between remote and office workers.
- **Alternative Hypothesis (H₁)**: Remote workers have significantly better mental health scores than office workers.

## Tools and Libraries
- **Python**: Programming language used for analysis.
- **Pandas**: Data manipulation and cleaning.
- **NumPy**: Numerical operations.
- **Matplotlib** & **Seaborn**: Data visualization.
- **SciPy**: Statistical testing.

## Methodology
1. **Data Simulation and Cleaning**:
   - Simulated a dataset with normal distribution for mental health scores.
   - Introduced slight bias to reflect real-world scenarios (better scores for remote workers).

2. **Descriptive Analysis**:
   - Examined distributions of mental health scores across groups.
   - Checked for missing values and duplicates.

3. **Visualization**:
   - Box plots and histograms to compare distributions between groups.

4. **Statistical Testing**:
   - **T-Test**: Independent two-sample t-test to evaluate mean differences.
   - **Effect Size**: Cohen's d to measure the practical significance of observed differences.

5. **Insights**:
   - Identified trends and evaluated the statistical significance of findings.

## Results
- The t-test revealed [insert result: "significant"/"non-significant"] differences in mental health scores.
- Remote workers demonstrated a [higher/lower] average mental health score compared to office workers.

## How to Run the Project
1. Clone this repository:
   ```bash
   git clone https://github.com/your_username/ab-testing-mental-health.git
   ```
2. Install required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn scipy
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook ab_testing_analysis.ipynb
   ```

## Future Improvements
- Extend analysis to real-world datasets.
- Incorporate additional factors influencing mental health, such as job role and work-life balance.
- Perform multi-group A/B testing to explore hybrid work models.

## Acknowledgments
This project was inspired by the need to assess the impact of workplace environments on employee well-being, a crucial consideration for modern organizations.

# AdMetrics Insights

**Analyze A/B testing data to drive actionable insights and optimize advertising strategies.**

---

## Project Overview

This project provides an in-depth analysis of data from an A/B test aimed at understanding the impact of advertising campaigns on conversion rates and revenue. Using Python, this project showcases data cleaning, exploratory analysis, statistical testing, and visualization techniques.

### Objectives

1. Calculate overall and cohort-specific metrics, including:
   - Conversion Rate (CR)
   - Value per Transaction (VPT)
   - Uplift
2. Assess whether advertising campaigns had a positive or negative impact.
3. Conduct statistical testing to measure the confidence of results.
4. Explore additional metrics for actionable insights.

---

## Dataset

The dataset includes information such as user demographics, device usage, session details, campaign costs, and conversion values. Key columns:
- `agegroup`, `gender`, `device`: User demographics and device information.
- `bidprice_usd`: Campaign cost.
- `value`: Conversion value (if a conversion occurred).
- `group`: A/B test assignment (`treatment` or `control`).
- `cohort`: The event month.

### Key Metrics
- **Conversion Rate (CR)**: Percentage of users who converted.
- **Value per Transaction (VPT)**: Average bid price per session.
- **Uplift**: Improvement in conversion rate due to the treatment group.

---

## Key Features of the Notebook

1. **Data Cleaning**:
   - Impute missing values for device and gender.
   - Fill missing conversion values with zero.
   - Feature engineering for `converted` status.
   
2. **Exploratory Data Analysis**:
   - Visualize missing data and distribution of key metrics.
   - Analyze cohort-wise performance trends.

3. **Statistical Testing**:
   - Perform Z-tests for comparing conversion rates.
   - Use T-tests to analyze bid price differences.
   - Multiple testing correction to account for statistical rigor.

4. **Visualization**:
   - Heatmaps for missing data.
   - Cohort-specific trend plots.
   - Bar and line charts for group comparisons.

5. **Business Insights**:
   - Determine if the ad campaign uplift is significant.
   - Suggest alternative metrics for a comprehensive evaluation.

---

## Instructions

1. Clone the repository: 
```bash git clone https://github.com/your-username/admetrics-insights.git ```
2. Install dependencies: 
```bash pip install -r requirements.txt```
3. Open the Jupyter Notebook: 
```bash jupyter notebook notebooks/experimentation_solution.ipynb```

---

### Results

#### Summary
- The treatment group exhibited an uplift in conversion rate of **X%** compared to the control group.
- Statistical tests confirm that the observed difference is significant at a confidence level of **95%**.
- Additional metrics such as **Value per Transaction** indicate opportunities for further optimization.

#### Recommendations
- Target high-performing cohorts for future campaigns.
- Explore demographic-based advertising strategies.

---

#### Future Enhancements
- Develop predictive models to forecast cohort performance.
- Integrate automation for regular A/B testing analyses.
- Extend reporting with dynamic dashboards.

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


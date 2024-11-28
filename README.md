# AdMetrics Insights

**Analyze A/B testing data to derive insights and optimize advertising strategies.**

## Project Overview

This project involves analyzing data from an A/B test to measure the impact of advertising strategies. The key objectives include:
1. Calculating overall and cohort-wise Conversion Rates, Value per Transaction, and Uplift.
2. Determining whether the advertising intervention provided a positive impact.
3. Evaluating confidence levels in the results.
4. Exploring additional metrics to provide actionable insights.

## Dataset

The dataset consists of user interaction data, including the following features:
- `agegroup`, `gender`, `device`: Demographic and device information.
- `bidprice_usd`: Cost of campaign events.
- `value`: Conversion value for events.
- `group`: A/B test assignment (`treatment` or `control`).
- `cohort`: Event month.

## Key Metrics

- **Conversion Rate (CR)**: Percentage of users converting, calculated for both treatment and control groups.
- **Value per Transaction (VPT)**: Average bid price per session.
- **Conversion Rate Uplift**: Percentage improvement in conversion rate due to treatment.

## Instructions

1. Clone the repository: `git clone https://github.com/your-username/admetrics-insights.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Open the Jupyter Notebook: `jupyter notebook notebooks/experimentation_solution.ipynb`

## Results

The analysis shows:
- [Summary of findings, e.g., "The treatment group had a conversion uplift of X%."]

## Future Enhancements

- Add predictive models to analyze factors influencing uplift.
- Automate reporting with Python scripts.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


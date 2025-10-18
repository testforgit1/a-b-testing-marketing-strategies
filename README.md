# A/B Testing for Optimizing Marketing Strategies

## Overview
This project conducts A/B testing on marketing campaign datasets to compare control and test groups, analyzing metrics like click-through rate (CTR) and conversion rates to recommend the optimal strategy.

## Project Details
- **Dataset**: Control and test campaign data (e.g., impressions, clicks, purchases)
- **Technologies**: Python, Pandas, NumPy, SciPy, Matplotlib
- **Outcome**: Recommended Test Campaign for superior CTR (p=0.0003)

## Features
- Data preprocessing with Pandas for column renaming and missing value imputation.
- Statistical analysis using t-tests to compare metrics (e.g., CTR, added to cart) with p-values and effect sizes.
- Visualization of results with Matplotlib for metric comparisons.

## Usage
- Run the Jupyter notebook `AB testing for optimizing marketing strategies.ipynb` to perform the analysis.
- Modify metric lists or preprocessing steps in the code as required.

## Results
- Significant difference in CTR (Test better) and added to cart (Control better) with p<0.05.
- Recommended Test Campaign for enhanced engagement and traffic potential.

## Challenges
- Addressed inconsistencies in column names and handled missing data effectively.
- Ensured statistical significance with appropriate sample size considerations.

## Future Improvements
- Add power analysis to determine optimal sample size.
- Include additional metrics like customer lifetime value (CLV) for deeper insights.

## Contact
- Author: Yeshwanth Bikkavolu
- Email: yeswanthbikkavolu@gmail.com
- LinkedIn: linkedin.com/in/naga-veera-y-29379a2ba

# Price Optimization Analysis
## Project Overview
This project aims to optimize product pricing in a supermarket chain to maximize sales volume. The analysis uses simulated sales data to evaluate the relationship between pricing strategies, promotions, and sales volume.
## Objectives
- Understand the impact of price changes and promotions on sales volume.
- Implement a linear regression model to predict sales volume based on pricing and promotions.
- Generate actionable insights to improve pricing strategies and maximize revenue.
## Methodology
1. **Data Generation:** Simulated data representing prices, promotions, and sales volume is created.
2. **Exploratory Data Analysis (EDA):** Analyze the distribution of sales volume, the effect of price changes, and the impact of promotions.
3. **Modeling:** Train a linear regression model to predict sales volume based on pricing and promotion data.
4. **Evaluation:** Evaluate model performance using Mean Squared Error (MSE) and R-squared (R2) metrics.
5. **Reporting:** Generate a PDF report summarizing the results, including visualizations and recommendations.
## How to Run the Project
1. **Install the required libraries:**
   Run the following command in the terminal to install all necessary libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn fpdf
   ```
2. **Run the script:**
   Execute the script using the following command:
   ```bash
   python script.py
   ```
3. **Check the outputs:**
   - `sales_data.csv`: Contains the simulated sales data.
   - PNG files: Various visualizations generated during the analysis.
   - `sales_model.pkl`: The trained linear regression model.
   - `sales_report.pdf`: A detailed PDF report of the analysis.
## Results
The analysis revealed a significant relationship between pricing, promotions, and sales volume. The trained linear regression model demonstrated effective prediction of sales volume with the following metrics:
- **Mean Squared Error (MSE):** Indicates the average squared difference between predicted and actual values.
- **R-squared (R2):** Represents the proportion of variance explained by the model.
## Key Insights and Recommendations
- **Price Elasticity:** The analysis shows that changes in price significantly affect sales volume, with promotions having a positive impact.
- **Optimal Pricing Strategy:** Adjusting prices while leveraging promotions can enhance sales performance and maximize revenue.
- **Further Analysis:** Consider expanding the model to include other variables, such as seasonal effects or product categories, to improve predictions.
## Requirements
This project requires the following software and libraries:
- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- fpdf

# SupplyChainLogistics


Modern supply chains are increasingly complex, with challenges such as:

Delivery Delays: Caused by traffic congestion, port delays, and
warehouse inefficiencies.

High Operational Costs: Inefficient fuel usage and unpredictable
demand.

Inventory Management: Imbalances between demand and supply
result in surplus or deficits.

Our motivation stems from solving these challenges by:

Improving delivery efficiency and identifying causes of delays.

Minimizing operational risks using statistical tests and risk classification
models.

Optimizing inventory management with mathematical modeling.

Forecasting trends using time-series analysis.

Goal: To reduce delays, optimize resources, and provide a data-driven
decision support system for supply chain managers.

In the competitive landscape of e-commerce, effective inventory management and sales forecasting are crucial for
maintaining optimal stock levels, reducing excess inventory, and ensuring timely deliveries.
Analyzing historical data on inventories, sales, and shipments can reveal trends and patterns that
inform decision-making and strategic planning.

Methodology:
Descriptive Analytics:
 - Data visualization using libraries like Matplotlib and Seaborn to analyze historical trends.
 - Summary statistics to understand inventory turnover rates and sales patterns.
Predictive Analytics:
 - Time series analysis to forecast future sales using techniques like ARIMA, Exponential
Smoothing, or Prophe
Statistical Analysis:
 - Chi-square tests to analyze the relationships between sales and inventory changes.

1 - Statistical tests help identify patterns in the data, making sure
strategies are based on facts and not assumptions.

2 - Time-series models allow businesses to predict future needs,
helping them prepare for changes in demand and avoid
inventory issues.

3 - Optimization techniques make sure that resources like
inventory, transportation, and labor are used in the most
efficient way, saving costs and improving overall performance.

Bayesian Analysis: To compare the predictive
power of two conditions (traffic vs. port
congestion) in identifying "High Risk" routes.

The T-test is used to compare the mean
delivery_time_deviation between two groups:
high-risk and low-risk classifications.

Chi-Square test was used between delay
probability and risk_classification, to evaluate
the independence between categorical
variables, helping to identify significant
relationships within the dataset.

Time series analysis: ARIMA models delivery
deviations with external predictors, while
SARIMA adds seasonality to capture periodic
trends.

Bayesian Analysis: To compare the predictive
power of two conditions (traffic vs. port
congestion) in identifying "High Risk" routes.

The T-test is used to compare the mean
delivery_time_deviation between two groups:
high-risk and low-risk classifications.

Chi-Square test was used between delay
probability and risk_classification, to evaluate
the independence between categorical
variables, helping to identify significant
relationships within the dataset.

Time series analysis: ARIMA models delivery
deviations with external predictors, while
SARIMA adds seasonality to capture periodic
trends.

CCA identifies relationships between two
sets of variables by maximizing their
correlations, helping to uncover
interdependencies in features like
delivery_time_deviation and
warehouse_inventory.

Monte carlo simulation: Used random
sampling to predict outcomes and
manage uncertainties in logistics systems.

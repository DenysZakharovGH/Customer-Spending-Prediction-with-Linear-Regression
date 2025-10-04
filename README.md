📊 Customer Spending Prediction with Linear Regression

This project explores a customer dataset (Ecommerce Customers.csv) to discover important correlations between variables and to predict the yearly amount of money a customer will spend in the future.

Using both custom Linear Regression (implemented from scratch) and scikit-learn’s LinearRegression, we:

Perform exploratory data analysis (EDA) with pairplots and scatter plots.

Identify strong correlations between variables like Length of Membership, Time on App, Time on Website, and the target variable Yearly Amount Spent.

Train regression models to predict future spending behavior.

Compare performance using Mean Squared Error (MSE) on training and test sets.

🔍 Key Findings

Length of Membership has the strongest correlation with Yearly Amount Spent.

Our regression models confirm this and provide accurate predictions for customer spending.

Both custom and scikit-learn models give similar results, validating the scratch implementation.

🖼️ Visualizations
Pairplot of dataset variables

Helps identify potential correlations:


Scatter plot of Length of Membership vs Yearly Amount Spent

Shows a clear positive linear relationship:


Regression line fit

The blue line shows the regression prediction vs real customer data:


🚀 Applications

Predict future revenue from customers based on their behavior.

Identify which features drive customer spending the most.

Provide actionable insights for marketing and customer retention strategies.

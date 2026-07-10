# Price-Optimisation-model

### Project Overview

Developed a pricing optimisation model for a luxury candle manufacturer selling through Amazon to determine the selling price that maximises profitability. Using three years of historical sales data, the project analysed the relationship between price and customer demand by applying polynomial regression to model non-linear pricing behaviour. The resulting demand model was combined with variable cost analysis to estimate profit across different price points, while Excel Solver was used to identify the optimal selling price. The analysis concluded that a selling price of **£10.20** would maximise daily profit, generating an estimated **£1,432** per day from approximately **140 units** sold. The project demonstrates the application of statistical modelling, optimisation techniques, and Excel-based analytics to support commercial pricing decisions.

### Business Problem

Auroiwick, a luxury candle manufacturer selling products through Amazon, wants to identify the optimal selling price that would maximise profitability. The company had historically adjusted prices based on market conditions, but management required a data-driven approach to understand the relationship between price, demand, and costs to determine the most profitable pricing strategy. 

### Tools Used

- Power Query
- Excel

### Techniques applied

- Logistic Regression
- Price Optimisation
- Statistics
- Data Visualisation

### Methodology

- Imported historical Price and Quantity data into Power Query using an OData Feed API endpoint
- Cleaned and transformed sales data for analysis
- Calculated variable costs and contribution profit per unit
- Visualised the relationship between Price and Quantity Sold using a scatter plot
- Applied polynomial transformation by creating a squared price variable to capture non-linear demand relationships
- Performed regression analysis to estimate the relationship between price and demand
- Interpreted regression coefficients and evaluate model performance
- Developed a demand prediction model using the regression equation
- Created a profit optimisation model combining predicted demand, selling price, and variable costs
- Used Excel Solver to identify the profit-maximising selling price

### Key Insights

- Product prices ranged between **£9.00 and £12.00** over the three-year analysis period.
- Historical profit increased as the selling price increased, before declining beyond a certain price point, indicating an optimal pricing range.
- Regression analysis identified a **significant non-linear relationship** between price and demand. The positive coefficient for **Price** (β = 1475.35, *p* < 0.05) and the negative coefficient for **Price²** (β = -7318.22, *p* < 0.05) indicate that demand initially increases with price before decreasing at higher price levels.
- Excel Solver identified **£10.20** as the profit-maximising selling price. At this price, the model predicts a daily demand of approximately **140 units**, resulting in an estimated daily profit of **£1,432**.


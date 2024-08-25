# CostOptimization
Analyzing historical sales data with price elasticity to assess how customers might respond to future price adjustments.

**AIM**

Utilizing data from a Cafe, the objective is to apply price elasticity concepts to historical sales data to evaluate how customer demand for coffee responds to price changes. By doing so, the aim is to determine the optimal pricing strategy that maximizes profit, balancing between setting prices too high or too low.

**METHODOLOGY**

1. **Exploratory Data Analysis**
   - Exclude variables such as SchoolBreak and Weekends, which affect sales but do not influence pricing, as they are irrelevant to the analysis.
   - Identify and address any missing data.
   - Examine and integrate various aspects of the merged data.

2. **Modeling**
   - **Price Elasticity of Demand (PED):** This measure assesses how the quantity demanded of coffee changes in response to price adjustments, holding all other factors constant. It quantifies the percentage change in quantity demanded for a 1% change in price. The formula for price elasticity (ǫ) is:

     $$
     e = \frac{\%\Delta Q}{\%\Delta P}
     $$

   - Here, let's analyze the sales data of a Cafe that sells coffee. The goal is to determine the ideal price point to maximize profit. High prices tend to reduce sales, while low prices increase sales but may lower total profit. The main aim is to identify the optimal price that maximizes profit by exploring the linear relationship between quantity sold and price using linear regression.

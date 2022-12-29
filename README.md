# Unsupervised-Learning
## Repository for unsupervised learning techniques

**mtcars.csv**

*Data Background* 

Hierarchical cluster analysis performed on a dataset containing vintage cars. The data was extracted from the 1974 Motor Trend US
magazine, and comprises fuel consumption and 10 aspects of automobile design and performance for 32 vintage automobiles (1973–74
models).

The purpose of hierarchical cluster analysis is to explore how vintage cars are clustered together and group similar vintage cars into the
same cluster. Customers may have multiple choices to purchase given their preference of automobile design and performance features.

*Data Dictionary*

model: Model of vehicle

mpg:Miles/(US) gallon,the determinant of fuel efficiency

cyl: Number of cylinders,a good proxy for the total amount of power the engine can generate.

disp: Displacement (cu.in.),measures an engine’s power output

hp: Gross horsepower,the number of turns of the drive shaft for every one rotation of the wheel axle
drat: Rear axle ratio, the number of turns of the drive shaft for every one rotation of the wheel axle.

wt: Weight (1000 lbs)

qsec: 1/4 mile time, a performance measure, primarily of acceleration

vs: Engine (0 = V-shaped, 1 = straight),a binary variable signaling the engine cylinder configuration a V-shape (vs=0) or Straight Line
(vs=1). V==0 and S==1

am: Transmission (0 = automatic, 1 = manual),a binary variable signaling whether vehicle has automatic (am=0) or manual (am=1)
transmission configuration.

gear: Number of forward gears

carb: Number of carburetors

---

**mall_customers.csv**

*Data Dictionary*

CustomerID: Unique ID assigned to the customer.

Gender: Gender of the customer.

Age: Age of the customer.

Annual_Income (k$): Annual Income of the customer.

Spending_Score (1-100): Score assigned by the mall based on customer behavior and spending nature.

---

**Pharmaceuticals.csv**

*Data Background*

An equity analyst is studying the pharmaceutical industry and would like your help in exploring and 
understanding the financial data collected by her firm. Her main objective is to understand the 
structure of the pharmaceutical industry using some basic financial measures. 

*Data Dictionary*

Financial data gathered on 21 firms in the pharmaceutical industry are available in the 
file Pharmaceuticals.csv. For each firm, the following variables are recorded: 

Market capitalization (in billions of dollars): how much the company is worth as determined by 
the stock market. 

Beta:the relationship between systematic risk and expected return for assets (usually stocks).High-
beta stocks are supposed to be riskier but provide higher return potential; low-beta stocks pose less 
risk but also lower returns. 

Price/earnings ratio: a company's share price to its earnings per share. A high P/E ratio could 
mean that a company's stock is over-valued, or else that investors are expecting high growth rates in 
the future. 

ROE-Return on equity:a measure of financial performance calculated by dividing net income by 
shareholders' equity 

ROA-Return on assets: an indicator of how profitable a company is relative to its total assets 

Asset turnover: the ratio of total sales or revenue to average assets

Leverage: the use of debt (borrowed funds) to amplify returns from an investment 

Estimated revenue growth:estimated increase, or decrease, in a company's sales 

Net profit margin: the ratio of net profits to revenues for a company 

Median recommendation (across major brokerages): recommendation of buying 

Location of firm’s headquarters: the country where this company is located 

Stock exchange on which the firm is listed: the places where stocks of this company are traded. 

---
**groceries.csv**

*Data Background* 

Grocery dataset contains 9,835 transanctions from a grocery store. Each row represents one transaction, showing the items/products that were purchased in this partitucalr transaction. We will perform market basket analysis to generate association rules, and indentify the strong rules.
 

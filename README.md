# Project Financial Market Analysis
## This project was made to complete the course Python for Finance offered jointly by Trading com Dados and Florida International University

### 1. Introduction
The project involves conducting data analysis of the financial market and macroeconomic scenario using Python.
We chose tech stocks APPL, MSFT, AMZN, GOOGL and META with period from 2020-01-01 to 2023-12-31(to get till the most recent date)
The python libraries used were: 
- yfinance, nasdaqdatalink to get stock and macroeconomic data
- pandas to data analysis
- plotly to graphical design

### 2. Stocks analysis
#### 2.1. We can see some stastistics values below
![statistics](https://github.com/Jtani/project-financialmarket-analysis/assets/16908394/919dcd27-0c15-4753-8d62-5e37f5c7ae7d)
- We can note that META it's highly volatile as the standard devion is 70
- MSFT have the highest average value and GOOGLE have the lowest

#### 2.2. Graphic comparing the stock prices
![stockcomparison](https://github.com/Jtani/project-financialmarket-analysis/assets/16908394/14b08213-a5d0-4629-8c72-724de6ec26ca)
- We can observe that Google and Apple, started almost with the same price but at the moment Apple has a higher price
- META went down abbrubtaly in 2022 but recovered this year
- 
#### 2.3. Graphic comparing the stock prices normalized
![stockcomparison-norm](https://github.com/Jtani/project-financialmarket-analysis/assets/16908394/097946c3-bf2c-4dd2-a31b-9081c9fb4fb5)
- We note here that Apple has ther better performance among the stocks, and that META was the worst and couldn't assume that in the previous graphic

### 3. Macroeconomic Analysis
#### 3.1. Graphic SP500 x Interest Rates
![macroeconomic-sp-ir](https://github.com/Jtani/project-financialmarket-analysis/assets/16908394/8ac53da3-8774-4e14-90ac-6697440b3030)
- Unfortunately we only have values of the interest rates until july 2022
- It seems that in higher interest rates SP500 go down and in lower interest rates SP500 goes up

#### 3.2. Graphic SP500 x Inflation
![macroeconomic-sp-inf](https://github.com/Jtani/project-financialmarket-analysis/assets/16908394/68362d90-37c8-4fca-a6f1-048ff4f22277)
- In the period of 2020 and 2021 the trend between inflation and sp500 looked at the same direction but after 2022 they look inversely proportional

### 4. Panel comparing stocks in relation to fundamental data
![newplot](https://github.com/Jtani/project-financialmarket-analysis/assets/16908394/53650415-3675-4b47-b54a-830d8336ec45)
- Apple has the largest MarketCap and Entreprise Value but don't have the better Revenue neither Profit Margin
- Also Amazon has the largest Revenue despite having the worst Profit Margin and Operating Margin
- Google(Alphabet Inc.) almost always appears 3rd in rank, it looks like a stable company

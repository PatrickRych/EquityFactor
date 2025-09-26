# Equity Factor Analysis

## Objective

### What is factor analysis?
Factor trading/investing is an approach that targets specific drivers of return across asset classes. These factors are considered systematic and can be applied broadly across markets, and can be harvested through rule-based strategies. Through research and testing, I look for factors that are applicable and carry statistical significance in the effect of your corresponding thesis. You may think past winners continue to outperform, so you study momentum driven signals, and subsequently long those which have a (+) momentum and short (-) those with negative momentum signals. In trading, these factor signals are often translated into systematic allocation models or multi-factor portfolios. 

### Why use a factor method?

**Persistence & Pervasiveness:**
-Many factors work across asset classes, geographies, and time.
-Factor premiums are not a fluke but have economic rationale (risk-based or behavioral).
-The factor overlay systmetizes your trading strategy. 
**Risk vs. Behavioral Theories:**
-Some factors (e.g., value, size) are explained by traditional risk compensation models.
-Others (e.g., momentum) may be due to investor biases (e.g., underreaction, herding).  
**Combining Factors Improves Sharpe Ratios:**
-A multi-factor approach can reduce drawdowns and cyclicality.
-Factors are not perfectly correlated — combining them provides diversification benefits .
**Practical Challenges:**
-Real-world implementation faces turnover costs, data mining risks, and changing market regimes.
-Factor returns decay over time if they become crowded or arbitraged away.
-Technical factors focus on the past and do not provide the implied market 
**Academic vs Practitioner View:**
-Academics focus on long-term significance and robustness.
-Practitioners focus on real-time performance, scalability, and trading feasibility

# Analysis

## Historical Analysis: 
<img width="2487" height="839" alt="EquityFactor(1)" src="https://github.com/user-attachments/assets/a8ee1d00-34db-4f93-83d8-a8c9825f1c20" />

**Multi-Factor Market Regime Dashboard Summary**
The histotic analysis tab gives us the quantitative lense into stock behaviour, tracing patterns from the past to the present. Is offers a non-trivial way for systematizing a strategy rather than searching for information, rather than merely searching for information to confirm existing biases. By grounding decisions in systmatic analysis, traders gain a structured roadmap for scaling positions based on size, time and strategy type. 


**Analytical Output:**
Performance metrics are segmented by factor (e.g., CMF, LT Momentum, EMA Mult.) with:
- Return Distributions (mean, median, min/max)
- Hit Rates: % of days above/below the threshold return
- Average Return by Regime (e.g., CMF > threshold shows 2.1% return over 30-day horizon)
  
![EquityFactor(2) - ParamterAdjustments](https://github.com/user-attachments/assets/55c4810d-2319-4eb2-b25d-73c005bf4612)

## Visualizations

#### Momentum Visualization - MACD  
![Macd](https://github.com/user-attachments/assets/79dd0def-f71d-41fc-b163-916047f9678d)

#### Momentum Visualization - Chaikin Money Flow 
![Visual(3)_CMF](https://github.com/user-attachments/assets/e0346478-5063-462c-9e9f-2f4f28cc0e48)

#### Price Normalized and Realized Volatility 
![Visual(1)PriceNormalized Vol](https://github.com/user-attachments/assets/ccfe672f-9482-42de-a223-6c6986f15b59)

#### Max Drawdown Visualization
![MaxDrawdown](https://github.com/user-attachments/assets/71c9a952-9158-494d-b26b-9423bc24ef50)



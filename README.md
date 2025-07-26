# Equity Factor Analysis

## Objective

### What is factor analysis?
Factor trading/investing is an approach that targets specific drivers of return across asset classes. These factors are considered systematic and can be applied broadly across markets, and can be harvested through rule-based strategies. Through research and testing, we look for factors that are applicable and carry statistical significance in the effect of your corresponding thesis. You may think past winners continue to outperform, so you study momentum driven signals, and subsequently long those which have a (+) momentum and short (-) those with negative momentum signals. In trading, these factor signals are often translated into systematic allocation models or multi-factor portfolios. 

### Critical Thinking:

**Persistence & Pervasiveness:**
-Many factors work across asset classes, geographies, and time.
-Factor premiums are not a fluke but have economic rationale (risk-based or behavioral).
**Risk vs. Behavioral Theories:**
-Some factors (e.g., value, size) are explained by traditional risk compensation models.
-Others (e.g., momentum) may be due to investor biases (e.g., underreaction, herding).
**Combining Factors Improves Sharpe Ratios:**
-A multi-factor approach can reduce drawdowns and cyclicality.
-Factors are not perfectly correlated — combining them provides diversification benefits .
**Practical Challenges:**
-Real-world implementation faces turnover costs, data mining risks, and changing market regimes.
-Factor returns decay over time if they become crowded or arbitraged away.
**Academic vs Practitioner View:**
-Academics focus on long-term significance and robustness.
-Practitioners focus on real-time performance, scalability, and trading feasibility

# Analysis on SPY 

## SPY Historical Analysis: 
![image](https://github.com/user-attachments/assets/8a50d1ed-7238-448f-b514-a0a61b271267)


### Indicator Dynamic Parameter Adjustments 

**Multi-Factor Market Regime Dashboard Summary**
- This dashboard was designed to dynamically analyze how multiple technical indicators and market signals influence forward return profiles over a customizable window (e.g., 30-day returns). The core goal was to isolate statistically relevant market conditions by adjusting parameters across momentum, volume, and volatility indicators.

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

## Options Pricing Models 

### Black-Scholes 

The following models are designed to:

- Price vanilla options under standard BSM assumptions
- Compare theoretical vs realized outcomes for model validation
- Identify risk to reward for various structures 
- Simulate expected value under different market regimes

![OptionPricingModel](https://github.com/user-attachments/assets/1364bac5-4401-4f2e-9693-57d96dad9ca5)

Practical Application: 

The models presented here are designed to deconstruct the current market landscape and extract actionable insights. When a backtested strategy generates a signal, I immediately reference the live implied option chain. While I currently lack direct access to implied volatility surface data for integration into the model, I bridge that gap by comparing implied market pricing with realized pricing—as shown in the pricing simulator. 

Additionally, I compare the historical rank of implied volatility with that of realized volatility over the same period—derived from data provided by my brokerage. This gives me a clearer view of how volatility is currently priced across different deltas and expirations. While I don't have a full implied volatility surface to visualize skew, this relative rank structure allows me to infer whether I should be a net buyer or seller of options, and whether spreads offer a more favorable risk-reward payoff than outright positions.

I actively backtest strategies across different volatility regimes and signal types, helping me formulate different factor based strategies. 

My _backtest model_ tests my hypothesis and determines the effectivness and the strategy type across history
The Backtest model can be found in the project arhive. 

### Log-Normal Distribution Visualizations 
![Visual_OptionsPricing](https://github.com/user-attachments/assets/8f8e270b-fcbe-48f3-852e-6fdd85a76806)


## Project Archive 

| <a href="https://github.com/PatrickRych/Project">LandingPage </a>
| <a href="https://github.com/PatrickRych/Portfolio-Manager">Project Archive </a>
****

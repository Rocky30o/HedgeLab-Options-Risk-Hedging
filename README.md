# HedgeLab — Options Risk & Hedging Analysis

HedgeLab is a quantitative finance research project that analyzes how protective put options can reduce downside risk for an equity portfolio.

The project combines option pricing, Greeks, delta hedging, scenario analysis, and Monte Carlo simulation to compare hedged and unhedged portfolio outcomes.

## Problem

An investor holding a large equity position is exposed to downside risk.

The project evaluates:

- How much downside protection a protective put provides
- How much the hedge costs
- How option Greeks describe portfolio sensitivity
- How hedged and unhedged portfolios behave under different market scenarios
- How the distribution of portfolio outcomes changes under Monte Carlo simulation

## Methodology

### 1. Black-Scholes Option Pricing

European call and put options are priced using the Black-Scholes model.

### 2. Greeks Analysis

The project calculates:

- Delta
- Gamma
- Vega
- Theta
- Rho

### 3. Delta Hedging

The portfolio's stock exposure is compared with the option delta to estimate the number of contracts required for an approximately delta-neutral hedge.

### 4. Scenario Analysis

The portfolio is tested under different market conditions:

- Strong rally
- Moderate rally
- Base case
- Moderate decline
- Market crash

### 5. Monte Carlo Simulation

10,000 simulated stock-price paths are generated using a Geometric Brownian Motion framework.

The resulting distributions are used to compare:

- Unhedged P&L
- Hedged P&L
- Downside percentiles
- Worst-case outcomes
- Probability of loss

## Technologies

- Python
- NumPy
- Pandas
- SciPy
- Matplotlib
- Monte Carlo Simulation
- Black-Scholes Model
- Quantitative Risk Analysis

## Key Insight

The protective put reduces downside exposure at the cost of an upfront option premium and reduced upside participation.

The project demonstrates how derivatives can be used as a risk-management tool rather than simply as a speculative instrument.

## Disclaimer

This project is an educational quantitative-finance simulation using model assumptions and does not constitute financial advice or a live trading system.

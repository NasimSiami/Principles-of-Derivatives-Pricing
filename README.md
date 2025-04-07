# Credit Risk Modeling: Distance to Default and Probability of Default

This project models credit risk using a structural approach to calculate **Distance to Default (DD)** and **Probability of Default (PD)**, based on the firm's asset value, volatility, debt obligations, and time to maturity. It is inspired by the Merton model and developed as part of a financial risk analysis course.

## 📘 Overview

The notebook covers:

- Calculation of distance to default using asset value and debt structure
- Estimation of the probability of default using the standard normal distribution
- Sensitivity analysis on model parameters (optional extension)
- Clean and reusable Python function for credit risk analytics

## 🔍 Key Formula

Distance to Default:
dd = [ln(A0/B) + (α - 0.5 * σ²) * T] / (σ * sqrt(T))


Probability of Default:
pd = N(-dd)


Where:
- `A0`: Asset value  
- `B`: Debt threshold (barrier)  
- `α`: Expected return on assets  
- `σ`: Asset volatility  
- `T`: Time to maturity  
- `N(.)`: Cumulative normal distribution

## 🔧 Technologies

- Python
- NumPy
- SciPy
- Matplotlib
- Seaborn
- Pandas

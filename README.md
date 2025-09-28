# Marci: Marketing Analytics and ROI Calculator

[![Tests](https://github.com/yourusername/marci/workflows/Tests/badge.svg)](https://github.com/yourusername/marci/actions)
[![Python](https://img.shields.io/badge/python-3.8%2B-blue.svg)](https://www.python.org/downloads/)

**Marci** is a comprehensive Python package for marketing analytics, campaign optimization, and ROI calculations.

## 📊 Interactive Documentation

👉 **[View Interactive README.ipynb](README.ipynb)** - Complete examples with live outputs!

## 🚀 Features

- 🎯 **Campaign Simulation**: Realistic campaign performance modeling with seasonality, conversion delays, and elasticity
- 📊 **Portfolio Optimization**: Multi-campaign budget allocation and performance analysis
- 📈 **Statistical Distributions**: Advanced probability distributions for modeling uncertainty
- 🔄 **Elasticity Analysis**: Marketing mix modeling and response curve analysis
- 📅 **Seasonality Modeling**: Time-series patterns and seasonal adjustments
- ⏱️ **Conversion Delay**: Realistic conversion timing modeling
- 📊 **Visualization**: Built-in plotting and charting capabilities

## 📦 Installation

```bash
pip install marci
```

## 🎯 Quick Start

```python
import marci
from marci import Campaign, Portfolio

# Create a campaign
campaign = Campaign(
    name="My Campaign",
    cpm=10,
    cvr=0.02,
    aov=100,
    budget=1000
)

# Create a portfolio
portfolio = Portfolio([campaign])

# Optimize budgets
optimal = portfolio.find_optimal_budgets(total_budget=5000)
```

## 🧪 Testing

```bash
# Run all tests
pytest tests/ -v

# 218 tests covering all functionality
```

## 📚 Documentation

For complete examples and interactive demonstrations, see **[README.ipynb](README.ipynb)**.

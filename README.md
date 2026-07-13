# Portfolio Optimization Library

A Python library for quantitative portfolio optimization.

## Features

- Mean-Variance Optimization
- Risk Parity
- Maximum Sharpe Portfolio
- Black-Litterman (coming soon)
- Hierarchical Risk Parity (coming soon)

## Installation

```bash
pip install yfinance .
```

## Example

```python
from portfolio import MeanVarianceOptimizer

optimizer = MeanVarianceOptimizer()

optimizer.fit(prices)

print(optimizer.weights)
```

## Future Work

- Bayesian Portfolio Optimization
- Transaction Costs
- Robust Optimization
- Factor Models

## Author

Andreas Lejdå

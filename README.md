# CIRL Portfolio Management

An implementation of Cooperative Inverse Reinforcement Learning (CIRL) for portfolio management with online preference learning.

## Quick Start

### 1. Create a Virtual Environment

```bash
# Create virtual environment
python3 -m venv cirl_env

# Activate it
# On macOS/Linux:
source cirl_env/bin/activate
# On Windows:
cirl_env\Scripts\activate
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the Notebook

```bash
# Start Jupyter Lab
jupyter lab

# Or use Jupyter Notebook
jupyter notebook
```

Then open `cirl_portfolio_agent.ipynb` and run all cells.

## Structure:

- **Portfolio Environment**: Simple simulator with 1 risky asset + cash, Gaussian returns, transaction costs
- **Human Model**: Boltzmann-rational agent with risk and turnover preferences
- **CIRL Agent**: Bayesian belief maintenance with active querying and greedy control
- **Baseline Agent**: No-query comparison baseline
- **Experiments**: 100-episode evaluation with statistical analysis
- **Visualizations**: performance and belief evolution

## System Requirements

- Python 3.8 or higher

## Project Structure

```
.
├── cirl_portfolio_agent.ipynb  # Main notebook
├── requirements.txt                  # Python dependencies
└── README.md                         # This file
```

```

```

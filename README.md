# Time-Series Models: A Comparative Analysis

## Overview
This repository provides a systematic benchmarking framework to evaluate the robustness of various time-series forecasting models under controlled concept drift scenarios. We generate synthetic multivariate data with injected drifts and compare classical and modern architectures—ARIMA, Prophet, LSTM, CNN, and TimeMoE—across multiple evaluation regimes.


## Features
- **Controlled Drift Injection**: Create synthetic time series with sudden and gradual distributional shifts.  
- **Multi-Model Benchmarking**: Evaluate ARIMA, Prophet, LSTM, CNN, and TimeMoE under identical conditions.  
- **Multiple Regimes**: Test in stable-only, drift-only, mixed sampling, extended training/short testing, and rolling-window streaming.  
- **Robustness Metrics**: Calculate RMSE and robustness ratios to quantify performance degradation.  
- **Streaming Pipeline**: Implement sliding-window evaluation to mimic a real-time forecasting environment.

## Getting Started

### Prerequisites
- Python 3.8+  
- pip  
- Virtual environment tool of your choice (venv, conda, etc.)

### Installation
```bash
# Clone the repository
git clone https://github.com/waasi1709/TimeSeriesAnalysis.git
cd TimeSeriesAnalysis

# Create and activate a virtual environment
python -m venv env
source env/bin/activate      # Linux/macOS
env\Scripts\activate         # Windows

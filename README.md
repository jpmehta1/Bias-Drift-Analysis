# Bias Drift Analysis in LLMs via Prompt Framing

This project investigates how different prompt framings can introduce or amplify biases in Large Language Models (LLMs). By systematically varying prompt structures and analyzing model outputs, we aim to understand how subtle changes in prompt formulation can lead to significant variations in model behavior and potential bias drift.

## Project Overview

The analysis focuses on:
- Identifying different framing techniques in prompts
- Measuring bias drift across various demographic and contextual dimensions
- Developing metrics to quantify bias amplification
- Providing insights for more responsible prompt engineering

## Getting Started

### Prerequisites

- Python 3.8+
- Jupyter Notebook
- Required Python packages (see `requirements.txt`)

### Installation

1. Clone this repository:
   ```bash
   git clone [your-repository-url]
   cd [repository-name]
   ```

2. Create and activate a virtual environment (recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Open the Jupyter notebook:
   ```bash
   jupyter notebook "Bias Drift Analysis in LLMs via Prompt Framing.ipynb"
   ```

2. Follow the notebook sections to:
   - Load and preprocess data
   - Run bias analysis experiments
   - Visualize results
   - Interpret findings

## Project Structure

```
project-root/
│
├── data/                   # Data files
│   ├── raw/               # Raw data
│   └── processed/         # Processed data
│
├── notebooks/             # Jupyter notebooks
│   └── Bias Drift Analysis in LLMs via Prompt Framing.ipynb
│
├── src/                   # Source code
│   ├── analysis/         # Analysis modules
│   ├── visualization/    # Visualization utilities
│   └── utils/            # Helper functions
│
├── results/              # Output files and visualizations
├── requirements.txt      # Python dependencies
└── README.md            # This file
```

## Contact

[Jeet Mehta] - [jpmehta@wisc.edu]  
[Project Link](https://github.com/jpmehta1/Bias-Drift-Analysis)

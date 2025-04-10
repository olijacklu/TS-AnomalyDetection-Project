# Time Series Anomaly Detection: A Comprehensive Evaluation

## Overview
This repository contains the implementation and experiments based on the paper "Anomaly Detection in Time Series: A Comprehensive Evaluation" [Schmidl et al., 2022]. We evaluate various anomaly detection techniques on time series data and provide tools for benchmarking, ensemble creation, and performance analysis.

## Project Structure
```
├── Anomaly_Detection_in_Time_Series_A_Comprehensive_Evaluation.pdf  # Original paper
├── data/                          # Dataset directory
├── ensemble.ipynb                 # Ensemble method implementation
├── generated_data-evaluation-results.csv  # Results from generated data
├── get_default_scores.ipynb       # Default hyperparameter evaluation
├── gridsearch.ipynb               # Hyperparameter optimization
├── gutentag_data_generator.ipynb  # Synthetic dataset generator
├── models/                        # Saved model directory
├── outputs/                       # Logging and output files
├── performance_evaluation.ipynb   # Algorithm performance assessment
├── plots_tables.ipynb             # Visualization of results
├── README.md                      # Project documentation
├── results/                       # Output results directory
├── scores_calculator.ipynb        # Tutorial and algorithm setup
├── tsad-evaluation-results-summary.csv  # Summary evaluation results
├── tsad-evaluation-results.csv    # Detailed evaluation results
└── worst_performing_datasets.csv  # Analysis of difficult datasets
```

## Key Features
- Comprehensive evaluation of unsupervised anomaly detection algorithms on time series data
- Hyperparameter optimization through grid search and random search
- Ensemble methods to improve detection performance
- Synthetic data generation for controlled experiments
- Performance visualization and comparative analysis

## Installation

### Requirements
- Docker (required for running the environment)

### Setup
1. Install Docker by following the instructions at: https://docs.docker.com/engine/install/
2. Launch Docker and ensure it's running in the background
3. Clone this repository:
   ```
   git clone https://github.com/yourusername/time-series-anomaly-detection.git
   cd time-series-anomaly-detection
   ```
4. Launch Jupyter through Docker to access the notebooks

## Usage Guide

### Notebooks
- **scores_calculator.ipynb**: Tutorial for setting up and running algorithms
- **performance_evaluation.ipynb**: Evaluate algorithms on datasets and visualize results
- **gridsearch.ipynb**: Optimize hyperparameters for any algorithm on any dataset
- **get_default_scores.ipynb**: Evaluate algorithms with default hyperparameters
- **ensemble.ipynb**: Create optimal ensembles from various algorithms
- **gutentag_data_generator.ipynb**: Generate synthetic time series with configurable anomalies
- **plots_tables.ipynb**: Generate visualizations and tables for analysis

### Workflow Example
1. Use `performance_evaluation.ipynb` to test algorithms on your datasets
2. Run `gridsearch.ipynb` to find optimal parameters for promising algorithms
3. Combine top-performing methods with `ensemble.ipynb`
4. Visualize and analyze results with `plots_tables.ipynb`

## Results
The repository includes evaluation results for multiple algorithms across various datasets:
- AUC-ROC and AUC-PR metrics
- Parameter sensitivity analysis
- Ensemble performance
- Comparative analysis with state-of-the-art methods

## Contributing
Contributions are welcome! Please feel free to:
- Add new algorithms
- Include additional datasets
- Improve evaluation metrics
- Enhance visualization methods

## Contact
For questions or inquiries, please contact:
- olijacklu@gmail.com
- paulohenriquecrs@hotmail.com

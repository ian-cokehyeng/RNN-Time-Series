# RNN Hyperparameter Tuning to Forecast Daily MW with 30-day Gap

A compact and informative demonstration to show how to forecast a time series with a 30-day gap using a double-stacked GRU model, built via the `tensorflow` library. This notebook demonstrates the use of the lookback window size, dropout rate, and recurrent dropout rate as hyperparameters for tuning.

## Prerequisites

Before you begin, ensure you have met the following requirements:
- You have installed the latest version of [Conda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html).

## Installation

To install this project, follow these steps:

```bash
conda env create -f environment.yml -n custom_env_name
```

This command will create a new Conda environment that includes the dependencies needed for the project.

## Usage

To use this project, follow these steps:

```bash
conda activate <env_name>
jupyter notebook
```

Replace `<env_name>` with the name of the Conda environment specified above. This will activate the environment and start Jupyter Notebook, where you can open and run the notebook file.

## Contributors

The following individuals who have contributed to this project:

- Ian CoKehyeng

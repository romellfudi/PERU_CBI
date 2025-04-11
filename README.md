# PERUVIAN SENSOR BRAIN DATABASE (PERU_CBI)

Author: Romell Dominguez

## Project Overview
This repository contains data and analysis tools for the Peruvian Sensor Brain Database (PERU_CBI), a collection of EEG (electroencephalogram) recordings for cerebellar analysis. The project focuses on analyzing brain activity patterns, with particular attention to ictal (seizure) and interictal (between seizures) states.

## Notebook Content
The `Cerebellar_Analysis.ipynb` notebook provides comprehensive tools for analyzing the EEG data:

- **Data Loading and Processing**: Loads EEG data from various patients in the CHB-MIT Scalp EEG Database
- **Visualization**: Creates topographical maps and time-series plots of brain activity
- **Analysis**: Compares ictal and interictal states, with frequency analysis using scipy
- **MNE Integration**: Uses MNE Python for advanced EEG analysis and visualization

## Requirements
The analysis requires several Python packages, which are listed in the `requirements.txt` file. You can install all dependencies with:
```
pip install -r requirements.txt
```

## Data Structure
The repository contains:
- Patient summary files (chbXX-summary.txt)
- Jupyter notebook for analysis (Cerebellar_Analysis.ipynb)

## Usage
1. Open the Jupyter notebook in your preferred environment (local or Google Colab)
2. Run the cells sequentially to set up the environment and analyze the data
3. The notebook will download necessary files from PhysioNet when executed

## Citation
If you use this data or analysis in your research, please cite:
- Romell Dominguez, PERU_CBI: Peruvian Sensor Brain Database (2025)
- Original CHB-MIT Scalp EEG Database from PhysioNet

## License
This project is available for academic and research use.

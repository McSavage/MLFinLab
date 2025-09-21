# MLFinLab Project - FIN221

This project uses the Hudson and Thames MLFinLab library for Machine Learning in Finance coursework.

## Project Structure

```
MLFinLab/
├── data/           # Raw and processed datasets
├── notebooks/      # Jupyter notebooks for analysis
├── scripts/        # Python scripts and utilities
├── docs/          # Documentation and reports
├── requirements.txt
└── README.md
```

## Setup Instructions

### 1. Activate Conda Environment

Your MlFinLab environment is already set up! To activate it:

**Option A: If conda is initialized in PowerShell:**

```powershell
conda activate MlFinLab
```

**Option B: Direct activation:**

```powershell
& "C:\Users\danmc\Anaconda3\condabin\conda.bat" activate MlFinLab
```

### 2. Verify Installation

```powershell
# Check Python version (should be 3.11.13)
python --version

# Check MLFinLab installation
python -c "import mlfinlab; print(f'MLFinLab version: {mlfinlab.__version__}')"
```

### 3. Launch Jupyter Notebook

```powershell
jupyter notebook
```

## MLFinLab Overview

MLFinLab is a comprehensive library that implements cutting-edge financial machine learning research, including:

- **Data Structures**: Dollar/Volume/Tick bars, Information-driven bars
- **Feature Engineering**: Fractional differentiation, Structural breaks
- **Labeling**: Triple barrier method, Meta-labeling, Trend scanning
- **Portfolio Optimization**: Mean reversion, Hierarchical risk parity
- **Microstructure**: VPIN, Order flow imbalance

## Getting Started

1. Check out the example notebook in `notebooks/01_getting_started.ipynb`
2. Place your data files in the `data/` folder
3. Use the `scripts/` folder for reusable Python modules

## Resources

- [MLFinLab Documentation](https://mlfinlab.readthedocs.io/)
- [Hudson & Thames Research](https://hudsonthames.org/)
- Course materials and assignments in `docs/`

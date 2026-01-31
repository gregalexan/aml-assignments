# AML Assignments Repository

This repository contains three machine learning assignments exploring different approaches to data analysis, predictive modeling, and decision-making analysis.

## Project Overview

This collection includes applied machine learning projects covering sustainable development metrics, statistical analysis of demographic data, and predictive modeling on human decision-making patterns.

---

## Assignments

### 📊 Assignment 1: Doughnut Analysis
**Directory**: `aml-assignment-1/`

Analysis of sustainable development and planetary health metrics using the Doughnut Economics framework. This assignment explores global sustainability indicators including climate change, ocean acidification, biodiversity, and socioeconomic factors across multiple countries.

**Key Topics**:
- Data exploration and cleaning of sustainability indicators
- Analysis of ecological boundaries (climate, pollution, biodiversity)
- Analysis of social foundations (health, education, equality, justice)
- Visualization of multi-dimensional sustainability metrics
- Correlation analysis between environmental and social indicators

**Data**:
- 24 ecological and social indicator datasets
- Population and GNI data for 193 countries
- Time series data from 2000-2022

**Technologies**: Pandas, NumPy, Matplotlib, Seaborn, Plotly, Altair, Scikit-learn

**Files**:
- `doughnut.ipynb` - Main analysis notebook
- `assignment/doughnut_assignment.ipynb` - Assignment submission
- `data/` - All indicator CSV files
- `outputs/` - Analysis results and visualizations

---

### 📈 Assignment 2: Age & Gender Distortion Analysis
**Directory**: `aml-assignment-2/`

Statistical analysis of age and gender demographic patterns with interactive regression modeling and visualization. This assignment investigates relationships between age, gender, and other demographic variables.

**Key Topics**:
- Statistical analysis of demographic distributions
- Age and gender distortion metrics
- Linear and non-linear regression modeling
- Interactive visualization of demographic patterns
- Statistical hypothesis testing (using Pingouin and Statsmodels)

**Technologies**: Pandas, NumPy, Matplotlib, Seaborn, Plotly, Altair, Scikit-learn, Scipy, Statsmodels, Pingouin

**Files**:
- `assignment.ipynb` - Main assignment notebook
- `assignment/age_gender_distortion_assignment_new.ipynb` - Updated assignment
- `assignment/age_gender_regression_interactive.html` - Interactive regression visualization
- `outputs/` - Generated plots and results

---

### 🎲 Assignment 3: Choices13k Dataset Analysis
**Directory**: `aml-assignment-3/`

Machine learning analysis of the Choices13k dataset containing 13,006 human decision-making instances under uncertainty. This assignment applies modern ML techniques to predict and understand human risky choice behavior.

**Dataset**:
- 13,006 risky choice problems from human participants
- Each problem presents two gambling scenarios with different risk profiles
- Problems parameterized with outcomes, probabilities, and lottery structures
- 30x larger than previous behavioral decision datasets
- Collected following best practices in human decision-making research

**Key Topics**:
- Predictive modeling of human choice behavior
- Classification and regression on behavioral data
- Feature engineering from choice parameters
- Model comparison (Scikit-learn, XGBoost, TensorFlow)
- Analysis of decision-making patterns

**Technologies**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost, TensorFlow, Keras

**Files**:
- `assignment.ipynb` - Main analysis notebook
- `choices13k_assignment.ipynb` - Assignment submission
- `Choices13k Example.ipynb` - Example analysis
- `c13k_problems.json` - Choice problems dataset
- `c13k_selections.csv` - Human choice selections
- `LICENSE` - Dataset license information
- `README.md` - Dataset documentation

---

## Setup & Installation

Each assignment has its own Python environment defined in `pyproject.toml`. 

### Requirements
- Python >= 3.13
- Jupyter

### Installing Dependencies

Navigate to an assignment directory and install its dependencies:

```bash
cd aml-assignment-1
uv sync
```

Or install in development mode:

```bash
uv pip install -e .
```

---

## Repository Structure

```
aml-assignments/
├── README.md                          # This file
├── LICENSE                            # Repository license
├── aml-assignment-1/                  # Sustainable development analysis
│   ├── doughnut.ipynb
│   ├── pyproject.toml
│   ├── assignment/
│   ├── data/                          # 24 indicator datasets + population data
│   ├── images/
│   └── outputs/
├── aml-assignment-2/                  # Demographics & regression analysis
│   ├── assignment.ipynb
│   ├── pyproject.toml
│   ├── README.md
│   ├── assignment/
│   └── outputs/
└── aml-assignment-3/                  # Risky choice prediction
    ├── assignment.ipynb
    ├── pyproject.toml
    ├── README.md
    ├── Assignment-README.md
    ├── c13k_problems.json
    ├── c13k_selections.csv
    └── assignment/
```

---

## Running the Assignments

1. **Launch Jupyter**:
   ```bash
   jupyter notebook
   ```

2. **Navigate to an assignment directory** and open the `.ipynb` notebook file

3. **Install dependencies** within the notebook if needed:
   ```python
   !uv sync
   ```

---

## Technologies & Tools

Common technologies across assignments:
- **Data Processing**: Pandas, NumPy, Scipy
- **Visualization**: Matplotlib, Seaborn, Plotly, Altair
- **Machine Learning**: Scikit-learn, XGBoost, TensorFlow
- **Statistical Analysis**: Scipy, Statsmodels, Pingouin
- **Jupyter**: Interactive notebook environment

---

## License

See [LICENSE](LICENSE) file for details.

---

## Author Notes

These assignments demonstrate practical applications of machine learning and statistical analysis to diverse real-world datasets, from global sustainability metrics to human behavioral economics.
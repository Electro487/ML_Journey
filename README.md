# ML Journey 🚀

A structured collection of machine learning experiments and implementations, progressing from foundational concepts to more advanced techniques.

## Project Overview

This repository documents a machine learning learning journey, covering fundamental algorithms and their practical applications. Each directory represents a distinct project or topic with hands-on implementations using Jupyter notebooks.

## Repository Structure

```
ML_Journey/
├── 01_linear_regression/
│   └── basic_experiment.ipynb          # Introduction to linear regression with visualization
├── 02_knn/
│   ├── knn_algo.ipynb                  # K-Nearest Neighbors algorithm implementation
│   └── winequality-white.csv          # Wine quality dataset
├── 03_scaling_knn/
│   ├── library_knn.ipynb               # KNN using scikit-learn with scaling techniques
│   └── winequality-white.csv          # Wine quality dataset
├── 04_linear_regression/
│   ├── linear_regression.ipynb         # Advanced linear regression analysis
│   └── Houseprice.csv                 # Housing price dataset
├── requirements.txt                    # Python dependencies
└── venv/                              # Virtual environment
```

## Projects

### 1. **Linear Regression Basics** (`01_linear_regression/`)
- **File**: `basic_experiment.ipynb`
- **Topics**: 
  - Linear regression fundamentals
  - Model training and prediction
  - Visualization of results
- **Dataset**: Synthetic or built-in data

### 2. **K-Nearest Neighbors (KNN)** (`02_knn/`)
- **File**: `knn_algo.ipynb`
- **Topics**:
  - KNN algorithm implementation from scratch
  - Distance metrics and neighbor selection
  - Classification on real-world data
- **Dataset**: Wine Quality dataset (white wine)

### 3. **KNN with Scaling & Optimization** (`03_scaling_knn/`)
- **File**: `library_knn.ipynb`
- **Topics**:
  - Feature scaling (StandardScaler)
  - Scikit-learn implementation
  - GridSearchCV for hyperparameter tuning
  - Model evaluation and metrics
- **Dataset**: Wine Quality dataset (white wine)

### 4. **Advanced Linear Regression** (`04_linear_regression/`)
- **File**: `linear_regression.ipynb`
- **Topics**:
  - Comprehensive regression analysis
  - Data preprocessing and exploration
  - Model training and evaluation
  - Advanced regression techniques
- **Dataset**: Housing price data

## Technologies & Libraries

- **Python 3.x**
- **NumPy**: Numerical computing
- **Pandas**: Data manipulation and analysis
- **Scikit-learn**: Machine learning algorithms
- **Matplotlib/Seaborn**: Data visualization
- **Jupyter**: Interactive notebooks
- **Jupyter Lab**: Enhanced notebook environment

For complete dependencies, see [requirements.txt](requirements.txt)

## Getting Started

### Prerequisites
- Python 3.7+
- pip or conda

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd ML_Journey
   ```

2. **Create and activate virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Launch Jupyter Lab**
   ```bash
   jupyter lab
   ```

5. **Open and run notebooks**
   - Navigate to desired project folder
   - Open the `.ipynb` file in Jupyter Lab
   - Execute cells sequentially to follow along

## Key Concepts Covered

| Topic | Project | Key Points |
|-------|---------|-----------|
| Linear Regression | 01, 04 | Fitting lines, predictions, visualization |
| KNN Classification | 02, 03 | Distance metrics, neighbor voting |
| Feature Scaling | 03 | StandardScaler, normalization |
| Hyperparameter Tuning | 03 | GridSearchCV, cross-validation |
| Model Evaluation | 03, 04 | Accuracy, metrics, train/test split |

## Learning Path

Follow this recommended order for best understanding:

1. Start with **01_linear_regression** - understand basic ML concepts
2. Move to **02_knn** - explore a different algorithm and implement it
3. Progress to **03_scaling_knn** - learn practical techniques and optimization
4. Finish with **04_linear_regression** - apply advanced regression analysis

## Usage Tips

- Run cells in order within each notebook
- Modify parameters and re-run cells to experiment
- Check outputs and visualizations to understand model behavior
- Use comments in notebooks for detailed explanations

## Datasets

- **Wine Quality Dataset**: Used in KNN projects to classify wine quality
- **Housing Price Dataset**: Used in linear regression for price prediction

Both datasets are included in their respective directories.

## Notes

- These are educational implementations meant to illustrate ML concepts
- For production use, consider additional validation and optimization
- Experiment with different parameters to deepen understanding

## Future Improvements

- [ ] Add more advanced algorithms (SVM, Random Forest, etc.)
- [ ] Include cross-validation examples
- [ ] Add more diverse datasets
- [ ] Create utility functions module
- [ ] Add data visualization best practices guide

---

**Last Updated**: December 2025

Happy Learning! 📊📈

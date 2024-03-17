# Forest Cover Type Classification Project

## 1. Project Aim and Goal
The Forest Cover Type Classification Project is dedicated to predicting the type of forest cover from cartographic variables. The goal is to accurately classify the forest cover type into one of seven classes based on environmental and geographical features using Support Vector Machine.
## 2. Dataset Explanation
The dataset for this project comprises cartographic variables derived from the US Geological Survey (USGS) and the US Forest Service (USFS) data.
- `54` Features
- `7` Classes 

**To Import Data**
```python
from sklearn.datasets import fetch_covtype
covertype = fetch_covtype()
```

Key features include:

- **Elevation**: The elevation of the forest in meters.
- **Aspect**: The compass direction that the slope of the forest faces.
- **Slope**: The steepness of the slope of the forest.
- **Horizontal Distance to Hydrology**: The horizontal distance to the nearest surface water features.
- **Vertical Distance to Hydrology**: The vertical distance to the nearest surface water features.
- **Horizontal Distance to Roadways**: The horizontal distance to the nearest roadway.
- **Hillshade Indexes**: Measures of shade, at morning, noon, and afternoon.
- **Horizontal Distance to Fire Points**: The horizontal distance to the nearest wildfire ignition points.
- **Wilderness Area**: Categorical variable indicating the wilderness area designation.
- **Soil Type**: Categorical variable indicating the type of soil.

The target variable is the `Cover_Type`, which represents seven different forest cover types.

## 3. Packages and Libraries Required
To execute the project, the following Python packages and libraries need to be installed:
- `numpy`: For numerical computations.
- `pandas`: For data manipulation and analysis.
- `matplotlib`: For creating static, interactive, and animated visualizations.
- `seaborn`: For high-level interface for drawing attractive and informative statistical graphics.
- `scikit-learn`: For machine learning and predictive data analysis.
- `catboost`: For gradient boosting on decision trees.

## 4. File Formatting and Structure

```
| partOne.ipynb (Notebook for partone)
| y_pred_test.csv (pulsar data)
| a PDF report (for the "Go wild !" part)
project
│   main.ipynb
│   README.md
└───Data
    │   balanced_train.csv
    │   cover_type_scaled_reduced.csv
```



## Getting Started
To run the project:
1. Ensure Python 3.x is installed.
2. Install the required libraries using pip:
   ```shell
   pip install numpy pandas matplotlib seaborn scikit-learn catboost

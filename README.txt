# Machine Learning Model for Glass Type Prediction

This project focuses on building a machine learning model that predicts the type of glass based on its chemical composition using Python. The model aims to classify glass into various types like building windows, vehicle windows, containers, etc.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Model Building](#model-building)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Overview
Glass is a material that can be classified into various types based on its chemical composition, and this classification is crucial for industrial purposes. The aim of this project is to develop a machine learning model that can accurately predict the type of glass based on a set of input features.

The project covers the following steps:
1. Data loading and preprocessing.
2. Feature selection and scaling.
3. Model building and training.
4. Model evaluation using accuracy, precision, recall, etc.
5. Final predictions.

## Dataset
The dataset used in this project is the [Glass Identification Dataset](https://archive.ics.uci.edu/ml/datasets/glass+identification) from the UCI Machine Learning Repository. It contains the following features:
- Refractive Index
- Sodium (Na)
- Magnesium (Mg)
- Aluminum (Al)
- Silicon (Si)
- Potassium (K)
- Calcium (Ca)
- Barium (Ba)
- Iron (Fe)

The target variable is the glass type, which can be one of the following:
- 1: Building windows float processed
- 2: Building windows non-float processed
- 3: Vehicle windows float processed
- 4: Vehicle windows non-float processed
- 5: Containers
- 6: Tableware
- 7: Headlamps

## Technologies Used
- **Python**: Programming language for data analysis and model building.
- **Scikit-learn**: Library for building machine learning models.
- **Pandas & NumPy**: For data manipulation and analysis.
- **Matplotlib & Seaborn**: For data visualization.
- **Jupyter Notebook**: For running and presenting the project.

## Installation

### Prerequisites
Ensure you have the following installed:
- Python 3.x
- pip

### Steps to Setup the Project
1. Clone this repository:
   ```bash
   git clone https://github.com/sanjay-2k04/Glass-Prediction-using-Machine-Learning.git

# SVM Breast Cancer Classification

This project uses Support Vector Machine (SVM) to classify breast cancer data. The dataset used in this project is the Breast Cancer Wisconsin dataset, which is available in the `sklearn.datasets` library.

## Prerequisites

Before you begin, ensure you have met the following requirements:
- Python 3.x is installed on your system
- Required Python libraries are installed:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `sklearn`

You can install the required libraries using the following command:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Project Structure
SVM.ipynb: The Jupyter Notebook containing the code for data loading, preprocessing, training the SVM model, and evaluating its performance.
README.md: This file provides an overview of the project, setup instructions, and usage details.

### Installation
Clone this repository:
```bash
git clone https://github.com/ArezooAraste/svm-breast-cancer-classification.git
```

Navigate to the project directory:
```bash
cd svm-breast-cancer-classification
```

Install the required libraries:
```bash
pip install -r requirements.txt
```

## Usage
Open the Jupyter Notebook:
```bash
jupyter notebook SVM.ipynb
```

Run the cells step by step to:
Load the breast cancer dataset
Preprocess the data
Train the SVM model
Evaluate its accuracy

## Dataset
The dataset used in this project is the Breast Cancer Wisconsin dataset. It contains features related to cell nuclei present in breast tissue, which are used to classify tumors as benign or malignant.

## Model
The SVM (Support Vector Machine) algorithm is used for classification. It aims to find a hyperplane that best separates the data points of different classes in a high-dimensional space.

## Results
The notebook contains steps for evaluating the model's performance using accuracy metrics, confusion matrix, and visualization tools like Seaborn for better understanding.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.




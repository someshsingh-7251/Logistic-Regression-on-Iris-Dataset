
# Logistic Regression on Iris Dataset

This repository contains a machine learning project that uses **Logistic Regression** to classify the species of the Iris flower based on the well-known **Iris dataset**. The Iris dataset is widely used for demonstrating classification algorithms in machine learning.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Dependencies](#dependencies)
- [Installation](#installation)
- [Usage](#usage)
- [Model Evaluation](#model-evaluation)
- [Contributing](#contributing)
- [License](#license)

## Project Overview
Logistic Regression is a supervised learning algorithm that is commonly used for binary and multi-class classification tasks. In this project, logistic regression is applied to the **Iris dataset**, which consists of three classes representing three species of Iris flowers: **Setosa**, **Versicolor**, and **Virginica**. 

This project walks through the following steps:
1. Data loading and visualization.
2. Preprocessing the dataset.
3. Building and training a logistic regression model.
4. Evaluating the model performance on the test data.

## Dataset
The **Iris dataset** contains 150 samples of iris flowers, with the following features:
- **sepal length** (cm)
- **sepal width** (cm)
- **petal length** (cm)
- **petal width** (cm)
- **species**: Iris-Setosa, Iris-Versicolor, Iris-Virginica (Target labels)

**Source**: The Iris dataset is a standard dataset that is included in the `scikit-learn` library. For more information, see [Iris Dataset on UCI](https://archive.ics.uci.edu/ml/datasets/iris).

## Dependencies
The project is implemented in Python and requires the following libraries:
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`

## Installation
1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/someshsingh-7251/Logistic-Regression-on-Iris-Dataset.git
    cd Logistic-Regression-on-Iris-Dataset
    ```

2. (Optional) Set up a virtual environment:
    ```bash
    python -m venv env
    source env/bin/activate  # On Windows use: env\Scripts\activate
    ```

3. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```

4. Launch Jupyter Notebook (if needed):
    ```bash
    jupyter notebook
    ```

## Usage
Once the environment is set up, open the Jupyter notebook `Logistic_Regression_Iris.ipynb` to explore the implementation of the logistic regression model on the Iris dataset.

The notebook walks you through:
1. **Loading the Iris dataset** from `scikit-learn`.
2. **Data exploration**: Understanding the distribution of the data with visualization techniques like pair plots and histograms.
3. **Data preprocessing**: Normalization and splitting the dataset into training and testing sets.
4. **Model training**: Applying logistic regression using `scikit-learn` and training the model on the training set.
5. **Model evaluation**: Predicting on the test set and evaluating the model performance using metrics such as accuracy, confusion matrix, and classification report.

To run the project locally:
1. Make sure all dependencies are installed.
2. Run the notebook using the following command:
   ```bash
   jupyter notebook Logistic_Regression_Iris.ipynb
   ```

## Model Evaluation
The logistic regression model is evaluated using several key metrics:
- **Accuracy**: The proportion of correctly classified samples.
- **Confusion Matrix**: A matrix that shows the actual versus predicted classifications for each class.
- **Classification Report**: A detailed performance report that includes precision, recall, and F1-score for each class.

## Contributing
Contributions to the project are welcome! To contribute:
1. Fork the repository.
2. Create a new branch for your feature or bug fix (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -m 'Add feature'`).
4. Push your branch (`git push origin feature-branch`).
5. Open a Pull Request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

*Note: Feel Free to Contact at Instagram: https://www.instagram.com/officialsomeshchinkusingh?igsh=MW1vdTZwbDdmMTZxbw==*

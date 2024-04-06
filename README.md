**README**
# DataMiningProject

# Credit Card Fraud Detection Project

This repository contains a data mining project focused on credit card fraud detection. The project explores various methods, including Support Vector Classification (SVC), Logistic Regression (LT), and Neural Networks, to detect fraudulent transactions.

## Project Structure

The project directory is structured as follows:

- **evaluation_of_models/**: CSV Output which reflect the models statistic factors abd confusion tables.
- **main/**: Includes the Python scripts for data preprocessing, model training, and evaluation.
###TOC:
###rows        Description
###10-34       plot histograms of all variables
###37-51       plotting pie to show the proportion of 1 and 0 in y
###55-79       plotting MI graph
###88-200      Helpful Methods
###214-250     Decision Tree
###261-294     RandomForestClassifier
###303-352     SVC - Support Vector Classifier
###361-412     Improved Support Vector Classifier
###423-495     Nueral System + plot loss value and accuracy of test and train
###520+        Main

- **AVG-STDEV/**: Output that Review the mean and std of the Accuracy of the models.
- **calc_stat/**: Output that Review the statistics tests factor.
- **creditcard/**: InPut Contains the dataset used for training and testing the models.
- **results/**: Stores the results generated during model evaluation.
- **README.md**: This file, providing an overview of the project and instructions.

## Requirements

To execute the code in this project, ensure you have the following dependencies installed:

- Python 3.11
- NumPy
- pandas
- scikit-learn
- TensorFlow
- Keras
- imbalanced-learn
- SciPy
- matplotlib
You can install the required Python packages using pip:
pip install numpy pandas scikit-learn tensorflow keras imbalanced-learn scipy matplotlib

```
git clone https://github.com/your-username/credit-card-fraud-detection.git
```

## Contributing

Contributions to this project are welcome. If you have suggestions for improvement, please fork the repository, make your changes, and submit a pull request.

## Authors

- [Nir Maayan](https://github.com/nirma100)

## Acknowledgments

- Special thanks to Kaggle for providing the dataset used in this project.
- Inspiration for this project came from the article of S. Tharun Sainatha Reddy, P. Sriramya, which provided insights into credit card fraud detection methods.

Feel free to update this README file with additional information specific to your project as needed.

**README**
# Credit Card Fraud Detection Project: Exploring Machine Learning Methods

This repository contains a data mining project focused on credit card fraud detection. The project explores various methods, including Support Vector Classification (SVC), Logistic Regression (LT), and Neural Networks, to detect fraudulent transactions.

# References:
- **Link to DB :** https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
- **Link to the article :** https://sifisheriessciences.com/journal/index.php/journal/article/view/463/446

## Project Structure
The project directory is structured as follows:

- **evaluation_of_models/**: CSV Output which reflect the models statistic factors abd confusion tables.
- **main/**: Includes the Python scripts for data preprocessing, model training, and evaluation.

### Table of Contents of the python file:

| Rows     | Description                                                               |
|----------|---------------------------------------------------------------------------|
| 10-34    | [Histograms of All Variables](#histograms-of-all-variables)               |
| 37-51    | [Pie Chart of Class Proportions](#pie-chart-of-class-proportions)         |
| 55-79    | [Mutual Information Graph](#mutual-information-graph)                     |
| 88-200   | [Helpful Methods](#helpful-methods)                                       |
| 214-250  | [Decision Tree](#decision-tree)                                           |
| 261-294  | [RandomForestClassifier](#randomforestclassifier)                         |
| 303-352  | [SVC - Support Vector Classifier](#svc---support-vector-classifier)       |
| 361-412  | [Improved Support Vector Classifier](#improved-support-vector-classifier) |
| 423-495  | [Neural System](#neural-system)                                           |
| 520+     | [Main](#main)                                                             |

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

## Usage

1. **Read the Article**: Please refer to the article [here](https://sifisheriessciences.com/journal/index.php/journal/article/view/463/446) for detailed insights and context regarding the credit card fraud detection problem.

2. **Download Dataset**: Download the credit card CSV file from Kaggle using the following [link](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud).

3. **Download Python file**: 
    ```
 [python file](https://github.com/nirma100/Credit-Card-Fraud-Detection-Project-Exploring-Machine-Learning-Methods/blob/main/main.py)
    ```

4. **Update File Paths**: If necessary, update file paths in the code to match your local file structure. Look for lines referencing file paths (e.g., Line 15,41,63,216,521) and adjust them accordingly.

6. **Run the Scripts**: Execute the Python scripts in the `main/` directory to preprocess data, train models, and evaluate their performance. 

7. **Review Results**: Once the scripts have completed execution, check the `evaluation_of_models/` directory for the generated output, including performance metrics, visualizations, or any other relevant results.


## Contributing

Contributions to this project are welcome. If you have suggestions for improvement, please fork the repository, make your changes, and submit a pull request.

## Authors

- [Nir Maayan](https://github.com/nirma100)

## Acknowledgments

- Special thanks to Kaggle for providing the dataset used in this project.
- Inspiration for this project came from the article of S. Tharun Sainatha Reddy, P. Sriramya, which provided insights into credit card fraud detection methods.
- Special thanks to **Dima Alberg** for his guidance, encouragement, and dedication to teaching important subjects and pushing us to learn and improve.

Feel free to update this README file with additional information specific to your project as needed.

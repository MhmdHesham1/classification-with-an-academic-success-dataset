# Academic Success Prediction Model

## Overview
This project uses machine learning techniques to predict academic success based on various student attributes. It utilizes several classification algorithms, including Random Forest, Decision Tree, K-Nearest Neighbors, and CatBoost, to analyze and predict student outcomes.

## Dataset
The dataset used in this project contains various features related to students' academic and personal backgrounds. It includes information such as:
- Marital status
- Application mode
- Previous qualifications
- Parents' qualifications
- Curricular unit performance
- Economic indicators (Unemployment rate, Inflation rate, GDP)

The target variable is the student's academic outcome, categorized as 'Graduate', 'Dropout', or 'Enrolled'.

## Requirements
To run this project, you need the following Python libraries:
- numpy
- pandas
- scikit-learn
- catboost

You can install these dependencies using pip:
pip install numpy pandas scikit-learn catboost

## File Structure
- `classification-with-an-academic-success-dataset.ipynb`: Jupyter notebook containing the main code
- `train.csv`: Training dataset
- `test.csv`: Test dataset
- `submission.csv`: Output file with predictions for the test set

## Usage
1. Ensure all required libraries are installed.
2. Open and run the Jupyter notebook `classification-with-an-academic-success-dataset.ipynb`.
3. The notebook will load the data, preprocess it, train multiple models, and generate predictions.
4. The final predictions will be saved in `submission.csv`.

## Model Performance
The project compares the performance of several classification models:
- Random Forest
- Decision Tree
- K-Nearest Neighbors
- CatBoost

Metrics used for evaluation include accuracy, precision, recall, and F1-score.

## Results
The CatBoost model showed the best performance among the tested algorithms, with the following metrics:
- Accuracy: 0.8181
- Precision: 0.7875
- Recall: 0.7683
- F1-Score: 0.7760

## Future Improvements
- Feature engineering to create more informative variables
- Hyperparameter tuning for each model
- Ensemble methods to combine predictions from multiple models
- Deep learning approaches for potentially improved accuracy

## Contributors
Mohamed Hesham
## License
[Specify the license under which this project is released, e.g., MIT, GPL, etc.]

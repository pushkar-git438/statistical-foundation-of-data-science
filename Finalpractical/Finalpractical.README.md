# Crop Recommendation Using Decision Tree

## Overview
This project uses a Decision Tree Classification algorithm to recommend crops based on environmental and soil conditions. The model predicts one of three crops: Apple, Rice, or Wheat.

## Dataset
A synthetic dataset of 900 samples is generated using NumPy.

### Features
- **ph** – Soil pH
- **rain** – Annual rainfall (mm)
- **temp** – Growing-season temperature (°C)
- **nitro** – Nitrogen level (kg/ha)
- **crop** – Target crop (Apple, Rice, or Wheat)

## Libraries Used
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

## Algorithm
Decision Tree Classifier

- Train-test split: 80% training, 20% testing
- Random state: 21
- Maximum tree depth: 3

## Implementation Steps
1. Import the required libraries.
2. Generate the synthetic dataset.
3. Explore and summarize the dataset.
4. Split the data into training and testing sets.
5. Train the Decision Tree classifier.
6. Evaluate the model using accuracy and confusion matrix.
7. Display the decision tree rules.
8. Visualize the decision tree.
9. Calculate and plot feature importance.

## How to Run
1. Open Google Colab.
2. Create a new notebook.
3. Copy the project code into separate cells.
4. Run all cells sequentially.

## Model Evaluation
The model is evaluated using:
- Test Accuracy
- Confusion Matrix
- Decision Tree Rules
- Feature Importance

## Output
The notebook produces:
- Dataset preview and statistical summary
- Crop distribution
- Test accuracy
- Confusion matrix
- Decision tree rules
- Decision tree visualization
- Feature importance table and graph

## Result
The Decision Tree model classifies crops based on the generated environmental dataset and provides interpretable decision rules for crop recommendation.

---
**Language:** Python  
**Algorithm:** Decision Tree Classification

Overview

This project implements a credit card fraud detection system using machine learning techniques. The system utilizes the AdaBoost algorithm and Majority Voting mechanism to classify transactions as normal or fraudulent. The implementation is done using Python and Tkinter for GUI-based interaction.

Features

1.Load and preprocess credit card transaction dataset

2.Split dataset into training and testing sets

3.Train a machine learning model using the Random Forest algorithm

4.Predict fraudulent transactions using trained models

5.Display fraud detection results with a graphical interface

6.Visualize normal and fraudulent transactions using bar graphs

Requirements

1The following Python libraries are required to run the project:

1.tkinter

2.matplotlib

3.numpy

4.pandas

5.scikit-learn

You can install the required libraries using:

1.pip install numpy pandas matplotlib scikit-learn

2.Installation & Execution

3.Clone the repository or download the project files.

4.Ensure all dependencies are installed.

5.Run the main.py file using:

python main.py

The GUI will launch, allowing users to interact with the application.

Usage

1.Upload Dataset: Load the credit card transaction dataset (CSV format) into the application.

2.Generate Train & Test Model: The dataset is split into training and testing sets.

3.Run Algorithm: Executes the fraud detection model using AdaBoost and Majority Voting.

4.Detect Fraud: Predicts fraudulent transactions from test data.

5.Graphical Analysis: Displays a bar graph showing normal vs. fraudulent transactions.

6.Exit: Closes the application.

Dataset

The dataset should be in CSV format and contain transaction details with class labels (0 for normal and 1 for fraudulent transactions). Ensure the dataset contains appropriate feature columns for model training.

Output

1.Classification of transactions as fraud or normal.

2.Accuracy report of the model.

3.Visual representation of transaction types.

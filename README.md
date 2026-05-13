# stress-level-prediction-neural-network
Neural network project focused on predicting stress levels from daily lifestyle habits using Python, TensorFlow, and data analysis techniques.


# Predicting Stress Levels from Lifestyle Habits Using Neural Networks

This project uses a feed-forward neural network to predict low, moderate, and high stress levels from lifestyle habit data such as sleep, exercise, pending tasks, interruptions, fatigue, social hours, and coffee intake.

## Project Goal
The goal was to test whether neural networks can learn patterns between daily lifestyle habits and stress levels.

## Dataset
The dataset contains 2,000 synthetic records from the General Mental Health and Lifestyle Dataset on Kaggle.

## Methods
- Exploratory data analysis
- Feature preprocessing and normalization
- Rule-based baseline predictors
- Feed-forward neural network model comparison
- Feature importance experiments
- ROC and AUC evaluation

## Best Results
- Best neural network: 1 hidden layer with 8 neurons
- Validation accuracy: 92.25%
- AUC score: 0.983
- Strongest feature: daily pending tasks

## Key Takeaway
A simple neural network performed better than manually designed rule-based predictors, showing that it could learn more complex relationships between workload, lifestyle habits, and stress.

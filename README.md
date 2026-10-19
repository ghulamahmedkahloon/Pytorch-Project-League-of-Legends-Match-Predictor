# League of Legends Match Outcome Predictor

A machine learning classification project built with PyTorch to predict the outcome of League of Legends matches from match-related features.

**Course:** PyTorch Basics for Machine Learning  
**Provider:** IBM  
**Project type:** Final course project  
**Language:** Python  
**Main library:** PyTorch

## Overview

This project explores how a machine learning model can use match data to predict whether a League of Legends team will win or lose.

The project was completed as the final project for IBM's *PyTorch Basics for Machine Learning* course. It applies fundamental machine learning concepts, including data preparation, model training, loss calculation, optimization, and evaluation, to a binary classification task.

The purpose was to strengthen my understanding of implementing and training a machine learning model with PyTorch.

## Objectives

- Prepare match data for a binary classification task.
- Build a logistic regression model using PyTorch.
- Understand how model predictions and loss are calculated.
- Train the model using an optimization algorithm.
- Evaluate model performance on training and test data.
- Explore how training choices affect model performance.

## Methodology

The project follows a typical supervised machine learning workflow:

1. **Data preparation:** Prepare the match features and target labels for model training.
2. **Model implementation:** Use a logistic regression model to estimate the probability of a match outcome.
3. **Loss calculation:** Use binary cross-entropy loss to measure the difference between predictions and actual labels.
4. **Training:** Update model parameters through gradient-based optimization.
5. **Evaluation:** Assess predictions on training and test data to examine how well the model generalizes.
6. **Experiments:** Explore training configurations and model behavior as part of the learning process.

## Technologies Used

- **Python** — programming language
- **PyTorch** — model implementation, automatic differentiation, and training
- **NumPy and pandas** — numerical and data manipulation
- **Matplotlib** — visualization, where used
- **Jupyter Notebook** — interactive development and experimentation

## Results and Limitations

This is an educational project rather than a production-ready match prediction system.

The model's predictive performance was limited and close to chance-level classification on the test data. This highlights an important lesson: implementing and training a model does not necessarily mean it will make reliable predictions.

Potential improvements include more informative features, more systematic hyperparameter tuning, stronger baseline comparisons, and further analysis of class balance and generalization.

## What I Learned

Through this project, I practiced:

- Implementing a machine learning model with PyTorch.
- Understanding the relationship between predictions, loss functions, and parameter updates.
- Applying gradient-based optimization to a classification problem.
- Evaluating a model on data separate from its training data.
- Interpreting model performance critically rather than assuming that training guarantees good results.

## How to Run

1. Clone or download this repository.
2. Open the Jupyter Notebook containing the final project.
3. Install the Python dependencies required by the notebook.
4. Follow the notebook cells in order.

Example environment setup:

```bash
python -m venv .venv
```

Activate the environment, then install the required packages:

```bash
pip install torch numpy pandas matplotlib scikit-learn jupyter
```

Start Jupyter Notebook:

```bash
jupyter notebook
```

**Note:** The notebook may depend on course-provided data files or supporting resources. Make sure any required files are available in the expected locations before running it from beginning to end.

## Acknowledgment

This project was completed as the final project of IBM's **PyTorch Basics for Machine Learning** course. It represents my practical work applying the concepts taught in the course.

## Author

**Ghulam Ahmad Kahloon**

- Portfolio: [ghulamahmadkahloon.com](https://ghulamahmadkahloon.com/)
- GitHub: [ghulamahmedkahloon](https://github.com/ghulamahmedkahloon)

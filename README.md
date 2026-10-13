# BugTriage AI — Problem Statement

Software development teams receive many bug reports, and manually reviewing and prioritizing them can take time. Delays in identifying critical bugs may affect software quality and the team's productivity.

BugTriage AI aims to automate bug severity classification using machine learning. The system will analyse the text of a bug report and predict its severity as Low, Medium, or High.

The project will use a labelled bug-report dataset to train and evaluate a machine learning model, with the goal of helping software teams prioritize bug reports more efficiently.

## Project Objectives

- Automate the initial classification of software bug reports.
- Predict bug severity as Low, Medium, or High using machine learning.
- Help software teams prioritize bug reports more efficiently.
- Evaluate model performance using appropriate classification metrics.

## Proposed Technology Stack

- **Programming:** Python
- **Data processing:** Pandas, NumPy
- **Machine learning:** Scikit-learn
- **Experiment tracking:** MLflow (planned for a later sprint)
- **Development environment:** Google Colab
- **Version control:** Git and GitHub
- **Project management:** Jira
- **Deployment:** Hugging Face Spaces (planned)

## Planned Workflow

1. Identify a suitable, labelled software bug-report dataset.
2. Inspect, clean, and prepare the data.
3. Map the available severity labels to Low, Medium, and High where appropriate.
4. Train a baseline Logistic Regression classifier.
5. Evaluate the model using precision, recall, F1-score, and a confusion matrix.
6. Track experiments with MLflow in a later sprint.
7. Develop and deploy a simple interface for submitting bug reports and viewing predicted severity.

**Project status:** Planning and initial setup. Dataset selection, model development, and deployment are pending.

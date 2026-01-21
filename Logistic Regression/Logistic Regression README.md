{
 "cells": [
  {
   "cell_type": "markdown",
   "id": "2cd25084-1408-4177-882f-67f1fd891e16",
   "metadata": {},
   "source": [
    "# Logistic Regression for Binary Classification (Synthetic Dataset)\n",
    "\n",
    "This project demonstrates how to build a **Logistic Regression** model for **binary classification** using a **synthetic 2D dataset** created with `sklearn.datasets.make_classification`.  \n",
    "It includes dataset creation, train-test split, model training, evaluation metrics, and visualizations (confusion matrix + decision boundary).\n",
    "\n",
    "---\n",
    "\n",
    "## Project Overview\n",
    "\n",
    "Logistic Regression is a supervised learning algorithm used for **classification** problems.  \n",
    "In this project, we:\n",
    "1. Generate a synthetic dataset with **2 features** (so we can plot it easily).\n",
    "2. Split the dataset into training and testing sets.\n",
    "3. Train a Logistic Regression model using scikit-learn.\n",
    "4. Evaluate the model using standard classification metrics.\n",
    "5. Visualize:\n",
    "   - Confusion Matrix (heatmap)\n",
    "   - Decision Boundary of the classifier\n",
    "\n",
    "---\n",
    "\n",
    "## Dataset Details\n",
    "\n",
    "The dataset is generated using:\n",
    "\n",
    "- `n_samples = 1000` (total samples)\n",
    "- `n_features = 2` (two input features)\n",
    "- `n_informative = 2` (both features are informative)\n",
    "- `n_redundant = 0`\n",
    "- `n_clusters_per_class = 1`\n",
    "- `random_state = 42` (for reproducible results)\n",
    "\n",
    "Train-test split:\n",
    "- Training: **70%**\n",
    "- Testing: **30%**\n",
    "\n",
    "---\n",
    "\n",
    "## Tech Stack / Libraries Used\n",
    "\n",
    "- **Python 3.x**\n",
    "- **scikit-learn** (dataset generation + model training + evaluation)\n",
    "- **numpy** (meshgrid + numerical operations)\n",
    "- **matplotlib** (plots)\n",
    "- **seaborn** (confusion matrix heatmap)\n",
    "\n",
    "---\n",
    "\n",
    "## Installation\n",
    "\n",
    "Install the required dependencies:\n",
    "\n",
    "```bash\n",
    "pip install scikit-learn numpy matplotlib seaborn\n"
   ]
  },
  {
   "cell_type": "raw",
   "id": "ab0021ab-e6d6-420a-b9cf-773403526d47",
   "metadata": {},
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python [conda env:base] *",
   "language": "python",
   "name": "conda-base-py"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.13.5"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 5
}

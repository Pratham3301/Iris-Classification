# Iris Species Prediction

This repository contains code to train models for predicting Iris species using the Iris dataset. It includes an SVM model and a TensorFlow neural network model.

## Table of Contents

- Introduction
- Dataset
- Models
- Setup
- Usage
- Contributing
- License

## Introduction

The goal of this project is to classify Iris species using machine learning models. Two models are trained:
- Support Vector Machine (SVM)
- TensorFlow Neural Network

## Dataset

The dataset used is the famous Iris dataset, which contains 150 samples of Iris flowers, each with four features:
- Sepal length
- Sepal width
- Petal length
- Petal width

There are three classes (species) in the dataset:
- Setosa
- Versicolor
- Virginica

## Models

1. **SVM Model**: A linear SVM classifier.
2. **TensorFlow Model**: A neural network with two hidden layers.

## Setup

### Prerequisites

- Python 3.x
- Joblib
- TensorFlow
- Scikit-learn
- Pandas
- Seaborn
- Matplotlib

### Installation

1. Clone the repository:
    \`\`\`bash
    git clone https://github.com/yourusername/iris-species-prediction.git
    cd iris-species-prediction
    \`\`\`

2. Create and activate a virtual environment (optional but recommended):
    \`\`\`bash
    python3 -m venv venv
    source venv/bin/activate   # On Windows: venv\\Scripts\\activate
    \`\`\`

3. Install the required packages:
    \`\`\`bash
    pip install -r requirements.txt
    \`\`\`

## Usage

To train and evaluate the models, run the provided Jupyter notebooks or Python scripts. The trained models are saved as \`svm_model.pkl\` and \`tf_model.h5\`.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
"""

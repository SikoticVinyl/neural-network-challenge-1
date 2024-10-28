# Student Loan Risk Assessment Neural Network

## Project Overview
This project implements a neural network model to assess student loan risk and recommend loan options. Using TensorFlow/Keras, the system analyzes various student attributes to predict credit rankings and provide personalized loan recommendations.

## Features
- Neural network model for credit risk assessment
- Data preprocessing and standardization
- Model evaluation and prediction capabilities
- Context-based filtering for loan recommendations
- Export/import functionality for trained models

## Technologies Used
- Python 3.10
- TensorFlow/Keras
- Pandas
- Scikit-learn
- StandardScaler for data normalization

## Model Architecture
- Input Layer: 11 features
- Hidden Layer 1: 6 neurons (ReLU activation)
- Hidden Layer 2: 3 neurons (ReLU activation)
- Output Layer: 1 neuron (Sigmoid activation)

## Key Features Analyzed
- Payment history
- Location parameters
- STEM degree scores
- GPA rankings
- Alumni success rates
- Study major codes
- Time to completion
- Finance workshop scores
- Cohort rankings
- Total loan scores
- Financial aid scores

## Model Performance
- Accuracy: 73%
- Precision: 0.73
- Recall: 0.73
- F1-Score: 0.73

## Possible Future Enhancements
- Integration of additional contextual data:
  - Personal/household income
  - Current debt information
  - Industry-specific employment rates
  - Regional cost of living data
- Enhanced recommendation system using context-based filtering
- Bias mitigation strategies
- Real-time economic factor adjustments

## Installation and Usage
1. Clone the repository
2. Install required dependencies:
```bash
pip install tensorflow pandas scikit-learn
```
3. Run the Jupyter notebook or Python script
4. Model will be saved as 'student_loans.keras'

## Model Performance
The nerual network model achieved a balanced performance with an accuracy of 73% across all metrics (precision, recall, and F1-score). This consistent performance across metrics suggests the model is reliable and unbiased in its predictions, though there is room for improvement.

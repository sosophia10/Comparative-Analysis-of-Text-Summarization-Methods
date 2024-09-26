# NLP-Classification-and-Analysis-Using-Logistic-Regression-and-SVM

## Overview
This project implements **Natural Language Processing (NLP)** techniques to classify text data. Using models such as **Logistic Regression** and **Support Vector Machines (SVM)**, the project processes text data and evaluates the classification performance of these models. The project includes data preprocessing, feature extraction, and performance metrics for both classifiers.

## Features
- **Data Preprocessing**: Includes tokenization, stopword removal, and TF-IDF vectorization to convert text into numerical features.
- **Model Training**: Implements Logistic Regression and SVM for text classification tasks.
- **Evaluation Metrics**: Assesses model performance using metrics such as accuracy, precision, recall, and F1-score.
- **Visualization**: Provides visual insights into model performance through confusion matrices and accuracy plots.

## Technologies Used
- **Python**: For data processing, model building, and analysis.
- **Pandas & NumPy**: For data manipulation and analysis.
- **Scikit-learn**: For implementing machine learning models and evaluation.
- **Matplotlib & Seaborn**: For visualization and graphical analysis.
- **Jupyter Notebook**: For step-by-step interactive code execution and result visualization.

## Setup and Installation

### Prerequisites
- Python 3.x installed on your system.
- **Jupyter Notebook** to run the project code.
- Required Python libraries: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, and `seaborn`.

### Installation Steps
1. Clone the repository:
   ```
   git clone https://github.com/your-username/nlp-classification.git
   ```

2. Navigate to the project directory:
   ```
   cd nlp-classification
   ```

3. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

4. Launch the Jupyter Notebook to explore the project:
   ```
   jupyter notebook AIT526_SophiaHerman_Lab2.ipynb
   ```

## Data
The project uses a labeled dataset for text classification. The dataset is preprocessed using NLP techniques such as tokenization, stopword removal, and TF-IDF vectorization. After preprocessing, the data is passed through Logistic Regression and SVM models for classification.

## Model Evaluation
- Logistic Regression: The model is evaluated based on its ability to classify text into the correct categories.
- SVM: Support Vector Machines are also used to classify the data, and the model's performance is compared to Logistic Regression.
- Confusion Matrix: A confusion matrix is plotted to provide insights into the classification results.

## Results
The project reports the following metrics for each model:
- Accuracy: The percentage of correct predictions.
- Precision and Recall: Measures of the models' relevance in classification tasks.
- F1-score: A combined metric of precision and recall to balance performance evaluation.


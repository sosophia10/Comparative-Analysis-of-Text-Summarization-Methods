# Comparative-Analysis-of-Text-Summarization-Methods

## Overview
This project focuses on comparing two popular text summarization techniques: **Extractive Summarization** and **Abstractive Summarization**. The project is implemented in Python using Natural Language Processing (NLP) tools to process a dataset, generate summaries with both methods, and evaluate the results using metrics such as ROUGE.

## Features
- **Extractive Summarization**: Selects key sentences from the original text to create a summary.
- **Abstractive Summarization**: Generates summaries by paraphrasing and rewording the text, producing more human-like summaries.
- **Evaluation**: Uses ROUGE metrics to compare the performance of both methods.

## Technologies Used
- **Python**: Core programming language used for implementing summarization techniques.
- **NLTK and SpaCy**: For text processing and extraction.
- **Transformers (Hugging Face)**: For building and applying pre-trained models for abstractive summarization.
- **Jupyter Notebook**: For code implementation and result visualization.

## Setup and Installation

### Prerequisites
- **Python 3.x** installed on your system.
- Libraries such as `pandas`, `nltk`, `transformers`, `spacy`, `rouge-score`.

### Installation Steps
1. Clone the repository:
   ```
   git clone https://github.com/sosophia10/Comparative-Analysis-of-Text-Summarization-Methods.git
   ```

2. Navigate to the project directory:
   ```
   cd text-summarization-comparison
   ```

3. Install dependencies:
   ```
   pip install -r requirements.txt

   ```

4. Launch the Jupyter Notebook to explore the project:
   ```
   jupyter notebook AIT526_SophiaHerman_Lab2.ipynb
   ```

## Usage
- Text Preprocessing: Preprocess the dataset to clean and tokenize the text.
- Summarization: Generate summaries using both extractive and abstractive techniques.
- Evaluation: Use ROUGE metrics to evaluate the accuracy and quality of the summaries.

### Example Commands
- To generate extractive summaries:
   ```
   python extractive_summarization.py
   ```

- To generate abstractive summaries:
   ```
   python abstractive_summarization.py
   ```

  

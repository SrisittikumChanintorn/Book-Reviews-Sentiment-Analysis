# 📚 Book Reviews Sentiment Analysis

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Transformers](https://img.shields.io/badge/Transformers-4.0%2B-yellow)
![VADER](https://img.shields.io/badge/VADER-3.3.2-green)
![License](https://img.shields.io/badge/License-MIT-brightgreen)

A comparative sentiment analysis of book reviews using both rule-based (VADER) and deep learning (Transformer) approaches.

## 🔍 Project Overview

This project analyzes sentiment in book reviews using two complementary models:

1. **VADER (Valence Aware Dictionary and sEntiment Reasoner)**: A lexicon and rule-based sentiment analysis tool specifically designed for social media content and short texts.

2. **Transformer-based model (DistilBERT)**: A pre-trained transformer model fine-tuned for sentiment classification.

## ✨ Features

- **Dual analysis approach** providing comparative insights
- **Text preprocessing** to clean and normalize review data
- **Sentiment classification** into positive, neutral, and negative categories
- **Visual presentation** of sentiment distribution
- **Quantitative measurement** of overall sentiment

## 🛠️ Technologies

- **Python**: Core programming language
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computing
- **Matplotlib**: Data visualization
- **VADER Sentiment**: Rule-based sentiment analysis
- **Transformers**: Pre-trained NLP models (Hugging Face)
- **RegEx**: Text cleaning and preprocessing

## 📊 Methodology

### Data Processing
- Load book reviews from CSV
- Convert text to lowercase
- Remove special characters and punctuation
- Prepare data for sentiment analysis

### VADER Analysis
- Apply SentimentIntensityAnalyzer to extract compound polarity scores
- Categorize text into negative (-1 to -0.1), neutral (-0.1 to 0.1), or positive (0.1 to 1)
- Visualize results with a color-coded bar chart

### Transformer Analysis
- Implement DistilBERT model using Hugging Face's pipeline
- Classify text into POSITIVE or NEGATIVE categories
- Calculate overall sentiment score (positive_count - negative_count)
- Visualize results with comparative bar chart

## 📋 Requirements

```
pandas==2.2.2
matplotlib==3.8.0
tensorflow==2.15.0
keras==2.15.0
vaderSentiment==3.3.2
transformers==4.41.1
huggingface-hub==0.23.0
tokenizers==0.19.0
```

## 🚀 Getting Started

1. Clone this repository
   ```
   Clone the repository to your local machine
   ```

2. Create or select a Python virtual environment
   ```
   Create a new virtual environment or select an existing interpreter
   ```

3. Install required packages
   ```
   pip install -r requirements.txt
   ```

4. Open main.ipynb and run the cells sequentially



## 📈 Results

The project provides:
- Distribution of sentiment categories from VADER analysis
- Counts of positive vs negative classifications from the transformer model
- Overall sentiment score for the dataset
- Comparative visualizations between different sentiment analysis approaches

## 🤔 Findings

- VADER provides more nuanced categorization with its neutral class
- Transformer models excel at capturing complex expressions and context
- Combining both approaches provides more robust sentiment insights
- Ratings and sentiment scores show strong correlation, validating both methods

## 🔮 Future Work

- Incorporate aspect-based sentiment analysis
- Experiment with different transformer models
- Add interactive visualization dashboard
- Extend analysis to compare books by genre
- Implement time-series analysis for tracking sentiment changes over time

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgements

- VADER Sentiment Analysis by C.J. Hutto and Eric Gilbert
- Hugging Face's Transformers library
- Book review dataset contributors

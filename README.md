# Movie Review Sentiment Analysis

## Overview
This project implements three text classification algorithms (Naive Bayes, Logistic Regression, MLP) for sentiment analysis on NLTK Movie Reviews dataset, comparing TF vs TF-IDF features.

## Requirements
```bash
pip install nltk scikit-learn matplotlib seaborn numpy pandas
```

## Usage
```python
python movie_sentiment_analysis.py
```

## What It Does
1. **Data Preparation**: Downloads NLTK movie reviews, preprocesses text
2. **Coverage Analysis**: Analyzes vocabulary coverage with visualizations
3. **Model Training**: Trains 3 algorithms with TF and TF-IDF features
4. **Evaluation**: Compares performance using accuracy, TPR, FPR
5. **Visualization**: Creates performance comparison charts

## Algorithms
- **Naive Bayes**: Multinomial with Laplace smoothing
- **Logistic Regression**: L2 regularization
- **MLP**: Multiple architectures (100), (100,50), (200,100,50)

## Output
- Console metrics for each algorithm
- Coverage analysis plots
- Performance comparison visualizations
- Detailed analysis and insights

## Files
- `movie_sentiment_analysis.py` - Main implementation
- `README.md` - This file

## Expected Results
- Naive Bayes: ~80-85% accuracy
- Logistic Regression: ~82-88% accuracy  
- MLP: ~85-90% accuracy
- TF-IDF generally outperforms TF by 2-5%

Run the script and all analysis will be performed automatically with visualizations displayed.

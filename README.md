# Disaster Tweet Classification

## Overview
This project classifies tweets as **disaster-related or not** using **Natural Language Processing (NLP) and Machine Learning** techniques. The dataset contains tweets labeled to indicate whether they describe real disasters or not.

## Features
- **Text Preprocessing**: Tokenization, stopword removal, and stemming
- **Feature Extraction**: TF-IDF vectorization
- **Model Training & Evaluation**: Multinomial Naïve Bayes, Logistic Regression, and K-Nearest Neighbors (KNN)
- **Accuracy**:
  - **Multinomial Naïve Bayes**: 80.7%
  - **Logistic Regression**: 80%
  - **KNN**: 66%

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/Disaster-Tweet-Classification.git
   cd Disaster-Tweet-Classification
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the script:
   ```bash
   python classify_tweets.py
   ```

## Future Improvements
- Implement **deep learning models (LSTMs, Transformers)**
- Deploy as a **web application**
- Enhance preprocessing for better accuracy

## Contributing
Feel free to contribute by creating issues or submitting pull requests.

## License
This project is licensed under the **MIT License**.

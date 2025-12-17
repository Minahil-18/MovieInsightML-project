# MovieInsightML – Revenue Forecasting & Genre Classification

## Group Members
- Minahil Rizwan (23I-0114)  
- Hamda Shahid (23I-0069)  

## Project Description
MovieInsightML is a machine learning project that predicts a movie’s revenue (regression) and classifies its main genre (classification) using a combination of numeric and textual features from a movie dataset. The project integrates text preprocessing (TF-IDF, sentiment analysis, word counts) with numeric features (budget, popularity, runtime, votes) and explores TinyML deployment for edge devices.

## Required Libraries / Dependencies
- Python 3.x  
- pandas  
- numpy  
- scikit-learn  
- matplotlib  
- seaborn  
- nltk / textblob (for sentiment analysis)  
- tensorflow / keras (for TinyML deployment)  
- edge-impulse-cli (optional, for Edge Impulse deployment)  

Install dependencies using:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn nltk textblob tensorflow

Instructions to Run the Code

Clone or download the project repository.

Ensure all dependencies are installed.

Load the dataset (movies.csv) in the same folder as the code.

Run the preprocessing script to clean data and extract features.

Run the regression and classification scripts to train models and evaluate metrics.

For TinyML deployment:

Convert the trained model to TFLite format.

Optionally, test on Edge Impulse or simulated edge devices.

Visualizations for model performance and feature importance will be generated automatically.
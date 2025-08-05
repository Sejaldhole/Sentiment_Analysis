# Sentiment Analysis using TF-IDF and Logistic Regression

This project performs **Sentiment Analysis** on the IMDB dataset of 50,000 movie reviews using **TF-IDF Vectorization** and a **Logistic Regression** model. It classifies movie reviews as either **positive** or **negative**.

##  Dataset

- **Name:** IMDB Dataset of 50K Movie Reviews
- **Source:** [Kaggle](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)
- **Columns:**
  - `review`: Text of the review
  - `sentiment`: Label (`positive` or `negative`)

##  Technologies Used

- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

##  Steps Performed

1. Load and preprocess dataset
2. Convert sentiment labels to numeric
3. Vectorize text using TF-IDF
4. Train a Logistic Regression model
5. Evaluate accuracy and metrics
6. Visualize confusion matrix

## SENTIMENT_ANALYSIS
├── sentiment-analysis.ipynb      
├── requirements.txt              
├── README.md                    
└── dataset
      └── imdb-dataset.csv          

##  Requirements

Install the following packages before running the notebook:

```bash
pip install -r requirements.txt
```

##  Results

- High accuracy (~85–90%) using Logistic Regression
- Effective classification between positive and negative reviews
- Confusion matrix and classification report provided

##  Files

- `Sentiment_Analysis.ipynb`: Main Jupyter notebook
- `requirements.txt`: List of Python packages
- `README.md`: Project overview

##  License

This project is for educational and internship purposes.

Fake News Detection Using Machine Learning
Project Overview
A machine learning-based application that identifies whether a news article is Fake or Real using Natural Language Processing (NLP).
Technologies Used
Python | Pandas | NumPy | Scikit-learn | TF-IDF | Passive Aggressive Classifier | Matplotlib | Seaborn
Dataset
The project uses the Fake and Real News Dataset from Kaggle.

Dataset Source:[Fake and Real News Dataset – Kaggle](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)

Download the dataset, extract it, and use Fake.csv and True.csv in the notebook.
Key Features
- Fake and Real news classification
- Text preprocessing and TF-IDF feature extraction
- Machine learning model training
- Confusion matrix visualization
- Performance evaluation
Model Performance
Test Accuracy: 98.81%

Evaluation Metrics: Precision, Recall and F1-score.

Results are based on the current train-test split and may vary with different preprocessing or data splits.
Project Structure
fakenews/
├── fake_news_detection.ipynb
├── README.md
└── requirements.txt
Installation
pip install pandas numpy matplotlib seaborn scikit-learn kagglehub
How to Run
1. Clone this repository.
2. Open the notebook in Google Colab or Jupyter Notebook.
3. Run all cells.
4. Upload Fake.csv and True.csv when prompted.
5. View the model results and evaluation metrics.

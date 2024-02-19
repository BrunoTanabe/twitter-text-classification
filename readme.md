# 🐦 Twitter Text Classification 🐦
This project focuses on sentiment analysis of tweets in Portuguese using machine learning techniques. The main goal is to classify tweets as positive or negative based on their content. Below is a detailed explanation of the project components, from data preprocessing to model evaluation.

## 🎯 Project Objectives 🎯
The main objective of this project is to classify tweets into positive and negative sentiments using natural language processing (NLP) techniques. Specifically, the project aims to achieve the following objectives:
- Develop a text classification model capable of accurately categorizing tweets based on sentiments.
- Utilize preprocessing techniques to clean and prepare text data for analysis.
- Evaluate the performance of the classification model on training and testing datasets.

## ℹ️ Key Features ℹ️
- Importing necessary libraries for data manipulation, visualization, and machine learning.
- Loading training and testing databases containing tweets for sentiment analysis.
- Text preprocessing steps including lowercase conversion, username handling, URL handling, emoticon handling, irrelevant word removal, lemmatization, and punctuation removal.
- Creating a text classification model using the `textcat` component of spaCy.
- Training the model using the training dataset and evaluating its performance.
- Testing the trained model on sample sentences and evaluating its predictions.
- Model evaluation using accuracy score and confusion matrix.

## 💻 Technologies Used 💻
The project utilizes the following technologies and libraries:
- Python 🐍
- spaCy 🧠
- NumPy 🔢
- pandas 🐼
- scikit-learn 🧮
- Matplotlib 📊
- Seaborn 🌊

## 📋 Requirements 📋
To run the project, make sure you have the following installed:
- Python 3.x
- Jupyter Notebook or another Python environment
- Required Python libraries: spaCy, NumPy, pandas, scikit-learn, Matplotlib, Seaborn

## ▶️ Setting Up the Project ▶️
### Setting up the environment on Linux
1. Clone this repository using the command `git clone https://github.com/BrunoTanabe/twitter-text-classification`.
2. Navigate to the `twitter-text-classification` folder using the command `cd twitter-text-classification`.
3. Create a virtual environment using the command `python3 -m venv venv`.
4. Activate the virtual environment using the command `source venv/bin/activate`.
5. Install requirements using the command `pip install -r requirements.txt`.
6. Execute the command `python -m spacy download pt_core_news_lg` to download the NLP model for text processing.

### Setting up the environment on Windows
1. Clone this repository using the command `git clone https://github.com/BrunoTanabe/twitter-text-classification`.
2. Navigate to the `twitter-text-classification` folder using the command `cd twitter-text-classification`.
3. Create a virtual environment using the command `python -m venv venv`.
4. Activate the virtual environment using the command `.\venv\Scripts\activate`.
5. Install requirements using the command `pip install -r requirements.txt`.
6. Execute the command `python -m spacy download pt_core_news_lg` to download the NLP model for text processing.

## ⚠️ Important Note ⚠️
Ensure that the file paths for loading and saving data/models are correctly configured based on the structure of your local directory.

## ✍️ Authors ✍️
This project was created by Bruno Tanabe. For any questions or feedback, please contact tanabebruno@gmail.com.
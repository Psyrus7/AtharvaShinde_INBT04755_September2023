# AtharvaShinde_INBT04755_September2023
# THIS PROJECT IS MADE FOR INTERNSHIP iNeuBytes


here is the preprocessed review (preprocessed_imdb.csv) file : https://drive.google.com/file/d/1-5NMjrzZqoWOPbkBL9n8SPKScrkWoDcg/view?usp=sharing

Note : Make sure that yyou changed the paths in the code according to where your preprocessed_imdb.csv is saved.


#IMDb Sentiment Analysis
This project focuses on sentiment analysis using IMDb movie reviews. The goal is to classify movie reviews as either positive or negative based on the sentiment expressed in the text.

Dataset
The IMDb dataset used in this project contains preprocessed movie reviews. The dataset was cleaned and preprocessed to remove any unnecessary information.

Files Included:
preprocessed_imdb.csv: The cleaned and preprocessed IMDb dataset.
Requirements
Make sure you have the following libraries installed to run the code:

pandas: Data manipulation library
nltk: Natural Language Toolkit for text preprocessing
sklearn: Scikit-learn for machine learning
matplotlib: Visualization library
seaborn: Data visualization library
wordcloud: Library for generating word clouds
You can install these libraries using pip install <library_name>.

Code Usage
Clone this GitHub repository to your local machine.
Download the preprocessed IMDb dataset (preprocessed_imdb.csv) from the provided Google Drive link.
Place the preprocessed_imdb.csv file in the same directory as the project code.
Open the Jupyter notebook or Python script and run the code.
Project Structure
The project code is organized as follows:

Data loading and preprocessing: Cleaning and preprocessing of the IMDb dataset.
Feature extraction: Using TF-IDF (Term Frequency-Inverse Document Frequency) for feature extraction.
Sentiment analysis: Training a Multinomial Naive Bayes classifier for sentiment analysis.
Visualization: Visualizing sentiment distribution, word clouds, top frequent words, confusion matrix, precision-recall curve, and ROC curve.
Results
The project provides the following results:

Accuracy of sentiment analysis.
Sentiment distribution visualization.
Word cloud of most frequent words.
Top N most frequent words.
Confusion matrix.
Precision-recall curve.
ROC curve.
## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/Psyrus7/Major_Project.ipynb
   cd imdb-sentiment-analysis

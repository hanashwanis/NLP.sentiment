 Movie Review Sentiment Analysis using NLP
This project is a machine learning application that classifies movie reviews as either **Positive** or **Negative** using Natural Language Processing (NLP) techniques.
Features :
- **Text Preprocessing**: Cleans HTML tags, removes special characters, and normalizes text.
- **TF-IDF Vectorization**: Converts text data into numerical features for the model.
- **Machine Learning**: Uses Logistic Regression to achieve high-speed and accurate classification.
- **Custom Prediction**: A built-in function to test your own movie reviews.

Tech Stack :
- **Language**: Python 3.x
- **Libraries**: 
  - `pandas` (Data manipulation)
  - `scikit-learn` (Machine Learning)
  - `BeautifulSoup4` (HTML cleaning)
  - `re` (Regular Expressions)

 Project Structure :
- `nlp_sentiment.ipynb`: Main Jupyter Notebook containing the code logic.
- `IMDB Dataset.csv`: The dataset containing movie reviews and labels.
- `README.md`: Project documentation.
- 
**Methodology**
The project follows a standard NLP pipeline:
Data Cleaning: Removing noise (HTML tags and punctuation).
Splitting: Dividing data into 80% training and 20% testing sets.
Feature Extraction: Using TfidfVectorizer to find important words.
Training: Fitting a LogisticRegression model.
Evaluation: Measuring performance using accuracy scores.

**Example Usage:**
Python
Input:
print(predict_sentiment("The cinematography was breathtaking and the acting was top-notch!"))
Output:
"positive"

## Amazon Reviews Sentiment Analysis with NLP and Machine Learning
Link to my repo containing other data science projects: [click the link](https://github.com/9more/test_repo)
### Project Overview
This project analyses customer reviews from the Amazon Reviews dataset available on Kaggle to predict sentiment using Natural Language Processing (NLP) and traditional machine learning techniques.
The objective is to transform unstructured text data into meaningful numerical representations and build an optimised classification pipeline capable of accurately identifying customer sentiment.
The project demonstrates expertise in:
•	Data ingestion and preprocessing
•	Text cleaning and transformation
•	Feature engineering using NLP techniques
•	Machine learning model development and optimisation
•	Pipeline automation and hyperparameter tuning
### Dataset
The dataset was sourced from the Kaggle Amazon Reviews collection and contains customer review text alongside associated sentiment labels.
Key features include:
•	Review text
•	Review ratings
•	Sentiment labels
•	Product metadata (where available)
### Technical Stack
•	Python
•	Pandas
•	NumPy
•	Scikit-learn
•	NLP
•	CSV processing
•	Jupyter Notebook
### Project Workflow
#### Data Ingestion and Cleaning
The workflow begins with processing raw CSV files to ensure the data is suitable for analysis within Pandas.
Key preprocessing steps include:
•	Loading and validating CSV files
•	Handling malformed records and inconsistent formatting
•	Removing duplicate entries
•	Managing missing values
•	Standardising text encoding
•	Cleaning and normalising review text
The cleaned dataset is then loaded into Pandas for downstream processing.
Natural Language Processing (NLP)
A comprehensive NLP pipeline was developed to convert unstructured review text into machine-readable features.
#### Text Preprocessing
The preprocessing stage includes:
•	Lowercasing text
•	Removing punctuation and special characters
•	Eliminating stop words
•	Tokenisation
•	Text normalisation
#### Feature Engineering
Two complementary vectorisation techniques were combined to capture both term frequency and term importance:
CountVectorizer: Converts text into a matrix of token counts.
TF-IDF (Term Frequency–Inverse Document Frequency): Weighs terms according to their relevance across the corpus.
This hybrid approach improves the model's ability to distinguish meaningful patterns within customer reviews while reducing the influence of common, less informative words.
#### Machine Learning Pipeline
An end-to-end Scikit-learn pipeline was implemented to automate preprocessing, feature extraction, model training, and evaluation.

The pipeline consists of:
1. CSV data ingestion and cleaning
2. Pandas-based preprocessing
3. Text embedding using CountVectorizer and TF-IDF
4. Model training and evaluation
5. Hyperparameter optimisation using GridSearchCV
Models Evaluated
The following machine learning algorithms were assessed:
•	Random Forest Classifier
•	Support Vector Machine (SVM)
•	K-Nearest Neighbours (KNN)
### Hyperparameter Tuning
GridSearchCV was used to systematically evaluate multiple model configurations and identify the optimal combination of:
•	Vectorisation parameters
•	Feature extraction settings
•	Model hyperparameters
This approach ensures robust model selection and maximises predictive performance.
Results

The project compares the performance of multiple classification algorithms using evaluation metrics such as:
F1-Score
Confusion Matrix
The best-performing model was selected based on cross-validated performance metrics obtained through GridSearchCV.

### Key Skills Demonstrated
•	Natural Language Processing (NLP)
•	Text classification
•	Feature engineering
•	CountVectorizer
•	TF-IDF vectorisation
•	Scikit-learn Pipelines
•	GridSearchCV
•	Hyperparameter optimisation
•	Data cleaning and preprocessing
•	Model evaluation
•	Python programming
•	Pandas data manipulation
### Future Improvements
Potential enhancements include:
•	Implementing word embeddings such as Word2Vec or GloVe
•	Exploring transformer-based models such as BERT
•	Deploying the model as an API
•	Building an interactive dashboard for sentiment analysis
•	Adding experiment tracking and model versioning
### Author
Developed as part of a machine learning and NLP portfolio project focused on extracting actionable insights from customer feedback at scale.

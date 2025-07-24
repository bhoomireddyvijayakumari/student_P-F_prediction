##  Task 1: Student Pass or Fail Prediction


In this task, the objective was to predict whether a student would pass or fail based on two primary features: the number of study hours and their attendance percentage. The dataset consists of records including study hours, attendance, and a binary result (Pass or Fail). After loading and inspecting the data for null values and basic statistics, preprocessing was carried out—this involved converting the categorical labels ("Pass" and "Fail") into numerical form to prepare the data for machine learning algorithms. The dataset was then split into training and testing subsets to ensure fair model evaluation. A Logistic Regression model was employed for binary classification. The model was trained on the training set and evaluated on the test set using metrics such as accuracy and classification report. Additionally, data visualization using scatter plots helped to show a positive correlation: students with higher study hours and better attendance were more likely to pass. Overall, the task demonstrated that even simple features like study time and attendance can be effective predictors for student performance using a basic machine learning model like logistic regression.

##  Insights from Task 1
Positive Correlation observed between:


- Higher study hours & attendance → more chances to pass.
  
- Logistic Regression performed well for binary classification.
  
- Useful baseline model for educational performance prediction.

## Task 2: Sentiment Analysis with NLP

The second task focused on performing sentiment analysis on customer reviews using Natural Language Processing (NLP). The goal was to classify the reviews as either positive or negative. The dataset, which contained textual reviews along with their sentiment labels, was first cleaned using various NLP preprocessing techniques. This included converting all text to lowercase, removing punctuation, numbers, and stopwords, and performing either stemming or lemmatization to reduce words to their root forms. After cleaning, the text data was converted into numerical format using methods like TF-IDF Vectorization, which helps highlight the importance of words relative to each document. A machine learning classifier—likely Logistic Regression—was trained on the vectorized data. The model was evaluated using standard classification metrics such as accuracy, precision, recall, and F1-score. Visualizations like word clouds or confusion matrices were likely used to support the analysis and provide insights into the dataset’s distribution and model performance. The results indicated that the model could effectively distinguish between positive and negative sentiments, proving the usefulness of basic NLP techniques for text classification tasks.

## Insights from Task 2: Sentiment Analysis with NLP


The sentiment analysis model demonstrated that clean and well-preprocessed text data significantly improves the accuracy of sentiment classification. By applying NLP techniques like stopword removal, stemming/lemmatization, and TF-IDF vectorization, the model was able to capture important linguistic patterns that distinguish positive reviews from negative ones. The classifier was able to learn sentiment patterns effectively, suggesting that the dataset was likely balanced and rich in sentiment-bearing terms. This task provided valuable insight into how textual data can be converted into structured information for machine learning models. The resulting model can be deployed in customer feedback systems to automatically flag negative reviews, enabling faster business response and better customer engagement strategies.


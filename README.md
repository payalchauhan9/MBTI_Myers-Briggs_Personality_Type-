**MYERS-BRIGGS PERSONALITY TYPE PREDICTION USING NLP & MACHINE LEARNING**

![Screenshot 2024-10-14 205105](https://github.com/user-attachments/assets/05550b36-77a6-4945-b0cb-5f259d426223)

*INTRODUCTION*

MBTI stands for Myers-Briggs Type Indicator, a personality test that classifies people into one of 16 personality types based on four dimensions, namely: Introversion (I) - Extroversion (E), Intuition (N) - Sensing (S), Thinking (T) - Feeling (F), Judging (J) - Perceiving (P). The MBTI is the most widely used personality inventory in the world, with over 2 million test takers annually. However, research on the accuracy of the MBTI has had mixed results. In this project, I have developed a MBTI personality classifier that uses machine learning models to predict a person’s personality based on the 50 recent social media posts per user as input.

*Dataset Description*

The dataset is taken from kaggle. The dataset contains 2 columns and 8675 records.It contains features like type, post. There are 16 unique labels in column ‘type’ with no null values, each representing 16 MBTI type indicators. Also the post column has paragraphs which requires natural language processing to perform model training.

*🧰 Tools & Technologies*

•Languages: Python

•Libraries: Scikit-learn, Pandas, NumPy, NLTK, spaCy

•Techniques: NLP (text preprocessing, TF-IDF, word embeddings), classification (Logistic Regression, Random Forest, SVM), data visualization

•Model Evaluation: Accuracy, F1 Score

*Preprocessing*

We performed this to reduce the inconsistency in the data by removing the terms which don't contribute much to the person's personality.
1.Convert data into lowercase.

2.  Removing URLs and Links.

3. Removing special characters and numbers.
   
4. Removing extra spaces.
  
5. Removing Stopwords like of, the, or, etc using nltk.
  
6. Perform word Lemmatization i.e. grouping of words with the same purpose together.

*Modle Implementation*

From various classification algorithm I have implemented the following one:
• K Nearest Neighbour Classifier

• Gaussian Naive Bayes Classifier

• Support Vector Classifier

• Decision Tree Classifier

• XGBoost Classifier

*📈 Key Insights*

•Certain words and phrases were strong indicators of specific personality types (e.g., emotional vs. logical words).

•Achieved ~54% accuracy in predicting the broader personality traits (e.g., Introvert vs. Extrovert).

•Found that word choice and sentence structure varied significantly across personality groups.

*📊 Impact / Outcome *

•Demonstrated how personality insights can be extracted from unstructured text data, with applications in HR tech, mental health, and personalized marketing.

•Strengthened understanding of NLP pipelines and classification workflows.

•Gained practical experience in building models for psychological or behavioral prediction.



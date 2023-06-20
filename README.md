# Reviews-Classification-using-Naive-Bayes-XGBoost-and-LSTM

The dataset I used in this project is about reviews of customers about products of a business. This dataset includes main features of any product like product_name, price, rate, review, summary and sentiment (label).

In this project, I will find out what popular keywords are in positive, negative and neutral reviews by drawing word clouds.

Then I will build a text classification model. I use 3 models which are Naive Bayes, XGBoost and LSTM to classify the text and then I evaluate which is the best one.

The outline of the project as below:
1. Data mining
2. Pre-processing
  2.1. Drop null value of summary column
  2.2. Convert the data type of rate and price column to numeric form
  2.3. Find and remove outliers and anomalies
  2.4. Create more useful columns: convert sentiment to numeric form, create additional columns length_of_text
3. EDA
  3.1. Distribution of price, rating and length of text
  3.2. Percentage of sentiment and rating
  3.3. Correlation between sentiment-length of text, sentiment and rating
4. Text processing
  4.1. Remove punctuations
  4.2. Tokenize and remove stop words
  4.3. Lemmatize
  4.4. Drawing word clouds
5. Building models
  5.1. Naive Bayes
  5.2. XGBoost
  5.3. LSTM
6. Conclusion

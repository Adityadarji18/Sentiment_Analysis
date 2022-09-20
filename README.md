# Stock Price Prediction - 

Problem Statement - Predict if the stock will increase or decrease/remain constant based on top 25 news headings

Solution -

1) Here the first step will be to join all the news heading and then cleaning the data
2) Did lower case on the data and then replace all punctuations and unwanted characters which from the data using replace.
3) Now we have cleaned data will all alphabets in lowercase, then I created bag of words using count vectorizer on the data
4) Then created Random Forest classifier and Logistic Regression model both gave around 85% accuracy on the test data.

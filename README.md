# Cuisine-Classification-and-Restaurant-Analytics
Cuisine Classification and Restaurant Analytics is an end to end Data Science project. The project consists of the entire data science pipeline starting from data collection to data analytics to using Machine Learning and Deep Learning techniques to classify the cuisine of the restaurant and then creating and deploying a web application to the cloud.

## 1st Part: Data Collection:

  * Restaurant data is collected by scraping the website : https://www.dineout.co.in/delhi-restaurants/welcome-back
  * More than 5000 data points are scraped(250+ webpages) to extract the information about restaurants in Delhi NCR, India.
  * The data is first extracted, then cleaned and then stored in a csv file.
  
  **Tools, Technology and Libraries used:**
   * Python programming language
   * Selenium Web Driver is used for web scraping
   * Pandas, re (Regular Expression), NumPy are used for data cleaning and storing.
   
  * The scraped data is provided in the repository in a csv file format along with the data dictionary.


## 2nd Part: Restaurant Analytics and Cuisine Classification:

  * In this part, data analysis is done and useful insights are generated.
  * An attempt has been made to solve the Cuisine Classification problem, the data contains 90 different cuisines and most of the restaurants offer more than 1 cuisine. Hence, it is a multilabel classification problem.
  * Machine Learning Classifiers like **Logistic Regression, Decision Tree, Random Forest, XGBoost** etc. are trained using the **One Versus Rest** Technique.
  * State of the Art Deep Learning models like **BERT** is also used. However, due to lack of computation power the BERT model has been trained for few iterations which does not yield good results.
  * However, **XGBoost Classifier** gives good results.



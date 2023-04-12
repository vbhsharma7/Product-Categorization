# Product-Categorization
![image](https://user-images.githubusercontent.com/107554669/231459172-b690870a-c952-418d-acbf-e7b80e3bd30f.png)

This product categorization project is a natural language processing (NLP) based machine learning project that aims to predict the category of a product based on its name. The project involves several key steps such as data preprocessing, feature extraction, model training, and evaluation.

The data preprocessing step involves cleaning and preparing the raw data, which in this case is a list of product names and their corresponding categories. This step may involve tasks such as tokenization, stemming, and removing stop words.

The feature extraction step involves converting the preprocessed data into a format that can be used by machine learning algorithms. In this case, the product names are transformed into numerical features that can be used by the classifiers.

Several classifiers were trained and evaluated using cross-validation, with the performance of each classifier measured using the F1 score. The classifiers tested included Naive Bayes, SVM, KNN, and Decision Tree, with SVM showing the best performance.

Once a suitable classifier has been trained, it can be used to predict the category of new products based on their names. This can be done using a simple Python script that prompts the user to enter a product name and then returns the predicted category.

Overall, this project demonstrates the power of NLP-based machine learning techniques for automating the categorization of products based on their names. By accurately predicting the category of a product, this system can help improve the efficiency of inventory management and product search.

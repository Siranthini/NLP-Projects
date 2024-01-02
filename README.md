Text Classification Project
Description
This project is a Jupyter Notebook that demonstrates a text classification application with a Tkinter-based GUI. 
It allows users to categorize news articles into three categories: Business, Science, and Sports. The process involves:

Preprocessing Data: Implementing a function to read word documents into a DataFrame, mapping article text to "Text" and categories to "Class". 
Preprocessing includes text normalization and lemmatization.

Classifier Models and Performance Evaluation: The data is split into training and testing sets. 
Various classifiers are tested (SVM, Ridge, Multinomial NB, DecisionTree), and their performance is evaluated using accuracy, precision, and F1 score metrics.

GUI Creation and Prediction: A simple GUI allows users to input text and predict its category. 
The application processes the entered text and displays the predicted category.

This application demonstrates a practical implementation of text classification techniques and provides a user-friendly interface for real-time classification.

Technologies Used
Python: The primary programming language used for developing the application.
Tkinter: A Python library used to create the GUI interface.
Machine Learning Libraries: Such as scikit-learn, for implementing and evaluating classifiers like SVM, Ridge, Multinomial NB, and DecisionTree.
Pandas: For data manipulation and analysis, particularly for handling the dataset in DataFrame format.
Natural Language Processing (NLP) Techniques: Utilized for text preprocessing, including lemmatization and stop word removal.

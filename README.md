# Stellar-Classification
Data Visualization JComp - Classification of stars based on their spectral characteristics.

Stellar classification is the classification of stars based on their spectral characteristics. The classification scheme of galaxies, quasars, and stars is one of the most fundamental in astronomy. 
The classification scheme of galaxies, quasars, and stars is one of the most fundamental in astronomy. The early cataloguing of stars and their distribution in the sky has led to the understanding that they make up our own galaxy and, following the distinction that Andromeda was a separate galaxy to our own, 
numerous galaxies began to be surveyed as more powerful telescopes were built.
Information collected by SDSS(Sloan Digital Sky Survey) will be used for training the models. Information like 'Ascension Angle’, ‘Declination Action’, Ultraviolet Filter, green, red and infrared filter, red-shift, etc. will be used to make decisions regarding classification. 
The dataset contains 1,00,000 records and 18 features. 

## ML models:
 Model Training-
 Every model was trained over all the three dataframes.
1) SVM with polynomial kerne: SMV model was trained with a polynomial of degree 2 and its 
classification report and confusion matrix was displayed. Its ROC curve 
was also plotted.
2) SVM with RBF kernel: SMV model was trained with a RBF kernel and its classification report 
and confusion matrix was displayed. Its ROC curve was also plotted.
3) Logistic Regression: Logistic regression model was trained for 100 iterations and its accuracy 
was calculated.
4) Random Forest: Random forest model was trained and its accuracy along with the ROC 
curve was plotted.
5) Decision Tree: Decision tree model as trained and its accuracy was calculated.
6) Customized ANN: A custom neural network model with 3 layers was trained. The first dense 
layer contained 30 nodes with ReLU as the activation function. The second 
layer contained 20 nodes with ReLU as the activation function. The last 
layer contained only 3 nodes as there are 3 class to be predicted. It used the 
softmax function and predicted the output that had highest probability 
score. The model was trained for 10 epochs.
7) MLP (Multi Layer Perceptron): MLP with 7 layers was trained and its accuracy score was calculated

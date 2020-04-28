## In Vino Veritas

The project involves using the Random Forest Classifier for classifying the wine quality followed by the comparative analysis of the decision surfaces of the Random Forest, SVM, and the Decision Tree Classifier. The data for the project is available at the standard UCI Machine Learning repository. 

Inherently we are using Random Forest for classification where the classes are skewed. Wine quality scores are reported out of 8 and we classify a wine to be postive (1) only if the quality is greater than or equal to 7. As a result, using accuracy as the scoring metric of the classifier won't suffice and which is eveident from the plot as we could also get a fairly good accuracy by using a naive classifier. 

Instead, F1 score is the metric to be used and thus we can observe that the F1-score isn't good enough. 

We also performed the relative comparison of the decision boundaries in the case of Decision Trees, Random Forest and Support Vector Machines.

# ConfusionMatrix

What is Confusion Matrix?

In the field of machine learning, a confusion matrix, also known as a contingency 
table or an error matrix is a specific table layout that allows visualization of the
performance of an algorithm, typically a supervised learning one. Each column of the
matrix represents the instances in a predicted class, while each row represents the 
instances in an actual class. The name stems from the fact that it makes it easy to see if
the system is confusing two classes (i.e. commonly mislabeling one as another).

    Input: Dictionary [keys: actual, items: predicted]
    Output: Formatted confusion matrix on screen

Run: python ConfusionMatrix.py


Reference:https://en.wikipedia.org/wiki/Confusion_matrix

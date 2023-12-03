# Leaf_Multiclass_Classification
Classifying 92 species of leaves using multiclass classification algorithms.
Dataset Description
The dataset consists of approximately 1,584 images of leaf specimens (16 samples each of 99 species) which have been converted to binary black leaves against white backgrounds. Three sets of features are also provided per image: a shape-contiguous descriptor, an interior texture histogram, and a ﬁne-scale margin histogram. For each feature, a 64-attribute vector is given per leaf sample.
File descriptions
train.csv - the training set
test.csv - the test set
sample_submission.csv - a sample submission file in the correct format
images - the image files (each image is named with its corresponding id)
Data fields
id - an anonymous ID unique to an image
margin_1, margin_2, margin_3, ..., margin_64 - each of the 64 attribute vectors for the margin feature
shape_1, shape_2, shape_3, ..., shape_64 - each of the 64 attribute vectors for the shape feature
texture_1, texture_2, texture_3, ..., texture_64 - each of the 64 attribute vectors for the texture feature
Data Source 
Data is available at https://www.kaggle.com/c/leaf-classification/data
Machine Learning Algorithms 
Logistic Regression 
Linear Discriminant Analysis {Used for Dimensionality Reduction and Classification problems}

# CatVsNonCat

This is a small project, which demonstrates how to implement logistic regression classifier to recognize the cat images. The solution in this project is built on the idea of implementing Neural Networks.

# Files

1) Cat Classification.ipynb: Which has the implementation of the whole project
2) lr_utils.py: The data set is loaded via h5py; This file loads the data from two different files to the respective variables.
3) train_catvnon_cat.h5: This file consists of all the training examples
4) test_catvnon_cat.h5: Thii file consists of test examples

# Implementation

We have seperated the training and test data sets into two differnt files mentioned above. The structure of data inside is:
**train_catvnon_cat.h5:** ['list_classes', 'train_set_x', 'train_set_y']  
**test_catvnon_cat.h5:**['list_classes', 'test_set_x', 'test_set_y']
These two files are accessed to load this data into four respective numpy.array variables in lr_utils.py  
This data is later utilised in the Cat Classification.ipynb file to implement the algorithm (clear step-by-step procedure is mentioned in comments).
 

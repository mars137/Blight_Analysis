# Blight_Analysis

Repository for  blight analysis using detroit crime , blight violation and demolition permit data.

The datasets provided can be found at the Detroit Open Data Portal.

Step 1: Establish a list of all the buildings with their space extents.

Step 2: Generate a balanced data set for training and testing

Map demolition permits to buildings, derive positive labels.
Random sample a same amount of buildings with negative labels.
Concatenate them into a "training" set.

Note

This "training" set will later be divided into a (real) training set and a validation set. In this task it does not make much sense to use the remaining data as a "testing" set (at least no in a traditional sense) because we only got buildings that are not on the demolition list. And there's no way to figure out their true labels. So this part is a little bit like semi-supervised learning: I'll just evaluate the model on the validation set and use the remaining data for visualization and drawing conclusions. Anyway this is also what the task requires us to do.

Step 3: Develop a naive model and evalute its performance.

Step 4: Feature engineering.

Step 5: Develop a more advanced model.

Step 6: Evaluation and drawing conclusions.


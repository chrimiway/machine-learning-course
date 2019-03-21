Libraries:
1. pip install keras
2. pip install tensorflow


Files:

1. Team_G_code.ipynb: the code used to train and evaluate the final model
2. Team_G_load_model.ipynb: load the final model and generate predictions
3. model1.h5: final model

Predictions:

The input format to my model is (, 101, 101, 3). In order to make prediction, use Team_G_load_model.ipynb and change the "X_test_path" to the path of your test dataset.

Note: Since I did not fix random seed, the model you trained may be slightly different from our final model.
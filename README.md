# Diagnostic Model

Steps Followed:
•	Normalize the data using Standard Scaler of scikit-learn library.
•	Divide the dataset into train set, validation set and test set using train_test_split of scikit-learn. (60% - train, 20% 
  validation, 20% test)
•	Train the model on the train set.
•	Fine tune the model using validation set.
•	Test the model on the test set.

Observations:
Performance of the diagnostic model is more efficient as compared to the prognostic model due to the lack of sufficient data in the prognostic model.


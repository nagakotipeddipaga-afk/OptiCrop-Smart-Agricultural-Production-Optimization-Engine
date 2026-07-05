Description:

All models are evaluated and compared using important classification metrics such as Accuracy, Precision, Recall, F1-Score, Confusion Matrix, and ROC-AUC Score. These metrics help in identifying the model that provides the most accurate and reliable predictions for the dataset.

After evaluating the performance of all trained models, the best-performing model is selected based on its overall classification results and generalization capability. The finalized model is then serialized using pickle.dump() and stored as model.pkl so that it can be reused without retraining during deployment in the Flask web application.

# A machine-learning algorithm for predicting brain age using Rey–Osterrieth complex figure tests of healthy participants

ABSTRACT

Objective: Neuropsychologists widely use the Rey–Osterrieth complex figure test (RCFT) as part of
neuropsychological test batteries to evaluate cognitive function and assess constructional ability,
with age being the most significant factor. Our study investigated a supervised machine learning
(ML) algorithm to predict brain age gap using RCFT drawings from the healthy elderly community
for early dementia detection.

Participants and Methods: RCFT drawings from 1,970 healthy subjects (ages 45–90 years) were
collected from the Korean elderly community. We recorded subject demographic information
including: age, gender, and education level. We trained the ML model with RCFT copies, immediate
recall, delayed recall, and education level of the healthy subjects using CNN regression algorithm
from Keras (https://keras.io/) with the Tensorflow library.

Results: The performance was evaluated by the mean absolute error (MAE) and root mean
squared error (RMSE) between the predicted age and the chronological age based on a test dataset
of 300 healthy subjects. The CNN regression model achieved an MAE of 7.2 years in predicting
the brain age gap of the subjects, with an RMSE of 8.9 years.
Conclusion: The MAE and RMSE accuracies of the CNN regression model predicting the brain age
gap showed the model could be a potential biomarker for individual brain aging and a cost-effective
method for early dementia detection.

Proposed convolutional neural network (CNN) for a regression architecture. Abbreviations: RCFT: Rey–Osterrieth Figure Test; CNN: Convolutional Neural Network; FNN: Feed-Forward Neural Network.Note. Age prediction (45–90 years).


![image](https://user-images.githubusercontent.com/46183754/212355634-5bd04d82-47c6-4952-a136-4b00d28fddf4.png)

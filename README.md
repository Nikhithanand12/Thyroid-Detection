# Thyroid-Detection-using-ML
The fundamental objective of this work is to employ Machine Learning
methods for the purpose of reliably diagnosing primary hypothyroid,
secondary hyperthyroid, compensated hyperthyroid and negative (no
thyroid) problems in patients. We did this by using the thyroid dataset
from the UCI Machine Learning repository to train several classification
algorithms.
There are a number of benefits to employing machine learning for
thyroid diagnosis over more conventional methods. The ability to
swiftly and properly analyse massive amounts of data is a significant
benefit. Data from medical records, laboratory tests, and other sources
can be processed by machine learning algorithms, allowing for very
accurate pattern recognition and prediction.
Another advantage is the ability to customize the detection process for
individual patients. Machine learning algorithms can be trained on data
from specific patient populations, allowing for personalized diagnosis
and treatment plans. This approach can help healthcare providers deliver
more effective and efficient care.
In addition, machine learning-based thyroid detection can reduce the
risk of human error. Traditional methods of thyroid detection rely on
manual interpretation of lab results and other data, which can be prone
to errors. Machine learning algorithms, on the other hand, can analyze
data objectively and consistently, reducing the risk of misdiagnosis or
missed diagnoses.
Random Forest best params: { criterion= 'entropy', max_depth= 3, max_fe
atures= 'auto', n_estimators= 100}.
AUC for RF:0.9576819167909485
The best Random Forest model found using GridSearechCV ,has shown an
AUC of 0.95.
KNN best params: { leaf_size= 30, algorithm= 'ball_tree', n_neighbors= 4,
p= 2}.
AUC for knn:0.9864854651972423
The best KNN model found using GridSearechCV has shown an AUC of 0
.95
Final results as ,
Random Forest Classifier:-
F1 score = 0.831
Precision_Score = 0.8343247257119747
Recall_Score = 0.8311072813442482
KNN classifier :-
F1 score = 0.94
Precision_Score = 0.9554703235243759
In general, the use of machine learning to the diagnosis of thyroid
conditions has a great deal of promise for enhancing the clinical results
of patients and expanding the area of medicine.


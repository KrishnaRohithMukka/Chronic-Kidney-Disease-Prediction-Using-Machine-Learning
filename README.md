# Chronic-Kidney-Disease-Prediction-Using-Machine-Learning

* **Abstract:**Due to its lack of symptoms, chronic kidney disease (CKD), a serious worldwide health issue with high rates of morbidity and mortality, is frequently overlooked in its early stages. Machine learning models provide quick and precise diagnostic help, and early detection is crucial to slowing the progression of disease. We used KNN imputation, a technique that mimics actual medical situations, to handle missing values in the CKD dataset from the UCI Machine Learning Repository.

Diagnostic models were constructed using six machine learning algorithms: feedforward neural network, k-nearest neighbor, random forest, support vector machine, logistic regression, and naive Bayes. The best accuracy of 99.75% was attained by random forest.

* **Dataset:** In this project, we have used five datasets merged to one file, they are, Fire accidents, Abuse, Car accidents, Vandalism and Violence from [universe.roboflow.com](url) .This dataset has 13,415 images.
  * The dataset is available here: https://drive.google.com/drive/folders/1YtxUcJATtDcZTabTVsauUyY4iF9dMC0A?usp=sharing
* **Methodology:**  A pre-trained InceptionV3 model which is trained on ImageNet dataset is selected as the base model for transfer learning. Two fully connected layers are added to classify anomalies across five classes fire accidents, abuse, car accidents, vandalism, and Violence. The video feed is processed frame-by-frame using OpenCV. For each frame, the model predicts the class and confidence score. Using twilio we created a notification system which sends notification to the user when anomaly is detected.

* **Results:** In this project we successfully implemented a anomaly detection system using the YOLOv8n model. The uploaded video is analyzed frame by frame and look for anomalies and detects it with higher accuracy. Frames containing detected anomalies were saved, annotated with bounding boxes and class labels. The notification system successfully sends the user notification immediately after detecting the anomalies. The Evaluation Metrics: Precision : 1.00, Recall : 0.80, F1 Score: 0.89, Mean IoU: 0.70.
![Poster_Anomaly_Detection_Krishnarohith_CS668 pptx](https://github.com/user-attachments/assets/2d442c80-13fc-4519-a1bd-03f44e80e791)

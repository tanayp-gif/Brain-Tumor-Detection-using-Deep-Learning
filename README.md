# Brain-Tumor-Detection-using-Deep-Learning

The project titled “Brain Tumor Detection and Classification using Deep Learning and Machine Learning Techniques” focuses on developing an efficient and reliable system for detecting and classifying brain tumors from MRI images. The project integrates multiple approaches, including deep learning-based convolutional neural networks and machine learning techniques such as XGBoost, to improve prediction accuracy and robustness.
About Dataset
Visualizes model predictions on MRI images with correct and misclassified cases.Provides insight into model performance and classification challenges.

<img width="1349" height="694" alt="image" src="https://github.com/user-attachments/assets/cac470b2-42a9-4c6a-8b10-38d91c925923" />

Tumor Type Counts:
pituitary_tumor     827
glioma_tumor        826
meningioma_tumor    822
no_tumor            395
Name: count, dtype: int64

<img width="540" height="393" alt="image" src="https://github.com/user-attachments/assets/6e73a86e-b774-4902-aa8d-af0321d72702" />

This figure presents a class-wise performance analysis of the CNN model by comparing misclassification loss with precision, accuracy, and F1-score. It highlights how the model performs differently across tumor classes such as glioma, meningioma, pituitary, and no tumor. The visualization helps identify challenging classes and provides insight into model strengths and weaknesses.

<img width="1011" height="1511" alt="image" src="https://github.com/user-attachments/assets/7bc049c8-3cfd-42f0-b6e2-22a8090c12c4" />

Implemented in the brain tumor classification notebook, extends the detection task by classifying tumors into specific categories. This model may either use a custom CNN or a transfer learning approach with pre-trained architectures to improve performance.
<img width="989" height="590" alt="image" src="https://github.com/user-attachments/assets/bac3b459-c81c-4d7a-bc5d-2ee611b85157" />

Training PCA+XGBoost with 20% of data...
Accuracy: 0.5330
F1-Score: 0.5016

Training PCA+XGBoost with 40% of data...
Accuracy: 0.5964
F1-Score: 0.5634

Training PCA+XGBoost with 60% of data...
Accuracy: 0.6421
F1-Score: 0.6073

Training PCA+XGBoost with 80% of data...
Accuracy: 0.6980
F1-Score: 0.6581

Training VGG16+XGBoost with 20% of data...
Accuracy: 0.5990
F1-Score: 0.5713

Training VGG16+XGBoost with 40% of data...
Accuracy: 0.6624
F1-Score: 0.6323

Training VGG16+XGBoost with 60% of data...
Accuracy: 0.6929
F1-Score: 0.6527

Training VGG16+XGBoost with 80% of data...
Accuracy: 0.7335
F1-Score: 0.6947

Training Raw+XGBoost with 20% of data...
Accuracy: 0.4670
F1-Score: 0.4290

Training Raw+XGBoost with 40% of data...
Accuracy: 0.5609
F1-Score: 0.5294

Training Raw+XGBoost with 60% of data...
Accuracy: 0.6015
F1-Score: 0.5611

Training Raw+XGBoost with 80% of data...
Accuracy: 0.6447
F1-Score: 0.5949

In conclusion, this project successfully demonstrates the application of deep learning and machine learning techniques for brain tumor detection and classification. The use of CNNs enables effective feature extraction from MRI images, while transfer learning improves performance with limited data



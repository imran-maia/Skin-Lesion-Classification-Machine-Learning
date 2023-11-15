# Skin-Lesion-Classification-Machine-Learning
The MAIA CADx Skin Lesion Classification Challenge using Machine Learning was organised by the consortium of the Erasmus Mundus Joint Master in Medical Imaging and Applications at the University of Girona in Spain.

# Abstract:

Skin lesions pose a significant risk due to their potential to manifest as malignant tumors. Early diagnosis plays a pivotal role in effective treatment and improved patient outcomes. Leveraging computer-aided diagnosis systems can revolutionize this process by enhancing accuracy and speed. This project aimed to develop a robust skin lesion classification model using machine learning. The pipeline encompassed image preprocessing, augmentation, feature extraction, feature engineering, and a machine learning classifier. Employing a mixed dataset comprising HAM10000(ViDIR Group, Medical University of Vienna), the BCN_20000 (Hospital Clínic de Barcelona) and the MSK Dataset (ISBI 2017), the binary classification achieved an impressive accuracy of 0.85, while the multiclass classification yielded a kappa score of 0.74 on the test data. These promising results underscore the potential of machine learning in aiding dermatologists and healthcare professionals in accurate and timely skin lesion diagnoses.

# Dataset:

Binary Class Challenge (Nevus and Others):
Training Data   - 1500
Validation Data - 4000
Testing Data    - 6000

Binary Class Challenge (Melanoma, Basal Cell Carcinomaand, Squamous Cell Carcinoma):
Training Data   - 5000
Validation Data - 2000
Testing Data    - 3000

# Image Pre-processing:

There are multiple preprocessing techniques have been used including hair removal, cropping the black vintage region, and contrast enhancement (gamma correction).

# Features Extraction:

Several features including intensity features (GLCM, LBP), shape features, texture features, colour features, and wavelet features have been extracted for the machine learning classifier.

# Features Engineering:

Feature engineering techniques such as Principal Component Analysis (PCA), K-best feature selection, and Model-Based feature selection have been leveraged to make the model more robust.

# Machine Learning Classifier:

Two different approaches of machine learning classification have been used for example independent classifiers and ensemble method. 

K-Nearest Neighbour, Support Vector Machine, Random Forest, XGBoost, and Extra Trees machine learning classifier have been used independently and also as an ensemble. In the case of the ensemble method, stacking and majority voting (hard voting, soft voting) have been used.

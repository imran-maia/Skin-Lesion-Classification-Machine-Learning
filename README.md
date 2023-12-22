# Skin-Lesion-Classification-Machine-Learning
The MAIA CADx Skin Lesion Classification Challenge using Machine Learning was organised by the consortium of the Erasmus Mundus Joint Master in Medical Imaging and Applications at the University of Girona in Spain. 

# Abstract:

Skin lesions pose a significant risk due to their potential to manifest as malignant tumors. Early diagnosis plays a pivotal role in effective treatment and improved patient outcomes. Leveraging computer-aided diagnosis systems can revolutionize this process by enhancing accuracy and speed. This project aimed to develop a robust skin lesion classification model using machine learning. The pipeline encompassed image preprocessing, augmentation, feature extraction, feature engineering, and a machine learning classifier. Employing a mixed dataset comprising HAM10000(ViDIR Group, Medical University of Vienna), the BCN_20000 (Hospital Clínic de Barcelona) and the MSK Dataset (ISBI 2017), the binary classification achieved an impressive accuracy of 0.85, while the multiclass classification yielded a kappa score of 0.74 on the test data. These promising results underscore the potential of machine learning in aiding dermatologists and healthcare professionals in accurate and timely skin lesion diagnoses.

# Dataset:

**Binary Class Challenge (Nevus and Others):**
<br>Training Data   - 15195
<br>Validation Data - 3796
<br>Testing Data    - 6340

**Multi Class Challenge (Melanoma, Basal Cell Carcinoma, and Squamous Cell Carcinoma):**
<br>Training Data   - 5760
<br>Validation Data - 1270
<br>Testing Data    - 2121

# Image Pre-processing:

There are multiple preprocessing techniques have been used including hair removal, cropping the black vintage region, and contrast enhancement (gamma correction).
<br><br>
![image](https://github.com/imran-maia/Skin-Lesion-Classification-Machine-Learning/assets/122020364/1144ac95-165d-4f8c-adda-6bf5e7bbc934)




# Features Extraction:

Several features including intensity features (GLCM, LBP), shape features, texture features, colour features, and wavelet features have been extracted for the machine learning classifier.

# Features Engineering:

Feature engineering techniques such as Principal Component Analysis (PCA), K-best feature selection, and Model-Based feature selection have been leveraged to make the model more robust.

# Machine Learning Classifier:

Two different approaches of machine learning classification have been used for example independent classifiers and ensemble method. 

K-Nearest Neighbour, Support Vector Machine, Random Forest, XGBoost, and Extra Trees machine learning classifier have been used independently and also as an ensemble. In the case of the ensemble method, stacking and majority voting (hard voting, soft voting) have been used.

**We secured the second position in the binary classification challenge with an accuracy of 0.8590**

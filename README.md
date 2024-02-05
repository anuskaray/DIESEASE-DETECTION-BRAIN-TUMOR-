# DIESEASE-DETECTION-BRAIN-TUMOR-
Tumor detection is an important task in medical diagnosis, and machine learning techniques have been widely used to improve accuracy and efficiency. Here, we focus on four popular machine learning algorithms, logistic regression, support vector machines (SVM), Decision tree and Random Forest Classifier for tumor detection.


#Image and Dataset Description

This paper mainly focus on image segmentation of a MRi Scan of brain and tumor dataset from Github.
The original MRI Scan of the brain “Fig 3.1”. The tumor dataset which has classified 2 stages of tumor M - malignant and B - Begin.There is total 357 begin tumor stage and 212 malignant tumour stage and there is total 539 rows and 31 columns. The dataset also contains the following information- 
Ten real-valued features are computed for each cell nucleus: 
•	radius (mean of distances from center to points on the perimeter) 
•	texture (standard deviation of gray-scale values) 
•	perimeter 
•	area 
•	smoothness (local variation in radius lengths) 
•	compactness (perimeter2 / area — 1.0) 
•	concavity (severity of concave portions of the contour) 
•	concave points (number of concave portions of the contour) 
•	symmetry 
•	fractal dimension (“coastline approximation” — 1)


# Algorithm and Technologies

Four machine learning algorithms are employed: Support Vector Machine (SVM), Decision Tree, Logistic Regression, and Random Forest Classifier along with image segmentation using MRI brain images. These algorithms serve classification and regression tasks. Python, a high-level, interpreted language, is used for programming, and Jupyter Notebook is adopted as an open-source web-based application for interactive code execution and data exploration, allowing for efficient experimentation and collaboration.


# Implementation (MRI SCAN)


We are starting with importing necessary libraries like skimage, skimage. color, matplotlib, pyplot,cv2 and few basic  packages. Before applying filters, the image is pre-processed. This may include resizing, converting to grayscale, or denoising. Now, different filters is applied for image segmentation.  The image processing is continued with more segmentation techniques like Threshold Segmentation and Gaussian Thresholding. Further the value of threshold is increased to get better features of the tumor so that the stage of the tumor is detected. Therefore with the help of different filtering methods the brain tumor is detected. The output images after filtering can be viewed and the classified tumor is detected.



# Implementation(TUMOR DATASET)
The tumor dataset is imported and preprocessed “Fig 3.3” and made suitable for applying the Ml algorithms. From the dataset count plot is generated which gives the diagnosis of the count of Malignant = 212 and Begin = 357 and a Correlation Heatmap is generated which can be used to to find potential relationships between variables and to understand the strength of these relationships.


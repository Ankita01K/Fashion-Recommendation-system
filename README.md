
# **Fashion Recommender: ResNet-50 Transfer Learning & K-Nearest Neighbors**

 ## **Introduction**

**Fashion Recommendation System leverages the prowess of transfer learning utilizing the ResNet-50 architecture along with an optimized K-Nearest Neighbors (KNN) algorithm. 
By extracting features from a vast dataset of over 45,000 images through transfer learning with ResNet-50, the system effectively analyzes image data. 
Implementing a similarity search approach using KNN, the system offers personalized fashion recommendations by identifying the top 5 closest matches to user input. 
This system, with its user-friendly interface and intuitive design, ensures accurate and efficient analysis of image data.**


## **Data Collection:**

**The dataset for this project is sourced from an e-commerce website available on Kaggle** here.

## **Data Pre-processing:**

**TensorFlow's robust set of tools is employed to manipulate data efficiently for training neural networks. The process involves:**

**Load Image**: Images are loaded into the system.

**Convert Image to Array**: Images are converted into arrays suitable for machine learning models.

**Expand Dimensions for Batch Input**: Dimensionality is expanded to facilitate batch processing.

**Align RGB to BGR**: Adjustments are made to align color models.

**Flatten**: Arrays are flattened for further processing.

**Normalization**: Normalization of data enhances model performance.

 ### **Flow chart**

![Screenshot 2024-03-26 050006](https://github.com/Ankita01K/Fashion-Recommendation-system/assets/123232024/0d1b1ee8-dd0c-4a66-9404-f83338650f49)


 # **Model:**

ResNet-50, a 50-layer convolutional neural network, is utilized to reduce computing time and improve results. Key components include:

1-ResNet-50: A deep CNN architecture comprising 48 convolutional layers, one MaxPool layer, and one average pool layer.

2-K-Nearest Neighbors Algorithm: Euclidean distance metric is employed to identify the most similar recommendations.






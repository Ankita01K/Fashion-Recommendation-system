
# **Fashion Recommender: ResNet-50 Transfer Learning & K-Nearest Neighbors**

## **Introduction**

**Fashion Recommendation System leverages the prowess of transfer learning utilizing the ResNet-50 architecture along with an optimized K-Nearest Neighbors (KNN) algorithm. By extracting features from a dataset of over 2906 images through transfer learning with ResNet-50, the system effectively analyzes image data. Implementing a similarity search approach using KNN, the system offers personalized fashion recommendations by identifying the top 5 closest matches to user input. This system, with its user-friendly interface and intuitive design, ensures accurate and efficient analysis of image data**

 ## **Data Collection:**

**The dataset for this project is sourced from an e-commerce website available on Kaggle** [Here](https://www.kaggle.com/datasets/vikashrajluhaniwal/fashion-images).
                                                                                                

 ## **Data Pre-processing:**

+ **TensorFlow's robust set of tools is employed to manipulate data efficiently for training neural networks. The process involves:**

+ **Load Image:**   **Images are loaded into the system.**

+ **Convert Image to Array:**  **Images are converted into arrays suitable for machine learning models.**

+ **Expand Dimensions for Batch Input:**  **Dimensionality is expanded to facilitate batch processing**.

+ **Align RGB to BGR:**  **Adjustments are made to align color models.**

+ **Flatten:**  **Arrays are flattened for further processing**.

+ **Normalization:**  **Normalization of data enhances model performance**.

## **Flow chart**

![Screenshot 2024-03-26 050006](https://github.com/Ankita01K/Fashion-Recommendation-system/assets/123232024/0d1b1ee8-dd0c-4a66-9404-f83338650f49)


## **Model:**

**ResNet stands for Residual Network and is a specific type of convolutional neural network (CNN). ResNet-50 is a 50-layer convolutional neural network (48 convolutional layers, one MaxPool layer, and one average pool layer). Residual neural networks are a type of artificial neural network (ANN) that forms networks by stacking residual blocks.**

+ **RESNET50 is used in order to reduce computing time and achieve better results.**

+ **K-Nearest Neighbors algorithm with Euclidean distance as a metric to pick out most similar recommendations.**



## Deployment

**To deploy this project run**

**Clone the repository:**

```bash
  https://github.com/Ankita01K/Fashion-Recommendation-system.git
```

**Install the required dependencies**

```bash
  pip install -r requirements.txt

```
**Run the Streamlit App**

```bash
  streamlit run main.py
```

![Screenshot 2024-03-25 052933](https://github.com/Ankita01K/Fashion-Recommendation-system/assets/123232024/4aabc6bc-4493-4295-8360-c20e1a8ffa06)



![Screenshot 2024-03-26 053632](https://github.com/Ankita01K/Fashion-Recommendation-system/assets/123232024/6f30186c-3fa8-485b-97ea-02bb8b9fff01)


![Screenshot 2024-03-26 053746](https://github.com/Ankita01K/Fashion-Recommendation-system/assets/123232024/c03b6431-0b17-4a52-877f-808cc0f6ffde)

🍚 Rice Variety Classification using CNN
This project showcases a Convolutional Neural Network (CNN) built with TensorFlow and Keras to classify images of five different varieties of rice. The model effectively learns to distinguish key features of each rice type, achieving an impressive overall accuracy of 98%.

🧠 About Convolutional Neural Networks (CNNs)
CNNs are a specialized type of Artificial Neural Network (ANN) designed to process grid-like data, such as images. Their architecture is inspired by the human visual cortex, making them highly effective for computer vision tasks.

Convolutional Layer: Applies filters (kernels) to the input image to extract spatial features like edges, textures, and shapes.

Pooling Layer: Reduces the spatial dimensions of the feature maps, which decreases computational load and helps in retaining the most dominant features.

Fully Connected Layer: Flattens the features extracted by the convolutional and pooling layers and performs classification based on the learned patterns.

🌾 The Dataset
The model is trained on the Rice Image Dataset, which contains thousands of images distributed across five major rice varieties.

Classes:

Arborio

Basmati

Ipsala

Jasmine

Karacadag

Image Preprocessing:

All images are resized to a uniform dimension of 32
times32 pixels.

Pixel values are normalized to a range of [0,1] for optimal model performance.

Data Split:

The dataset is split into a training set (80%) and a testing set (20%).

📊 Performance and Results
The model was trained for 5 epochs and demonstrated excellent performance on the test set, achieving an overall accuracy of 98%.

The detailed classification report below shows the precision, recall, and F1-score for each rice variety:

### **CNN Classification Report**

| Class      | Precision | Recall | F1-Score |
| :--------- | :-------: | :----: | :------: |
| **Arborio** |   0.99    |  0.97  |   0.98   |
| **Basmati** |   0.97    |  1.00  |   0.98   |
| **Ipsala** |   1.00    |  1.00  |   1.00   |
| **Jasmine** |   0.99    |  0.97  |   0.98   |
| **Karacadag**|   0.97    |  1.00  |   0.98   |
|            |           |        |          |
| **Accuracy** |           |        | **0.98** |
| **Macro Avg**|   0.98    |  0.98  |   0.98   |
| **Weighted Avg**| 0.98    |  0.98  |   0.98   |

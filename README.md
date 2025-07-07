# 🧠 Arabic Handwritten Character Group Classification using ANN
This project focuses on classifying Arabic handwritten characters into groups using an Artificial Neural Network (ANN). The dataset used is the Arabic Handwritten Characters Dataset from Kaggle.

🗂 Dataset Details:

The images are grayscale and resized to 100×100 pixels.

The dataset is divided into train and test directories, with subfolders for each character class.

Labels correspond to groups of Arabic characters based on their position in the alphabet or writing characteristics.

🛠️ Model Architecture:

Built using TensorFlow/Keras

Includes multiple convolutional and dense layers

Regularization and data augmentation techniques (rotation, zoom, shift, shear) are applied to improve generalization

Learning rate is scheduled using exponential decay

📈 Training Pipeline:

Image preprocessing and normalization

Data augmentation with ImageDataGenerator

Dataset split into training and validation sets using train_test_split

Evaluation on both training and test data

🔍 Label Predicted:

The group each Arabic character belongs to, as defined in the dataset folder structure

# ![image](https://github.com/user-attachments/assets/44695e9d-92d9-41e9-9e97-2576f7ee51f9) SureVenir Machine Learning Model

📸 Balinese Souvenirs Recognition Made Easy and Scam-Free!

The Surevenir Machine Learning Model is part of an application designed to help tourists identify and learn about authentic Balinese souvenirs. Using cutting-edge machine learning technology, this model processes images and provides:
- **🏷️ Name of the souvenir**
- **💰 Price range**
- **📖 Detailed description, including recommended places to buy**

## ✨ Introduction
Bali is a paradise filled with unique handmade crafts. However, tourists often face challenges such as being scammed by overpriced or counterfeit souvenirs and finding reliable information on where to buy authentic items. This project aims to:
- Assist tourists in identifying genuine Balinese souvenirs with ease.
- Provide accurate, detailed information, including recommended places to purchase authentic souvenirs.
-  Support local artisans by promoting their genuine products and fostering trust in the market.
🎯 Goal: Improve the shopping experience for tourists while boosting the local economy and protecting cultural heritage.

## 🔍 EDA & Data Preparation
Steps for Exploratory Data Analysis (EDA):
- 🔎 Dataset Inspection: Analyze class distributions and detect outliers.
- 📊 Visualization: Create distribution charts and explore feature relationships.

## ⚙️ Data Processing
Data processing involves preparing and transforming raw data into a format suitable for model training. It ensures data consistency, enhances diversity through augmentation, and optimizes inputs for better model performance.
1. 🔄 Normalization: Rescale pixel values of images to the range `[0, 1]` by dividing them by 255. This is applied to both training and validation datasets.
2. 📈 Data Augmentation: To increase dataset diversity and improve model generalization, several augmentations are applied to the training dataset:
   - Rotation: Randomly rotate images up to 20 degrees.
   - Flipping: Randomly flip images horizontally.
   - Brightness Adjustment: Vary brightness within a range of [0.5, 1.5].
   - Channel Shift: Shift color channels by a range of 50.0.
   - Shearing: Apply shearing transformations up to 0.2.
   - Zooming: Apply zoom transformations within a range of [0.8, 1.2].
   - Translation: Shift images up to 20% of their width and height.
3. 📂 Dataset Splitting: 80% for training and 20% for validation

## 🤖 Machine Learning Model
🛠️ Model Overview:
- Architecture: Convolutional Neural Network (CNN) with Transfer Learning
- Algorithm: MobileNetV2
- Framework: TensorFlow
📊 Training Results:
- Accuracy:
- Loss:
🚀 Steps Taken:
- Model selection and architecture definition.
- Model training with hyperparameter tuning.
- Evaluation using metrics like accuracy, confusion matrix, and classification report.
📌 Tools & Environment:
- 🖥️ IDE: Visual Studio Code (VS Code)
- 🐍 Programming Language: Python
- 📦 Libraries and Frameworks: TensorFlow, Keras, Pandas, Matplotlib, Seaborn, Scikit-learn

## 🚀 Model Deployment
Once the model is trained and ready, we use TensorFlow.js to convert the model into a JavaScript-compatible format.o
 

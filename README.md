🌳🔥 Forest Fire Detection using Deep Learning

📃 Overview

This project aims to detect forest fires using deep learning techniques. A Convolutional Neural Network (CNN) is trained on an image dataset to classify fire-related images.

🌍 Dataset

The dataset used is The Wildfire Dataset, downloaded from Kaggle. It consists of images labeled as fire and non-fire.

💻 Technologies Used

💻 Python

⚛️ TensorFlow/Keras

⚙️ NumPy

🎨 Matplotlib

💎 Kaggle API

🔄 Installation & Setup

🛀 Clone the repository:

git clone <repo-link>
cd Forest_Fire_Detection

✨ Install dependencies:

pip install -r requirements.txt

📂 Download the dataset:

import kagglehub
path = kagglehub.dataset_download("elmadafri/the-wildfire-dataset")

🏆 Train the model:

python train.py

🤖 Model Architecture

The CNN model consists of:

🌐 Convolutional and MaxPooling layers

📊 Flatten and Dense layers

🔒 Dropout for regularization

🖥️ Usage

Run the notebook Forest_Fire_Detection_using_Dl.ipynb to train and evaluate the model.

Deploy the trained model for real-time fire detection.

📊 Results

🎯 The model achieves high accuracy in detecting fire images.

🌄 Visualization of predictions using Matplotlib.

🔄 Future Enhancements

🔄 Improve model accuracy with data augmentation.

🌐 Deploy as a web-based application.

👤 Author

Monali


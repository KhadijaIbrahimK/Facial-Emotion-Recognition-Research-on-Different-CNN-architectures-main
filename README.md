🧠 Project Overview
This study explores the effectiveness of various convolutional neural network (CNN) architectures in detecting human emotions from facial expressions. The goal is to determine which model architecture offers the best balance of accuracy, speed, and generalization across a standardized dataset.

🔧 Technologies Used
Python

NumPy

TensorFlow

Keras

Matplotlib

Seaborn

🖼️ Dataset & Preprocessing
Images resized to 48x48 grayscale for uniform input dimensions.

Converted images to NumPy arrays.

Normalized pixel values to the [0,1] range for faster convergence.

🏗️ Model Architectures Trained
The following deep learning models were implemented and trained:

✅ Basic CNN

🔳 WideResNet

🔺 Pyramidal Net

🧱 VGG16-based Model

🚦 HighwayNet

🌐 DenseNet

📈 Performance Evaluation
Each model was evaluated using:

Accuracy and loss curves

Confusion matrices

Training vs Validation analysis

Visualizations using Matplotlib and Seaborn for interpretability.

📊 Results & Insights
Quantitative Metrics: Tracked training/validation accuracy and loss to identify overfitting or underfitting.

Qualitative Analysis: Visualized predictions vs actual emotions on test samples.

Insights were drawn to identify strengths and weaknesses of each model in recognizing complex emotions.

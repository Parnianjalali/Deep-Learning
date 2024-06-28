# Deep Learning Projects

This repository contains several deep learning projects including Emotion Recognition, Ethereum Price Estimation, and Face Mask Detection.

## Projects

### 1. Emotion Recognition for TFD Dataset
- **Description**: A convolutional neural network (CNN) model to recognize emotions from facial expressions.
- **Dataset**: TFD (Toronto Face Dataset)
- **Model**: Utilizes Conv2D, MaxPooling2D, Dense layers with ReLU and Sigmoid activation functions.
- **Training**: Trained with binary_crossentropy loss and Adam optimizer.

### 2. Ethereum Price Estimation with RNNs
- **Description**: A recurrent neural network (RNN) model to predict Ethereum prices.
- **Data**: Historical data including opening price, closing price, highest price, lowest price, and trading volume.
- **Preprocessing**: Normalized using MinMaxScaler; window size determined for lookback period.
- **Model**: LSTM network with multiple layers and dropout to prevent overfitting.
- **Performance**: Evaluated using Mean Absolute Error (MAE).

### 3. Face Mask Detection Using CNN
- **Description**: A CNN model to detect the presence of face masks in images.
- **Model**: Includes Conv2D, MaxPooling2D, and Dense layers.
- **Training**: Uses binary_crossentropy loss and Adam optimizer.

## Getting Started

### Prerequisites
- Python 3.x
- TensorFlow
- Keras
- Other dependencies as listed in `requirements.txt`

### Installation
Clone the repository:
```bash
git clone https://github.com/Parnianjalali/Deep-Learning.git
cd Deep-Learning

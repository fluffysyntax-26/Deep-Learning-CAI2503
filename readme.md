# Deep Learning (CAI2503)

This repository contains the laboratory sheets, source code, and resources for the course **CAI2503: Deep Learning Lab**. The materials are designed to provide practical experience in building, training, and deploying deep neural networks using Python and frameworks like TensorFlow/Keras or PyTorch.

## Course Overview

The primary goal of this course is to bridge the gap between deep learning theory and practice. The labs are structured as Jupyter Notebooks, progressing from the fundamentals of neural networks (ANNs) to advanced architectures like Convolutional Neural Networks (CNNs), Recurrent Neural Networks (RNNs), and Transfer Learning.

## Repository Structure

The coursework is typically divided into specific Lab Sheets covering key Deep Learning concepts:

| Lab Sheet | Topic | Description |
| :--- | :--- | :--- |
| **Lab 01** | **Introduction to Deep Learning Frameworks** | Setting up the environment; Basics of TensorFlow/Keras or PyTorch; Tensor operations and data manipulation. |
| **Lab 02** | **Artificial Neural Networks (ANN)** | Implementing Perceptrons and Multi-Layer Perceptrons (MLP) for binary and multi-class classification problems (e.g., XOR, Boston Housing). |
| **Lab 03** | **Activation Functions & Optimizers** | Experimenting with different activation functions (ReLU, Sigmoid, Tanh) and optimizers (SGD, Adam, RMSprop) to observe convergence. |
| **Lab 04** | **Convolutional Neural Networks (CNN)** | Building CNNs from scratch for image classification tasks using datasets like MNIST or CIFAR-10. |
| **Lab 05** | **Pooling & Padding** | Understanding the effects of stride, padding (valid/same), and pooling layers (Max/Average) on feature map dimensions. |
| **Lab 06** | **Transfer Learning** | Utilizing pre-trained models (e.g., VGG16, ResNet50, MobileNet) for feature extraction and fine-tuning on custom datasets. |
| **Lab 07** | **Recurrent Neural Networks (RNN)** | Implementing RNNs and LSTMs for sequence data, such as time-series prediction or sentiment analysis. |
| **Lab 08** | **Autoencoders** | Building autoencoders for unsupervised learning tasks like dimensionality reduction or image denoising. |
| **Lab 09** | **Model Evaluation & Tuning** | Techniques for hyperparameter tuning, preventing overfitting (Dropout, Early Stopping), and visualizing training history. |

*(Note: The exact number of labs and specific order may vary based on the specific semester schedule.)*

## 🛠️ Prerequisites & Technology Stack

To run the notebooks in this repository, you need the following software and libraries installed:

* **Python 3.x**
* **Jupyter Notebook** or **Google Colab**

**Required Python Libraries:**
* `tensorflow` / `keras` (or `torch`)
* `numpy`
* `pandas`
* `matplotlib`
* `scikit-learn`
* `seaborn`

## Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/fluffysyntax-26/Deep-Learning-CAI2503.git](https://github.com/fluffysyntax-26/Deep-Learning-CAI2503.git)
    cd Deep-Learning-CAI2503
    ```

2.  **Create a virtual environment (Optional but Recommended):**
    ```bash
    python -m venv dl_env
    # Windows
    dl_env\Scripts\activate
    # macOS/Linux
    source dl_env/bin/activate
    ```

3.  **Install dependencies:**
    ```bash
    pip install tensorflow numpy pandas matplotlib scikit-learn jupyter
    ```

## Usage

1.  Launch Jupyter Notebook from the terminal:
    ```bash
    jupyter notebook
    ```
2.  Navigate to the specific lab you wish to explore (e.g., `LabSheet04.ipynb`).
3.  Execute the cells sequentially to visualize the model building and training process.

**Note for GPU Users:** If you have a compatible NVIDIA GPU or Apple Silicon (M1/M2/M3), ensure you install the appropriate GPU-supported versions of TensorFlow or PyTorch for faster training.
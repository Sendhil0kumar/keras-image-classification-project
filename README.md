# CIFAR-10 Image Classification using a CNN

This project implements a Convolutional Neural Network (CNN) to classify images from the CIFAR-10 dataset. The primary goal is to build, train, and evaluate a deep learning model using TensorFlow and Keras.

---

### Technologies Used
* Python
* TensorFlow / Keras
* NumPy
* Matplotlib

---

### Model Architecture
The CNN architecture consists of the following sequential layers:
* **Conv2D Layer 1** (ReLU) -> **MaxPooling2D Layer 1**
* **Conv2D Layer 2** (ReLU) -> **MaxPooling2D Layer 2**
* **Conv2D Layer 3** (ReLU) -> **MaxPooling2D Layer 3**
* **Flatten Layer**
* **Dense Layer** (ReLU)
* **Output Layer** (Softmax)

---

### Results
The model was trained for 10 epochs and achieved a final test accuracy of **70.19%**.

The training and validation history is shown below:

![Training History Plots](training_history_plots.png)

---

### How to Run
The complete code and analysis are available in the `Your_Notebook_Name.ipynb` file.

*(**Important:** Make sure to change `Your_Notebook_Name.ipynb` in that last line to the actual name of your notebook file!)

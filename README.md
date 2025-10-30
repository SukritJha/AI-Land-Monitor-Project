# 🛰️ AI-Powered Land Use Monitor

This is a deep learning project built for my internship. It uses a Convolutional Neural Network (CNN) to classify satellite images into 10 different land use categories.

This project was built in Google Colab and trained on the EuroSAT dataset.

---

## 🎯 Problem Statement

Monitoring land use changes (like deforestation, farming, or urban sprawl) is a slow and expensive manual process. This project aims to create a fast, accurate, and automated AI solution to classify land use from satellite imagery.

## 💡 Solution

The solution is a CNN model built using TensorFlow and Keras. It uses **Transfer Learning** with the **MobileNetV2** model, which was pre-trained on millions of images. The model was then re-trained on the EuroSAT dataset to learn the specific features of satellite images.

---

## 📊 Key Results

The model achieved a **final test accuracy of 91.63%**.

### Model Performance
(Drag and drop your `model_accuracy_loss.png` graph here! GitHub will upload it for you.)

### Prediction Examples
(Drag and drop your `prediction_grid.png` grid screenshot here!)

The model performs very well, with most errors being understandable (e.g., confusing `Pasture` and `HerbaceousVegetation`).

---

## 🛠️ Technology Used

* **Language:** Python
* **AI Frameworks:** TensorFlow & Keras
* **Core Model:** Convolutional Neural Network (CNN) - MobileNetV2
* **Libraries:** TensorFlow Datasets (for data loading), Matplotlib (for plotting), NumPy
* **Environment:** Google Colab (with T4 GPU)
* **Dataset:** EuroSAT (27,000 images, 10 classes)

---

## 🚀 How to Run

The entire project is contained in the `Land_Use_Monitor.ipynb` notebook file.

1.  Download the `.ipynb` file.
2.  Upload it to [Google Colab](https://colab.research.google.com/).
3.  Ensure the runtime is set to **T4 GPU**.
4.  Click **Runtime > Run all** to execute the code from start to finish.

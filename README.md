# Brain Tumor Classification 🧠

This project uses **Deep Learning (VGG19 Transfer Learning)** to classify MRI brain scans into two categories: **Tumor (Yes)** or **No Tumor**.

## 🚀 Features

* Preprocessing of MRI images
* Transfer learning with VGG19
* Binary classification (`yes` / `no`)
* Visualization of predictions

## 📂 Dataset

Brain MRI images (Tumor / No Tumor).

## ⚙️ Tech Stack

* Python, TensorFlow/Keras
* VGG19 (pretrained on ImageNet)
* NumPy, Matplotlib

## ▶️ Usage

```bash
# Train the model
python brain.ipynb

# Predict on new images
model.predict(img_array)
```

## 📊 Results

* Outputs prediction with label (`yes` / `no`)
* Displays MRI image with predicted class

## 📜 License

Open for educational and research purposes.


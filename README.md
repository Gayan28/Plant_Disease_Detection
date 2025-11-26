# Plant Disease Detection
Computer Vision course work

# 🌱 Plant Disease Detection

A deep learning based system to classify plant leaf diseases using **Convolutional Neural Networks (CNN)** and **MobileNetV2 Transfer Learning**.

## 📊 Dataset
- PlantVillage dataset (~54k images of healthy & diseased leaves)
- Train/Val/Test split: 70/15/15
- Preprocessing: resize (224x224), normalization, augmentation

## 🧠 Models
- **Custom CNN** – baseline model
- **MobileNetV2** – transfer learning, best performance

## 🎯 Results
| Model        | Accuracy | Precision | Recall | F1-score |
|--------------|----------|-----------|--------|----------|
| CNN          | 0.XX     | 0.XX      | 0.XX   | 0.XX     |
| MobileNetV2  | 0.XX     | 0.XX      | 0.XX   | 0.XX     |

## 💻 Application
- Built with **Streamlit**
- Upload plant leaf image → get disease prediction + confidence
- Shows **Top-3 predictions** with progress bars

## 🚀 Run Locally
```bash
pip install -r requirements.txt
streamlit run app.py

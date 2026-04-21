# 🛡️ DeepFake Detection on Edge Devices

### 📖 Overview
This research project focuses on building and optimizing a lightweight, efficient DeepFake detection model specifically designed to run on **Edge Devices**. 

In the context of modern AI applications (like eKYC or secure authentication), running models on the edge reduces server latency, minimizes bandwidth costs, and—most importantly—protects user privacy by processing face data locally.

### 🧠 Model Architecture & Methodology
- **Dataset:** Trained and evaluated using the large-scale **Celeb-DF (V2)** dataset.
- **Models Explored:** We analyzed and integrated various lightweight architectures suitable for mobile/edge environments, including:
  - **MobileNet** (for efficient feature extraction)
  - **MobileViT** (combining CNN and Vision Transformers)
  - **LSTM** (for temporal sequence analysis in videos)

### 📊 Performance & Results
* **Accuracy:** Reached `[over 60% and continuing update]` on the test set.
### 🚀 Future Work (Product Perspective)
If developed into a real-world product feature, this core technology could be integrated directly into financial apps to prevent spoofing attacks during user login or transaction verification.

# DiaCure: Diabetic Retinopathy Prediction using Optimized Neural Network

DiaCure is a deep learning-based project that detects diabetic retinopathy (DR) through retinal images using an optimized neural network. The aim is to assist in early detection of diabetes and related eye conditions to allow timely medical intervention.

---

## 👨‍⚕️ Problem Statement

Diabetic retinopathy is a major cause of vision loss among diabetic patients. It affects the retina and can lead to:

- **Diabetic Macular Edema (DME)**: Leakage into the macula causing blurry vision.
- **Neovascular Glaucoma**: Abnormal blood vessel growth blocking fluid drainage in the eye.

Early detection is key to effective treatment.

---

## 🎯 Objectives

- Collect a diverse dataset of retinal images (diabetic & non-diabetic).
- Design an efficient CNN architecture using ResNet18.
- Apply nature-inspired algorithms for performance optimization.
- Train for maximum accuracy and minimum loss.
- Evaluate performance with metrics like accuracy, precision, recall, and F1-score.
- Develop a user-friendly interface for medical professionals.

---

## 🛠️ Tools & Technologies

- **Languages**: Python
- **Frameworks**: Fastai, Flask, React (for deployment)
- **Libraries**: Pandas, NumPy, Matplotlib, OS
- **IDE**: Jupyter Notebook, Kaggle
- **Frontend**: HTML, CSS, Bootstrap

---

## 🗂️ Dataset

1. `diabetic-retinopathy-224x224-gaussian-filtered`
2. `APTOS 2019 Blindness Detection`

---

## 🧠 Model Architecture

- **Model Used**: ResNet18
- **Tasks**: Image classification for detection of DR
- **Optimization**: Nature-inspired algorithms for parameter tuning
- **Evaluation Metrics**: Accuracy, Precision, Recall, F1 Score, Sensitivity, Specificity

---

## 🔄 Project Workflow

### 1. Data Collection & Preprocessing
- Gather labeled retinal images
- Apply Gaussian filtering
- Standardize image dimensions (224x224)

### 2. Feature Extraction
- Extract key features indicative of DR
- Enhance image features for better learning

### 3. Model Development
- Design CNN architecture
- Use appropriate activation, loss, and optimizer

### 4. Training & Validation
- Train on train/validation split
- Fine-tune for high performance

### 5. Interpretability
- Ensure predictions are interpretable for medical use
- Visual aids and explainability integrated

### 6. Testing
- Rigorous real-world testing
- User experience evaluation

### 7. Integration & Deployment
- Flask backend + React frontend
- Compliant with healthcare ethics and standards

---

## ✅ Results

- 🎯 High accuracy in detecting diabetic retinopathy
- 🧠 Model provides confidence score for predictions
- ⚡ Performs efficiently in real-time conditions

---

## 👥 Team

- Abhishek V K
- Suhas S
- Sai Kruthik Reddy N S
- Sanchit Vijay

---

## 📌 Future Scope

- Expand to other eye diseases
- Improve interpretability with visual saliency maps
- Real-time deployment in telemedicine platforms

---

## 📷 Sample Output(with confidence score)

### ✅ No Diabetic Retinopathy
![No DR](./images/no_diabetic_retinopathy.png)

### 🚨 Diabetic Retinopathy Detected
![DR Detected](./images/diabetic_retinopathy_detected.png)

### 🚨 Diabetic Retinopathy Detected with severity
![DR Detected](./images/diabetic_retinopathy_detected.png)
---

## 📬 Contact

For more information or collaboration, feel free to reach out to the contributors.

---


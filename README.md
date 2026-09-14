### Hey there! 👋 I'm Dimple Vincia Selet RR 🚀

<img src="https://komarev.com/ghpvc/?username=dimplevincia&color=brightgreen&style=flat-square" alt="Profile Views" />

👩‍💻 An aspiring **Data Scientist & Machine Learning Engineer** who loves transforming raw data into intelligent, production-ready solutions and interactive web applications. 🌟

---

### 🛠️ Technical Arsenal & Skills
* **Languages:** Python 🐍, SQL 📊
* **Machine Learning & AI:** Scikit-Learn 🤖, XGBoost ⚡, Pandas 🐼, NumPy 🔢, SHAP (Explainable AI) 🔍
* **Web & MLOps Deployment:** Streamlit 🎈, Git 🌲, GitHub 🐙, Streamlit Cloud ☁️
* **Core Focus:** Predictive Modeling 📈, Data Preprocessing 🧹, Model Interpretability 💡

---

### 🚀 Featured Projects

#### 🤖 Machine Learning & XAI
* **[Customer Churn Predictor & Dashboard](https://github.com/dimplevincia/customer-churn-predictor)** 📉
  * **Tech Stack:** Python 🐍 | XGBoost ⚡ | SHAP 🔍 | Streamlit 🎈
  * **Highlights:** End-to-end churn prediction pipeline with local SHAP waterfall plots for deep model explainability.
  * **Demo:** [Live Web App 🌐](https://customer-churn-predictor-lufzdeaxngm5ganldmyqft.streamlit.app)

#### 📊 Data Analytics & Visualization
* **[Netflix Content Analysis Dashboard](https://github.com/dimplevincia/Netflix-Content-Analysis-Dashboard)** 🎬
  * **Tech Stack:** Python 🐍 | Pandas 🐼 | Plotly 📊 | Streamlit 🎈
  * **Highlights:** Exploratory Data Analysis (EDA) uncovering catalog expansion trends, genre distribution, and rating patterns across Netflix titles.
  * **Demo:** [Live Web App 🌐](https://netflix-content-analysis-dashboard-2k3u9zyij79jek4f23fgzu.streamlit.app)
---

### 📈 GitHub Analytics & Stats
<p align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=dimplevincia&show_icons=true&theme=radical&hide_border=true" height="160" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=dimplevincia&layout=compact&theme=radical&hide_border=true" height="160" />
</p>
# 🩻 Medical Diagnostic Vision System (Chest X-Ray Classifier + Grad-CAM)

An end-to-end deep learning diagnostic web application built with **PyTorch** and **Streamlit**. The system classifies chest X-ray images into Normal vs. Pneumonia and generates **Grad-CAM (Gradient-weighted Class Activation Mapping)** heatmaps to provide visual explainability for clinical decision support.

## 🚀 Live Demo
- **Live App**: [Streamlit Cloud Link](YOUR_STREAMLIT_APP_URL_HERE)

## 🛠️ Tech Stack & Architecture
- **Framework**: PyTorch & Torchvision
- **Model**: MobileNetV2 (Transfer Learning with custom classifier head)
- **Explainable AI**: Grad-CAM (Targeting final convolutional features)
- **Web Interface**: Streamlit
- **Image Processing**: OpenCV & Pillow

## 📂 Project Structure
```text
medical-vision-classifier/
├── model/
│   └── mobilenet_model.pth    # Fine-tuned model weights
├── utils/
│   └── grad_cam.py            # Grad-CAM heatmap generator
├── app.py                     # Streamlit frontend & inference pipeline
├── train.py                   # Model architecture & weight extraction
├── requirements.txt           # Environment dependencies
└── README.md

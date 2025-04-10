# 🧠 AI Skin Analyzer Website

## Overview

The **AI Skin Analyzer** is an intelligent web application designed to assist users in analyzing skin conditions using AI-powered image classification. By leveraging advanced machine learning techniques, the system can detect and classify various skin diseases through real-time camera capture or uploaded images.

This tool is particularly valuable for preliminary screening and educational purposes, providing insights into potential skin abnormalities. **It is not a replacement for professional medical advice or diagnosis.**

## 🧬 Supported Skin Disease Classes

The AI model is trained to detect and classify the following seven types of skin lesions:

1. **Actinic Keratoses and Intraepithelial Carcinoma**
2. **Basal Cell Carcinoma**
3. **Benign Keratosis-like Lesions**
4. **Dermatofibroma**
5. **Melanoma**
6. **Melanocytic Nevi**
7. **Vascular Lesions**

## 🔧 Features

- 📸 **Real-time camera capture** for skin lesion detection  
- 🖼️ **Image upload** option for flexible analysis  
- 🤖 **Deep learning-based classifier** for accurate predictions  
- 🗂️ Detailed display of prediction results and confidence levels  
- 💬 **Integrated chatbot** for skin health-related queries  
- 🖥️ Clean, responsive, and user-friendly interface  
- 📊 Dashboard view to visualize analysis results

## 🚀 Technologies Used

- **Frontend**: HTML, CSS, JavaScript, React.js (optional)
- **Backend**: Flask / FastAPI (depending on your stack)
- **Machine Learning**: TensorFlow / PyTorch
- **Model Hosting**: Google Colab (for model inference via API)
- **UI Enhancements**: Tailwind CSS, Chart.js, or Shadcn UI

## 📁 Folder Structure

```
ai-skin-analyzer/
├── static/
├── templates/
├── app.py
├── model/
│   └── skin_disease_model.h5
├── README.md
└── requirements.txt
```

## ⚙️ Installation

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/ai-skin-analyzer.git
cd ai-skin-analyzer
```

2. **Install dependencies**
```bash
pip install -r requirements.txt
```

3. **Run the app**
```bash
python app.py
```

4. **Visit**
Open your browser and go to `http://localhost:5000`

## ⚠️ Disclaimer

This tool is meant for **educational and preliminary assessment** purposes only. It does not provide a medical diagnosis. For any concerns or symptoms, consult with a certified dermatologist or medical professional.

---

# 💵 Fake Currency Detection Using Deep Learning

A Deep Learning-based **Fake Currency Detection System** that analyzes currency images and predicts whether the given note is **Genuine or Fake**.

## 🌐 Live Demo

🚀 **Live Server:** https://vdw6sc-jfbx91tah-arcadawebapps8.vercel.app/

> Try the live demo to test the currency detection system.

---

## 📌 Project Overview

Counterfeit currency is a major problem that can affect individuals, businesses, and financial institutions. Manually identifying fake currency can be difficult, especially when dealing with large numbers of notes.

This project uses **Deep Learning and Computer Vision** to analyze currency images and identify whether a currency note is likely to be **genuine or counterfeit**.

The system provides an easy-to-use web interface where users can upload a currency image and receive a prediction.

---

## 🎯 Objectives

* Detect potentially counterfeit currency notes.
* Analyze visual features of currency images.
* Use Deep Learning for automated classification.
* Reduce the effort required for manual verification.
* Provide a simple web-based detection system.
* Demonstrate the practical use of AI in financial security.

---

## 🧠 Technologies Used

* **Python**
* **Deep Learning**
* **Computer Vision**
* **CNN**
* **TensorFlow / Keras**
* **OpenCV**
* **HTML**
* **CSS**
* **JavaScript**
* **Vercel**

---

## ⚙️ System Workflow

```text
Currency Image
      ↓
Image Upload
      ↓
Image Preprocessing
      ↓
Feature Extraction
      ↓
Deep Learning Model
      ↓
Currency Classification
      ↓
Genuine / Fake
```

---

## ✨ Key Features

### 💵 Currency Image Analysis

Allows users to provide an image of a currency note for analysis.

### 🧠 Deep Learning Classification

Uses a trained Deep Learning model to classify the currency image.

### 🔍 Automated Detection

Provides an automated approach to identifying potentially counterfeit notes.

### 🌐 Web-Based Application

The system can be accessed directly through a web browser.

### ⚡ Simple Interface

Designed with a straightforward interface for easy testing and demonstration.

---

## 🏗️ System Architecture

```text
                ┌─────────────────────┐
                │   Currency Image    │
                └──────────┬──────────┘
                           ↓
                ┌─────────────────────┐
                │ Image Preprocessing │
                └──────────┬──────────┘
                           ↓
                ┌─────────────────────┐
                │ Feature Extraction  │
                └──────────┬──────────┘
                           ↓
                ┌─────────────────────┐
                │ Deep Learning Model │
                │        (CNN)        │
                └──────────┬──────────┘
                           ↓
                ┌─────────────────────┐
                │    Classification   │
                └──────────┬──────────┘
                           ↓
                    ┌──────┴──────┐
                    ↓             ↓
                Genuine         Fake
```

---

## 📂 Project Structure

```text
Fake-Currency-Detection/
│
├── dataset/
│   ├── genuine/
│   └── fake/
│
├── model/
│   └── currency_model.h5
│
├── static/
│   ├── css/
│   └── js/
│
├── templates/
│   └── index.html
│
├── app.py
├── requirements.txt
└── README.md
```

---

## 💻 How to Run Locally

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/fake-currency-detection.git
```

### 2. Navigate to the Project

```bash
cd fake-currency-detection
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Application

```bash
python app.py
```

Then open the local server in your browser.

---

## 🌍 Live Application

🚀 **Try the Fake Currency Detection System:**

https://vdw6sc-jfbx91tah-arcadawebapps8.vercel.app/

---

## 📊 Applications

This project can be useful for:

* 🏦 Banking and financial institutions
* 🛒 Retail businesses
* 💰 Cash handling environments
* 🏪 Shops and supermarkets
* 🎓 Educational AI projects
* 🔬 Computer Vision research

---

## 🔮 Future Enhancements

* Support for multiple currency denominations.
* Detection of different currencies.
* Real-time camera-based detection.
* Improved accuracy using transfer learning.
* Mobile application integration.
* Currency security-feature verification.
* Integration with POS and banking systems.
* Larger and more diverse datasets.

---

## 👨‍💻 Author

**Dhanush Reddy**

---

## ⭐ Support

If you find this project useful, consider giving the repository a ⭐ on GitHub.

### ⚠️ Disclaimer

This project is intended for **educational and research purposes**. Predictions should not be treated as definitive proof that a banknote is counterfeit. Official currency-authentication procedures should be used for real-world verification.

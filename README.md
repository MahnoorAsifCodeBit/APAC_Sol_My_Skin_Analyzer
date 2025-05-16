# 💆‍♀️ My Skin Analyzer

**My Skin Analyzer** is an AI-powered skincare assistant designed especially for women. It helps users detect their skin type through a selfie and provides personalized skincare product recommendations using Google Gemini APIs. The platform also includes a chatbot for skincare queries based on individual concerns like acne, dryness, or dark spots.

---

## 📌 Features

- 📷 Upload a selfie to detect your skin type (oily, dry, sensitive, combination)
- 💡 Get personalized product suggestions (serums, creams, moisturizers)
- 💬 Chatbot support for skincare-related questions
- 🔍 Select specific concerns: acne, hydration, wrinkles, dark spots
- 🧾 Clean, minimal UI built with Streamlit

---

## 🧠 Technologies Used

- Gemini 1.5 Vision API  
- Gemini 1.5 Pro API  
- Streamlit (Python)  
- Google Cloud Platform  
- Firebase

---

## 🌍 SDG Goal Addressed

**Goal 3: Good Health and Well-being**  
Helps women make informed skincare choices and reduce misuse of harmful products, contributing to healthier lifestyles.

---

## 🚀 How It Works

1. User uploads a selfie
2. Gemini Vision API detects the skin type
3. User selects a main skin concern
4. AI generates skincare recommendations
5. User can chat with the AI assistant for more guidance

---

## 🖼️ Screenshots (Add yours here)

| Upload Selfie | Chatbot |
|---------------|---------|
| *image 1*     | *image 2* |

---

## 🛠️ Installation

```bash
pip install streamlit google-generativeai Pillow
streamlit run app.py

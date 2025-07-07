# 🌾 AI Farmer Assistant

A multilingual, voice-enabled, AI-powered assistant for farmers—designed and developed by **Florence C Tungoe (Kiki27tungs)** to empower agriculture with smart technology. This project integrates computer vision, natural language processing, and offline capabilities to support farmers with real-time crop diagnostics, market insights, and planting guidance.

## 🚜 Features at a Glance

- 🧠 **Leaf Image Diagnosis**  
  Detects crop issues like insect damage, fungal spots, and leaf burn using deep learning (TensorFlow/Keras).

- 🌦️ **Context-Aware Advice**  
  Provides dynamic solutions and watering tips based on weather and soil input.

- 🌐 **Multilingual Support + Voice Output**  
  Translates diagnosis into multiple languages (currently English & Hindi) with audio playback using `gTTS`.

- 🧾 **Downloadable CSV Reports**  
  Farmers can save their diagnosis and advice summaries for recordkeeping.

- 🎨 **Styled Streamlit Interface**  
  Custom CSS creates a user-friendly, visually aesthetic dashboard with sidebar navigation.

- 📆 **Crop Planting & Harvest Calendar**  
  Interactive Plotly timelines for major crops like wheat, rice, maize, cotton, and sugarcane.

- 📊 **Crop Insights Dashboard**  
  Matplotlib-based analytics for fertilizer use, profit per acre, and production stats.

---

## 🔧 Tech Stack

| Area                | Tools/Frameworks                                     |
|---------------------|------------------------------------------------------|
| **Frontend/UI**     | Streamlit, Plotly, Matplotlib, PIL, CSS Styling      |
| **Modeling**        | TensorFlow/Keras (plant_disease_classifier.h5)       |
| **Language/NLP**    | Google Translate API (`googletrans`), gTTS           |
| **Data Handling**   | Pandas, NumPy, Base64 encoding                       |
| **Voice & Translation** | `gTTS`, `googletrans`, TTS playback using `st.audio()` |
| **Deployment Ready**| Designed for low-bandwidth/offline environments      |

---

## 🗺️ Navigation Menu

- 🌱 **Welcome Page**: App overview & mission
- 🤖 **AI Assistant**: Upload leaf images, get diagnosis, multilingual output
- 📆 **Crop Calendar**: Seasonal planting/harvest guide
- 📊 **Crop Insights**: Analytics for yield, water, fertilizer, profit

---

## 🌍 Vision & Impact

The AI Farmer Assistant is a grassroots solution aimed at:

- 🔸 Empowering **women farmers**
- 🔸 Making **AI accessible** in rural areas
- 🔸 Supporting farming decisions with **data-driven insights**
- 🔸 Reducing crop loss through **early disease detection**
- 🔸 Encouraging **sustainable farming** via CO₂ and water logic (in pipeline)

---

## 🚧 What's Next

- 🌾 Add disease comparison gallery (healthy vs affected leaves)
- 🔊 Expand multilingual + offline NLP chatbot interface
- 🌐 Add CO₂ estimator based on transport/fuel
- 📱 Optimize layout for mobile deployment

---

## 👩‍💻 Developed By

**Florence C Tungoe**  
AI Developer | Climate Tech Enthusiast | Dashboard Designer  
🎓 NSTI(W) Kolkata | AIPA Program  
🌐 [GitHub](https://github.com/Kiki27tungs)

> “Farming with knowledge is farming with power.”  
> – AI Farmer Assistant

---

🛠️ Want to contribute or test?  
Clone this repo, run `streamlit run app.py`, and join the farming tech revolution!

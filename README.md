# 🚨 LLM-Assisted Disaster Management Chatbot (RAG)

## 📌 Overview

This project presents an **AI-powered Disaster Management Chatbot** built using **Retrieval-Augmented Generation (RAG)**. It is designed to provide **accurate, reliable, and real-time disaster-related guidance** during emergency situations such as floods, earthquakes, cyclones, and heatwaves.

The system combines **information retrieval from trusted sources** with **Large Language Model (LLM) based response generation**, ensuring that users receive **fact-based and actionable information** instead of potentially misleading outputs.

---

## 🎯 Problem Statement

In emergency situations, people often rely on multiple sources like government websites, news platforms, and weather reports. This process is:

* Time-consuming
* Confusing
* Prone to misinformation

Traditional AI systems may also generate **hallucinated or incorrect responses**, which can be dangerous in critical scenarios.

---

## 💡 Solution

This project introduces a **RAG-based chatbot system** that:

* Retrieves relevant disaster-related information from trusted sources
* Generates structured and easy-to-understand responses
* Verifies the accuracy of generated outputs
* Provides real-time alerts using weather data

---

## ⚙️ Key Features

* 🔍 **Hybrid Retrieval System** (Dense + Keyword-based search)
* 🤖 **LLM-Based Response Generation**
* ✅ **Knowledge-Constrained Generation (Reduced Hallucination)**
* 🌦️ **Real-Time Weather Monitoring (API Integration)**
* 🗣️ **Voice Assistant Support**
* 🌐 **Multilingual Interaction (English & Hindi)**
* 🔐 **Role-Based Access Control (Admin & User)**
* 📊 **Performance Metrics (Accuracy, Relevance, Response Time)**

---

## 🏗️ System Architecture

```
User Query → Hybrid Retrieval → Context Processing → LLM Generation 
→ Verification → Evaluation → Final Response
```

---

## 🛠️ Technologies Used

* **Programming Language:** Python
* **Backend:** FastAPI / Flask
* **Frontend:** Streamlit / Web Interface
* **LLM Integration:** Google Gemini / OpenAI API
* **Vector Database:** FAISS / ChromaDB
* **Libraries:**

  * LangChain
  * Pandas, NumPy
  * Hugging Face Transformers
* **APIs:** OpenWeather API

---

## 📂 Project Structure

```
├── data/                  # Documents and datasets
├── config/                # Configuration files
├── document_processor/    # Document loading & preprocessing
├── vector_store/          # Embeddings and retrieval
├── llm_module/            # LLM integration
├── api/                   # Backend APIs
├── frontend/              # UI interface
├── main.py                # Entry point
├── requirements.txt       # Dependencies
└── README.md              # Project documentation
```

---

## 🚀 Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### 2️⃣ Create Virtual Environment

```bash
python -m venv venv
source venv/bin/activate   # For Linux/Mac
venv\Scripts\activate      # For Windows
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Set Environment Variables

Create a `.env` file and add:

```
GOOGLE_API_KEY=your_api_key
OPENWEATHER_API_KEY=your_api_key
```

### 5️⃣ Run the Application

```bash
python main.py
```

---

## 📊 Evaluation Metrics

The system performance is evaluated using:

* ✅ Response Accuracy
* ✅ Information Relevance
* ✅ Response Time
* ✅ Reduction in Misinformation

---

## 🔮 Future Enhancements

* Integration with more real-time data sources
* Support for additional languages
* Mobile application deployment
* Advanced alert and notification system
* Improved verification mechanisms

---

## 📜 License

This project is developed for academic purposes and can be extended for real-world applications.

---

## ⭐ Acknowledgement

We would like to thank our project guide and institution for their continuous support and guidance throughout the development of this project.

---

## 💬 Contact

For any queries or collaboration:

* 📧 Email: karthik70757@gmail.com
* 🔗 GitHub: https://github.com/Karthik-27-pixel

---

⭐ *If you found this project useful, consider giving it a star on GitHub!*

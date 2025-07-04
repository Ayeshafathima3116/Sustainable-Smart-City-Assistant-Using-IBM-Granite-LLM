# Sustainable-Smart-City-Assistant-Using-IBM-Granite-LLM

# 🌱 Sustainable Smart City Assistant

An AI-powered assistant designed to help municipalities and citizens manage urban sustainability using IBM Watsonx Granite LLM and Google Gemini. Built with FastAPI, Streamlit, and ML tools for forecasting and anomaly detection.

---

## 🚀 Features

### 🧠 AI Modules (Gemini & Watsonx)
- **Summarization**: Upload policy documents and get concise summaries.
- **Chat Assistant**: Ask sustainability-related questions, get smart city solutions.
- **Eco Tips**: Receive actionable eco-friendly tips based on topics like plastic or solar.

### 📊 Data Intelligence
- **KPI Forecasting**: Upload `.csv` with historical data and predict future trends.
- **Anomaly Detection**: Highlight unusual spikes in KPIs (like electricity or water).

### 📢 Civic Engagement
- **Citizen Feedback**: Submit reports about urban issues (water leaks, road damage).

---

## 🖼️ Project Architecture

smart_city_assistant/
├── backend/
│ ├── main.py # FastAPI entry point
│ ├── routes/ # API route modules
│ ├── services/ # Gemini + ML utility functions
│ ├── models/ # Pydantic schemas
│ └── utils/
├── frontend/
│ └── app.py # Streamlit UI
├── .env # API keys (not committed)
├── requirements.txt
└── README.md

yaml
Copy code

---

## 📸 Screenshots

| Summarization | Forecast | Tips |
|---------------|----------|------|
| ![Summary](https://github.com/Ayeshafathima3116/smart_city_assistant/blob/main/screenshots/summarize.png) | ![Forecast](https://github.com/Ayeshafathima3116/smart_city_assistant/blob/main/screenshots/forecast.png) | ![Tips](https://github.com/Ayeshafathima3116/smart_city_assistant/blob/main/screenshots/tips.png) |

## 🎥 Demo Video

▶️ [![Demo Video](https://github.com/Ayeshafathima3116/smart_city_assistant/blob/main/screenshots/demo.png)](https://drive.google.com/file/d/1u453N7XaYV_FV89H-ollSnzUNxIVnzgy/view)

---

## ⚙️ Installation

1. **Clone the repository**
```bash
git clone https://github.com/Ayeshafathima3116/smart_city_assistant.git
cd smart_city_assistant
Create a virtual environment

bash
Copy code
python -m venv venv
venv\Scripts\activate   # Windows
Install dependencies

bash
Copy code
pip install -r requirements.txt
Add your API keys to .env

ini
Copy code
GOOGLE_API_KEY=your_gemini_key
WATSONX_API_KEY=your_ibm_key
🧪 Run the Project
🟢 Run Backend
bash
Copy code
cd backend
uvicorn main:app --reload
Test API at: http://localhost:8000/docs

🎨 Run Frontend (Streamlit)
bash
Copy code
cd frontend
streamlit run app.py
Open: http://localhost:8501

🧠 Built With
FastAPI

Streamlit

Google Gemini (via google-generativeai)

IBM Watsonx Granite LLM

Pandas / scikit-learn

Pinecone (optional module for semantic search)

🤝 Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you’d like to change.

📜 License
MIT License — use it freely, just give credit.

🙋 Author
PATHAN AYESHA FATHIMA
🎓 SVR Engineering College
🆔 Roll Number: 22am1a3116
👥 Team ID: LTVIP2025TMID37001
📧 Email: 22am1a3116@svrec.ac.in
📞 Contact: 8688523832
🔗 GitHub: @Ayeshafathima3116


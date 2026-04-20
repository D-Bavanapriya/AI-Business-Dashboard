# 🚀 AI-Business-Dashboard
AI-powered business dashboard built with Streamlit, Pandas, and OpenAI. Visualizes sales, profit, and leads with interactive charts and enables natural language queries to generate insights from data.

# 📊 Features
- Sales, Profit & Leads visualization
- KPI metrics dashboard
- AI-powered question answering
- Real-time data simulation
- Clean and responsive UI
# 🛠️ Tech Stack
* Frontend/UI: Streamlit
* Data: Pandas, NumPy
* Visualization: Plotly
* AI: OpenAI
# 📂 Project Structure
yt_app/
│── app.py
│── requirements.txt
│── .streamlit/
│     └── secrets.toml
# ⚙️ Setup & Installation
Clone the repository
git clone <your-repo-link>
cd yt_app
Create virtual environment
python -m venv .venv
.venv\Scripts\activate
Install dependencies
pip install -r requirements.txt
Add API key
Create .streamlit/secrets.toml
OPENAI_API_KEY = "your_api_key_here"
Run the app
streamlit run app.py

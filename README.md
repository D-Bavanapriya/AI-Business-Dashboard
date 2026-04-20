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
1. Clone the repository
git clone <your-repo-link>
cd yt_app
2. Create virtual environment
python -m venv .venv
.venv\Scripts\activate
3. Install dependencies
pip install -r requirements.txt
4. Add API key
Create .streamlit/secrets.toml
OPENAI_API_KEY = "your_api_key_here"
5. Run the app
streamlit run app.py

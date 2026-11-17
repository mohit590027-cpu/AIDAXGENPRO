AI DAX Generator 🚀

Project Overview

AI DAX Generator is an AI-powered application that helps users generate DAX formulas using natural language business questions.

The application simplifies DAX formula creation and helps Power BI users understand and validate generated formulas.

🚀 Live Application

[Click Here to Open AI DAX Generator](https://mohit590027-cpu-aidaxgenpro-app-ib9far.streamlit.app/)

Features

Generate DAX: Generate DAX formulas from business questions.

Download DAX: Download generated DAX formulas.

Explanation: Understand the generated DAX formulas.

Validation: Validate generated DAX formulas.

Technologies Used

Python

Streamlit

Google Gemini API

DAX

Pandas

Project Structure

app.py – Main Streamlit application

gemini_service.py – Gemini API integration

geminimodels.py – Gemini model configuration

powerbi_schema.txt – Power BI schema information

requirements.txt – Project dependencies

.gitignore – Files excluded from GitHub

Installation and Setup

1. Clone the repository

git clone https://github.com/mohit590027-cpu/AIDAXGENPRO.git

2. Open the project folder

cd AIDAXGENPRO

3. Create a virtual environment

py -m venv .venv

4. Activate the environment

.venv\Scripts\activate

5. Install dependencies

pip install -r requirements.txt

6. Configure Gemini API Key

Create a .env file and add:

GEMINI_API_KEY=your_api_key

7. Run the application

streamlit run app.py

GitHub Repository

[AI DAX Generator – GitHub](https://github.com/mohit590027-cpu/AIDAXGENPRO)

Author

Mohit Sharma

Aspiring Data Analyst | Python | SQL | Excel | Power BI

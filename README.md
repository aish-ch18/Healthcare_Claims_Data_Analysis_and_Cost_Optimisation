# Healthcare Insurance Claims Analysis & Fraud Detection App

An end-to-end Streamlit-based application to analyze healthcare claims data, detect fraud using machine learning, visualize cost centers, generate automated PDF reports, and provide secure user login and registration.

## Features

- Exploratory Data Analysis (EDA) on insurance claims
- Interactive visualizations (bar, pie, line charts)
- Fraud prediction using trained ML model
- Downloadable PDF report generation
- User login and registration system (CSV-based)
- Dark/Light mode toggle
- Navigation tabs for modular navigation
- Lottie animations (optional, fallback shown without subscription)

## Tech Stack

- **Frontend:** Streamlit
- **Backend & ML:** Python, Pandas, Scikit-learn
- **Visualization:** Plotly, Matplotlib, Seaborn
- **Authentication:** File-based (CSV)
- **PDF Reporting:** FPDF
- **UI Enhancements:** Lottie animations, Streamlit themes

## Project Structure
├── streamlit_app.py # Main application script
├── insurance.csv # Claims dataset
├── users.csv # User credentials (CSV)
├── fraud_model.pkl # Trained ML model
├── pdf_reports/ # Generated reports folder
├── assets/ # Lottie animation files (optional)
└── README.md


##  Installation

```bash
git clone https://github.com/yourusername/healthcare-claims-fraud-detection.git
cd healthcare-claims-fraud-detection

# (Optional) Create a virtual environment
python -m venv venv
source venv/bin/activate  # macOS/Linux
venv\Scripts\activate     # Windows

# Install dependencies
pip install -r requirements.txt



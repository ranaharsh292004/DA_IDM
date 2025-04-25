# Consumer Behavior Analysis – Streamlit App

This project is a Streamlit web application that analyzes consumer behavior data for a new beverage product launch. It provides interactive visualizations to explore survey responses collected from multiple cities.

## 🔍 Features

- Upload and preview three key datasets: cities, respondents, and survey responses
- Explore trends in consumer awareness and satisfaction by city
- Dynamic bar charts generated using matplotlib
- Simple, user-friendly UI powered by Streamlit

## 📁 Project Structure

```
├── app.py               # Main Streamlit application
├── requirements.txt     # Python dependencies
└── README.md            # Project documentation
```

## 🛠️ Requirements

Ensure you have Python 3.8 or above installed.

Install required libraries using pip:

```bash
pip install -r requirements.txt
```

## 🚀 How to Run Locally

Clone the repository and run the Streamlit app:

```bash
git clone https://github.com/yourusername/consumer-survey-streamlit.git
cd consumer-survey-streamlit
streamlit run app.py
```

## 🌐 Deployment (Streamlit Cloud)

1. Upload all files (`app.py`, `requirements.txt`, and your `.csv` data files) to a public GitHub repository
2. Go to https://streamlit.io/cloud
3. Sign in with your GitHub account and click **"New App"**
4. Select your repository and branch, and enter `app.py` as the main file
5. Click **Deploy** – your project will be live with a public URL!

## 📊 Required Datasets (Uploaded via App Interface)

* `dim_cities.csv`
* `dim_respondents.csv`
* `fact_survey_responses.csv`

## 👨‍💻 Author

**Name:** Harsh Rana  
**Email:** harsh2004rana@gmail.com  
**College:** Government Engineering College, Dahod  
**Enrollment No.:** 220183107021  
**Semester:** 7th (Year 2025)

This project was completed as part of a data analytics internship and demonstrates skills in Python, data cleaning, visualization, and deploying real-world apps using Streamlit.

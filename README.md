﻿Sales Forecasting App
This is a Sales Forecasting Web Application built with Streamlit. It predicts future sales based on key input features such as store information, promotional activities, holidays, and more.

Features
Predicts sales using a pre-trained machine learning model.
Visualizes past sales trends alongside predicted sales.
User-friendly interface for easy input and quick predictions.

Tech Stack
Python
Streamlit for the web interface
Matplotlib for data visualization
Pandas and NumPy for data handling
Pre-trained Machine Learning Model (Pickle format)

How to Run

Clone the repository:
git clone <repository_url>
cd <repository_folder>

Install dependencies:
pip install -r requirements.txt

Run the app:
streamlit run ap.py

Input Features:
Store ID: Unique identifier for the store
Day of the Week: (1 = Monday, 7 = Sunday)
Open: Store status (1 = Open, 0 = Closed)
Promo: Promotion active (1 = Yes, 0 = No)
State Holiday: Holiday indicator (0, a, b, c)
School Holiday: School holiday status (1 = Yes, 0 = No)

Visualization:
Displays past 10 days of sales trends.
Highlights predicted sales for easy comparison.

**Preview**
![Screenshot (423)](https://github.com/user-attachments/assets/5b4a9e0a-b08b-4983-bfc6-3930b74e5a54)
![Screenshot (424)](https://github.com/user-attachments/assets/660beb4e-6ad4-40e8-8609-46eb993a288a)
![Screenshot (425)](https://github.com/user-attachments/assets/cd981059-22a6-4e9a-83cd-2c524558ff45)


You can checkout for the model UI in : https://streamlisales-d89nsrizfs8zzkgq9ydqwb.streamlit.app/

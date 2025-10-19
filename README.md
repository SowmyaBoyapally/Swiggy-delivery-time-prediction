Swiggy Delivery Time Prediction

A Machine Learning web application built using Streamlit that predicts the estimated delivery time for Swiggy orders based on various real-world factors like weather, traffic, delivery agent details, and more.

Project Overview

This project was developed as part of a Machine Learning hands-on workshop conducted by Innomatics Research Labs.
The goal is to build an end-to-end ML solution — from data preprocessing and model training to deployment with Streamlit.
Users can input delivery-related details, and the trained ML model will predict the expected delivery time in minutes.

Tech Stack

Python 
Streamlit (for interactive web app)
Pandas (for data manipulation)
Scikit-learn / Pickle (for ML model loading)

Features

✅ User-friendly web interface using Streamlit
✅ Takes multiple input parameters (weather, traffic, vehicle type, etc.)
✅ Predicts delivery time in minutes
✅ Uses a pre-trained model (model.pkl)
✅ Real-world dataset (swiggy_cleaned.csv)

How to Run the Project

1️.Clone this Repository
git clone https://github.com/your-username/swiggy-delivery-time-prediction.git
cd swiggy-delivery-time-prediction

2️.Install Dependencies
Make sure you have Python installed, then run:
pip install streamlit pandas scikit-learn

3️.Run the Streamlit App
streamlit run app.py

4️.Enter Input Values
Fill in the fields like age, weather, traffic, etc., and click Predict to see the estimated delivery time.

Project Structure

swiggy-delivery-time-prediction/
│
├── app.py                  # Streamlit web app
├── model.pkl               # Trained ML model
├── swiggy_cleaned.csv      # Dataset
├── requirements.txt        # (Optional) Python dependencies
└── README.md               # Project documentation

Input Features

Feature	Description
Age	Delivery agent’s age
Ratings	Average rating of the delivery agent
Weather	Current weather conditions
Traffic	Traffic density during delivery
Vehicle Condition	Condition of the delivery vehicle
Type of Order	Category of food ordered
Type of Vehicle	Bike, scooter, etc.
Multiple Deliveries	Number of deliveries in one trip
Festival	Indicates if it’s a festive day
City Type	Urban / Semi-Urban / Rural
City Name	Location of delivery
Order Day of Week	Day when order was placed
Is Weekend	1 if weekend, else 0
Pickup Time Minutes	Time taken to pick up the order
Order Time Hour	Hour of the order placed
Order Time of Day	Morning / Afternoon / Evening / Night
Distance	Distance between restaurant and delivery point

Example Prediction Output

“The delivery time is 32 minutes ⏱️”

Credits

This project was developed during the Machine Learning Hands-on Workshop (Basics to Deployment) by
Innomatics Research Labs, Dilsukhnagar, Hyderabad.

Future Improvements

Integrate Google Maps API for dynamic distance calculation
Deploy on Streamlit Cloud or Hugging Face Spaces
Add visualization for feature importance

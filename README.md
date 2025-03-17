#Maternal Health Risk Prediction
This project aims to develop a Maternal Health Risk Prediction application using AI-based predictions. The system leverages a pre-trained RandomForest model to assess maternal health risks based on user-provided input. The application provides a professional and engaging UI built with Streamlit (frontend) and a Flask backend stored in csv files for secure data storage and authentication.

#Features
✅ User Authentication: Patients and admins can log in securely.
✅ Patient Dashboard: View last 10 prediction records with timestamps & recommendations.
✅ Admin Dashboard: Access all patient records.
✅ AI-Based Predictions: Submit health data for real-time risk assessment.
✅ Data Storage: User records and predictions are saved in a CSV file.



#Tech Stack
Frontend: Streamlit
Backend: Flask (Python)
Data Storage: CSV file
Machine Learning: Pre-trained RandomForest model (random_forest_model.pkl)

#How It Works
Users log in (Patient/Admin).
Patients enter health details for risk assessment.
The system processes inputs using a RandomForest model.
Predictions are displayed and stored for future reference.
Admins can monitor all patient records.

Ayush Healthbot
===============

**Ayush Healthbot** is an AI-powered tool designed to diagnose diseases based on user-reported symptoms. The tool leverages machine learning models and Ayurvedic principles to offer predictions and potential remedies.

Features
--------

*   **Disease Diagnosis:** Utilizes a supervised machine learning model (KNN and TF-IDF) to analyze symptoms and diagnose diseases.
*   **Ayurvedic-Based Predictions:** Combines modern data analysis with traditional Ayurvedic principles for disease and remedy suggestions.
*   **Interactive User Interface:** A user-friendly UI allows users to input symptoms and receive instant feedback on potential diagnoses.
*   **Extensive Symptom Coverage:** Supports input for a wide range of symptoms to ensure accurate predictions.
*   **Backend Support:** Powered by a Flask backend to handle data processing and model predictions.

Data Collection
---------------

*   **Manual Scraping:** Data for a wide variety of diseases and demographic details were manually scraped and processed.
*   **Data Wrangling:** Extensive data wrangling was performed to clean, organize, and prepare the dataset for effective machine learning.

Installation
------------

To run the Ayush Healthbot locally, follow these steps:

1.  **Clone the repository:**
    
        git clone https://github.com/yourusername/ayush-healthbot.git
    
2.  **Navigate to the project directory:**
    
        cd ayush-healthbot
    
3.  **Install the required dependencies:**
    
        pip install -r requirements.txt
    
4.  **Run the Flask server:**
    
        python app.py
    
5.  **Access the application:**
    
    Open your browser and go to `http://127.0.0.1:5000/`.
    

Usage
-----

*   **Input Symptoms:** Users can enter their symptoms into the UI.
*   **Receive Diagnosis:** The model processes the input and returns a possible diagnosis with Ayurvedic-based remedies.
*   **Explore Remedies:** The application offers suggestions for treatment based on Ayurvedic practices.

Technologies Used
-----------------

*   **Python:** Core programming language for the application.
*   **Flask:** Used for backend development and handling model predictions.
*   **JavaScript:** Supports frontend interactivity.
*   **Data Wrangling Tools:** Employed for cleaning and organizing disease data.
*   **KNN and TF-IDF:** Machine learning algorithms used for symptom analysis and disease prediction.

Contributing
------------

Contributions are welcome! Please fork the repository and submit a pull request with your proposed changes.

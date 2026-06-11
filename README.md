# EcoGrowth: AI-Powered Smart Crop Recommendation System

## Overview

EcoGrowth is an AI-powered agricultural decision support system designed to help farmers select the most suitable and profitable crops based on soil and environmental conditions. The application combines machine learning, rainfall forecasting, and farm advisory services to provide personalized recommendations that improve productivity and reduce farming risks.

## Features

* AI-based crop recommendation using a Random Forest Classifier.
* Rainfall prediction based on historical rainfall patterns.
* Profitability analysis considering cultivation costs and market prices.
* Sustainability-based crop ranking.
* State-wise crop suitability recommendations.
* Personalized farming suggestions to optimize crop yield.
* Step-by-step cultivation guidance for recommended crops.
* Multilingual support for improved accessibility.

## Technologies Used

* Python
* Streamlit
* Scikit-learn
* Pandas
* NumPy
* Joblib
* Googletrans

## Project Structure

```
EcoGrowth/
│
├── app.py
├── rainfall_predictor_model.py
├── historical_rainfall_data.py
├── translations.py
├── crop_recommender_model.joblib
├── crop_class_names.joblib
├── Crop_recommendation.csv
├── requirements.txt
└── README.md
```

## Installation and Setup

### 1. Install Python

Download and install Python 3.10 or later from the official Python website. During installation, ensure that the **"Add Python to PATH"** option is selected.

### 2. Download or Clone the Repository

```bash
git clone <repository-url>
```

or download the ZIP file and extract it.

### 3. Navigate to the Project Directory

```bash
cd EcoGrowth
```

### 4. Create a Virtual Environment (Recommended)

```bash
python -m venv venv
```

### 5. Activate the Virtual Environment

**Windows**

```bash
venv\Scripts\activate
```

**macOS/Linux**

```bash
source venv/bin/activate
```

### 6. Install Dependencies

```bash
pip install -r requirements.txt
```

### 7. Run the Application

```bash
streamlit run app.py
```

### 8. Access the Application

Open the URL displayed in the terminal (usually `http://localhost:8501`) in your web browser.

## Required Files

Ensure the following files are present in the project directory before running the application:

* app.py
* rainfall_predictor_model.py
* historical_rainfall_data.py
* translations.py
* crop_recommender_model.joblib
* crop_class_names.joblib
* Crop_recommendation.csv
* requirements.txt

## Future Enhancements

* Real-time weather data integration.
* Market price prediction and mandi recommendations.
* Voice-based interaction in regional languages.
* Mobile application support.
* Crop disease detection using computer vision.

## Authors

* Dipak Choudhary

## License

This project is developed for educational and research purposes.

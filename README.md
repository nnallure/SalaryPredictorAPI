
# Salary Predictor API

Welcome to the Salary Predictor API repository. This API provides estimated salary predictions based on job title, experience, location, and other relevant factors.

## Overview

This Salary Predictor API uses machine learning models to predict salaries for various job positions across different industries. It is built to assist both individuals in assessing job offers and employers in offering competitive salaries.

## Features

- **Salary Prediction**: Get salary estimates based on job details.
- **Data Insights**: Understand salary trends across different sectors and regions.
- **Easy Integration**: Designed for easy integration with HR and job portal applications.

## How to Use

To use this API, send a POST request to the endpoint with the required job details. Below is a sample request using `curl`:

```bash
curl -X POST https://api.salarypredictor.com/predict \
     -H "Content-Type: application/json" \
     -d '{"title":"Data Scientist", "experience":5, "location":"San Francisco"}'
```

The response will be JSON formatted containing the estimated salary:

Output
```bash
    "predicted_salary": "$120,000"
```

#### Local Setup
To set up and run the API locally, follow these steps:

Clone the repository
```bash
git clone https://github.com/yourusername/salary-predictor-api.git
cd salary-predictor-api
```

Install dependencies
```bash
pip install -r requirements.txt
Run the application
```

Run the application
```bash
python app.py
```

Technologies Used
```bash
- Python: Programming language.
- Flask: Web framework for building the API.
- scikit-learn: Machine learning library to train the prediction model.
```

### Contact
Nikitha Nallure - [niki.nallure@gmail.com](mailto:niki@nallure.com)

Project Link: https://github.com/nnallure/SalaryPredictorAPI

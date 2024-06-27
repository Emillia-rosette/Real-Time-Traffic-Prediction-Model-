# Real-Time-Traffic-Prediction-Model-
This project utilizes historical traffic data to train a machine learning model, such as a neural network/time series model, to predict traffic congestion levels in various parts of London.

### Project Overview
This project aims to predict real-time traffic conditions in London using historical traffic data provided by Transport for London. The goal is to enhance urban mobility by providing accurate traffic predictions and visualizing them through an interactive dashboard.

### Features
- Real-time traffic prediction using machine learning models.
-  Integration and analysis of traffic data from Transport for London.
- Interactive dashboard for visualizing traffic conditions and predictions.

### Data Sources
Traffic Data: Obtained from Transport for London.

### Architecture
A high-level architecture of the project, including data collection, preprocessing, model training, and dashboard visualization.
![Screenshot 2024-06-27 at 15 55 24](https://github.com/Emillia-rosette/Real-Time-Traffic-Prediction-Model-/assets/36535655/e37e5591-8989-4850-a28c-0b977ce562f6)


### Setup Instructions
#### Prerequisites
- Google Cloud Account: Set up a Google Cloud account if you don't already have one.
- Google Cloud SDK: Install the Google Cloud SDK on your local machine.
- VS Code: Install Visual Studio Code.
- Python: Ensure Python 3.8 or higher is installed on your machine.
- Virtual Environment Tool: Use venv or virtualenv for managing virtual environments.


### Step-by-Step Setup
Clone the Repository: `git clone git@github.com:Emillia-rosette/Real-Time-Traffic-Prediction-Model-.git`

cd real-time-traffic-prediction


###  Set Up a Virtual Environment:

`python3 -m venv venv`
`source venv/bin/activate`  # On Windows use `venv\Scripts\activate`

###  Install Dependencies:
`pip install -r requirements.txt`


### Google Cloud Setup:

#### Install Google Cloud SDK:
Follow the installation instructions for your operating system from the Google Cloud SDK documentation(https://cloud.google.com/sdk/docs)

#### Initialize Google Cloud SDK:
`gcloud init`

#### Create a Google Cloud Storage Bucket:
`gsutil mb -l your-preferred-region gs://your-bucket-name`

#### Set Up Service Account shown here: (https://cloud.google.com/iam/docs/service-accounts-create)

#### Update your data collection script to upload data to Google Cloud Storage after collection
Use the google.cloud.storage library in Python for uploading files to Google Cloud Storage (GCS): (https://cloud.google.com/storage/docs/reference/libraries#client-libraries-usage-python)

### Run Data Collection Script
`python data_collection.py`

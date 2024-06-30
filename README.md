
# Resume Screening App

This is a web application built using Streamlit for screening resumes. The application classifies resumes into various categories using a pre-trained machine learning model.

You can access the live application [here](https://resume-screening-webapp-9.streamlit.app/).

## Installation

1. Clone the repository or download the source code.
2. Navigate to the project directory.

```sh
cd /path/to/project
```

3. Install the required packages.

```sh
pip install -r requirements.txt
```

## Usage

1. Upload a resume file (in .txt or .pdf format) using the web interface.
2. The application will predict the category of the resume and display it.

## Model Training (Optional)

If you want to train the model yourself, follow these steps:

1. Load your dataset and preprocess it as shown in the `train_model.py` script.
2. Train the model and save the trained models (`clf.pkl` and `tfidf.pkl`).


3. Ensure the trained models are in the project directory before running the Streamlit application.

## Files

- `app.py`: Main Streamlit application script.
- `train_model.py`: Script to train and save the machine learning model.
- `requirements.txt`: List of required Python packages.
- `README.md`: This file.


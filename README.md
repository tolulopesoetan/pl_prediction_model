This project explores premier league matches outcome prediction using 
1. bookmaker odds
2. team form
3. expected goals (xG)
4. historical football news sentiment
4. classical machine learning models

The goal is to compare:

- the bookmaker market baseline
- pre-match machine learning models
- pre-match machine learning models with sentiment features
- half-time machine learning models

# Project structure

- `notebooks/01_data_ingestion_and_preprocessing.ipynb`
- `notebooks/02_model_training.ipynb`
- `notebooks/03_evaluation_and_results.ipynb`

Setup:

1. Create a virtual environment:
   python -m venv .venv
   source .venv/bin/activate

2. Install dependencies:
   pip install -r requirements.txt

3. Create a .env file locally:
   GUARDIAN_API_KEY=your_api_key_here

4. Run notebooks in order:
   notebooks/01_data_ingestion_and_preprocessing.ipynb
   notebooks/02_model_training.ipynb
   notebooks/03_evaluation_and_results.ipynb

Note: The real .env file is not included for security reasons.


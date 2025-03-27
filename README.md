# Flask Web App Starter

A Flask starter template as per [these docs](https://flask.palletsprojects.com/en/3.0.x/quickstart/#a-minimal-application).

## Getting Started

Previews should run automatically when starting a workspace.

## Local Deployment Steps

1.  Set up a Python virtual environment: `python -m venv .venv`
2.  Activate the virtual environment: `source .venv/bin/activate`
3.  Install dependencies from requirements.txt: `pip install -r requirements.txt`
4. Start the development server using the command: `python main.py`


## Using Cloud SQL for data

1. Create a mysql db in Cloud SQL
2. Allow unrestricted access in networking.
3. Enable public ip and note it down.
4. Replace "localhost" with "public ip" of db...


## Deploy to App Engine

1. Create an app.yaml file for runtime and entrypoint.
2. This "app.yaml" file need to be created in root directory where main.py is present.
3. It will automatically install requirements.
4. Use gcloud CLI in your terminal and auth with your account.
5. use commands -
6. gcloud config set project YOUR_PROJECT_ID
7. gcloud app create --region=us-central1
8. gcloud app deploy
9. gcloud app browse
10. gcloud app logs tail -s default

# CHATBOT

## PRE-REQUISITE

**POETRY** should be installed on your machine.

## INSTALLATION

### Install dependencies

```bash
poetry install --no-root
```

### Setup Gemini API key

This program requires google studios ai keys.  
As it uses googles-gemini-ai.  
You can create a free api key from
https://aistudio.google.com/app/apikey

### FIRESTORE SETUP

Steps to replicate this example:

1. Create a Firebase account
2. Create a new Firebase project
   - Copy the project ID
3. Create a Firestore database in the Firebase project
4. Install the Google Cloud CLI on your computer
   - https://cloud.google.com/sdk/docs/install
   - Authenticate the Google Cloud CLI with your Google account
     - https://cloud.google.com/docs/authentication/provide-credentials-adc#local-dev
   - Set your default project to the new Firebase project you created
5. Enable the Firestore API in the Google Cloud Console:
   - https://console.cloud.google.com/apis/enableflow?apiid=firestore.googleapis.com&project=crewai-automation

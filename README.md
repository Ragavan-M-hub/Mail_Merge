# Gmail Invitation Sender 📧

This Python script automates sending personalized invitation emails via Gmail. It uses the Gmail API to authenticate and send emails to a list of recipients, replacing a placeholder in the letter template with each recipient's name.

## Features

- ✅ Google OAuth2 authentication
- ✅ Sends emails using Gmail API
- ✅ Personalizes messages using a template
- ✅ Automatically encodes and sends MIME emails
- ✅ Reads recipients from a file


## ✅ Prerequisites

- Python 3.12.4 or later
- Google Cloud Project with Gmail API enabled
- `credentials.json` file from Google Cloud Console
- Required Python packages:
  ```bash
  pip install --upgrade google-auth google-auth-oauthlib google-api-python-client



# HNG12 API Project

This is a simple API for the HNG12 internship project that returns the following information in JSON format:
- Your registered email address.
- The current date and time in ISO 8601 format (UTC).
- The URL of the project's GitHub repository.

## Setup Instructions

1. Clone the repository:
   
   git clone https://github.com/yourusername/hng12-api.git

2. Create a virtual environment:

python -m venv venv


3. Activate the virtual environment:

On Windows:

venv\Scripts\activate

On Mac/Linux:

source venv/bin/activate



4. Install dependencies:

pip install flask flask-cors


5. Run the API:

python app.py



API Documentation

Endpoint: /

Request Method: GET

Response Format: JSON

Response Example:

{
  "email": "your-email@example.com",
  "current_datetime": "2025-01-30T09:30:00Z",
  "github_url": "https://github.com/yourusername/hng12-api"
}

email: Your registered email used for the HNG12 Slack workspace.

current_datetime: The current date and time, dynamically generated in ISO 8601 format (UTC).

github_url: The URL to the GitHub repository hosting this API.



Resources

For more information on Python Flask, refer to the official documentation:
https://flask.palletsprojects.com/en/stable/

Looking for skilled Python developers? Check out:
https://hng.tech/hire/python-developers

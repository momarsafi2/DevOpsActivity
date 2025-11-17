# C8. DevOps - ACTIVITY — Omar Safi

## How to Run

1. Unzip the project folder
2. Open the folder in VS Code
3. Create and activate a virtual environment using terminal:
   python -m venv venv
   venv\Scripts\activate
4. pip install -r requirements.txt
5. Run the Flask app:
   python app.py
6. Endpoints:
   http://127.0.0.1:5000/hello
   POST: http://127.0.0.1:5000/echo

## How to Test

1. Run all tests locally:
   pytest -q
2. Run with coverage:
   pytest --cov=app

## Implemented

1. GET /hello:
   { "message": "Hello, World!" }
2. POST /echo"
   Accepts JSON input and returns status code 201.

## Tests

Added two unit tests using pytest:

1. test_hello():
   verifies /hello returns 200 and correct JSON
2. test_echo():
   verifies /echo returns 201 and echoes the payload

## Evidence

- `screenshots/` screenshots include all passing workflows such as tests workflow, linting, codeQL, codecov, etc.

## Github Repository link:

https://github.com/momarsafi2/DevOpsActivity.git

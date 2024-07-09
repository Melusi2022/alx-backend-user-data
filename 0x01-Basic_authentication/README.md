# Basic Authentication Project

## Description
This project demonstrates the use of Basic Authentication in a Python-based API.

## Setup
1. Install dependencies:
    ```bash
    pip3 install -r requirements.txt
    ```

2. Start the server:
    ```bash
    API_HOST=0.0.0.0 API_PORT=5000 python3 -m api.v1.app
    ```

3. Test the API:
    ```bash
    curl "http://0.0.0.0:5000/api/v1/status" -vvv
    ```

## Scripts

### Base64 Encoding
`encode_base64.py` - Script to encode a string in Base64.

### Basic Authentication Header
`basic_auth.py` - Script to send an Authorization header with Basic Authentication.

## Requirements
- Python 3.7
- pycodestyle 2.5

## Usage
Ensure all scripts are executable:
```bash
chmod +x <script_name>.py

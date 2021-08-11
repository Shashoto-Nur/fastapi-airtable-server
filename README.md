# FastApi with Airtable

A FastApi server that uses an external api.

## Installation

1. Make sure you have python installed.
2. Fill up the src/.env.example with appropriate credentials and remove '.example' from its name.
3. Run the following commands sequentially:
    ```cmd
        python -m pip install --upgrade pip
        .\Scripts\activate
        pip install -r requirements.txt
        uvicorn src.app:app --reload --port 5000
    ```

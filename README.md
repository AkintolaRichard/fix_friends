# calender_app
## Usage

## Pre-requisites
    python3 -m install fastapi
    python3 install pip fastapi
    pip install uvicorn

## Run the live server:
<p align="center">
<img src='./Resources/FastAPI.png'/>
</p>
    
    The command uvicorn main:app refers to:

    main: the file main.py (the Python "module").
    app: the object created inside of main.py with the line app = FastAPI().
    --reload: make the server restart after code changes. Only use for development.

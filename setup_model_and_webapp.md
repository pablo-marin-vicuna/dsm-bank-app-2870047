# Setup venv
- `py -m venv venv`
- `venv\Scripts\activate`

# Create .flaskenv
    FLASK_ENV=development
    FLASK_APP=main.py

- `pip install python-dotenv`

# create application (already done?)
- create `main.py`
- create folder `application`
- create file `__init__.py` in application folder. contains jupyter notebook code. Copy from https://github.com/LinkedInLearning/dsm-bank-model-2870047/blob/main/application/__init__.py

# install requirements
- `pip install sklearn`
- `pip install pandas`
- `pip install -r requirements.txt` (needed to fix several version numbers and comment out pywin32. Use python install_packages.py to do 1 by 1 install to see conflicts locally. Then will need to do similar with Heroku)

# initilaize bank flask app (open on another terminal)
- `cd dsm-bank-app-2870047`
- `set FLASK_APP=main.py`
- `flask run --port 8082`
- on browers: `http://127.0.0.1:8082`


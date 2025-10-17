# create a python virtualenv
python3 -m venv .venv

# activate it 
 .\.venv\Scripts\Activate.ps1

 pip install -r requirements.txt

 uvicorn app.main:app --reload
# Project Setup Instructions


### Step 1: Install `virtualenv`
First, install `virtualenv` using pip:
```bash
pip install virtualenv

virtualenv venv

venv\Scripts\Activate

source venv/bin/activate

pip install -r requirements.txt

python manage.py makemigrations
python manage.py migrate

python manage.py runserver



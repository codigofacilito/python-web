python3 -m venv env

source env/bin/active

pip install -r requirements.txt

python manage.py db init

python manage.py runserver

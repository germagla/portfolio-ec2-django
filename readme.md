python3 -m venv env

source env/bin/activate

touch .env

pip install -r requirements.txt

python manage.py migrate

python manage.py collectstatic

python manage.py runserver
Repo contains submodules, use the --recursive flag when cloning!

(git clone --recursive repository-url)

python3 -m venv env

source env/bin/activate

touch .env

pip install -r requirements.txt

python manage.py makemigrations && python manage.py migrate

python manage.py collectstatic

python manage.py runserver

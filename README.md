git clone url
cd project
virtualenv venv
source venv/bin/activate
pip install django
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
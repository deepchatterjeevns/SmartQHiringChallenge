# SmartQHiringChallenge
Hackerearth SmartQHiringChallenge Nov 2019

# Creating the image
`docker-compose build`
`docker-compose push`

# Running the application
`docker-compose up restaurant`

# Running application from image
`docker run --rm -it -p=8000:8000 deepaksood619/restaurant:0.0.1`

Navigate to localhost:8000 in browser

```bash
django-admin startproject restaurant .
python3 manage.py startapp sales

python3 manage.py makemigrations
python3 manage.py migrate

python3 manage.py runserver 0.0.0.0:8000

python3 mange.py loaddata

python3 manage.py createsuperuser
```
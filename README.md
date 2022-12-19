# Setup pipenv & Install Requirements
```sh
pip install pipenv
pipenv install -r requirements.txt
pipenv shell
```
# Set Up RabbitMQ Server
```sh
sudo apt-get install rabbitmq-server
service rabbitmq-server start
```
# make database migrations
python manage.py makemigrations
python manage.py migrate
```
# Start Server
```sh
python manage.py runserver
```

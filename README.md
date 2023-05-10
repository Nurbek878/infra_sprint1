## Kittygram

Kittygram is a social network for sharing photos of your favorite pets.

## Tech Stack

Python 3.9\
Django 3.2\
Djangorestframework 3.12\
Gunicorn 20.1.0 \
Nginx

## Project launch
Clone the project

```bash
  git clone git@github.com:Nurbek878/infra_sprint1.git
```
## Running a backend project on the server

Go to the project directory

```bash
  cd infra_sprint1/backend
```
Install and activate the virtual environment
```bash
  python3 -m venv venv
```
```bash
  source venv/bin/activate
```
Install dependencies from the file requirements.txt

```bash
  pip install -r requirements.txt
```
Make migrations
```bash
  python manage.py migrate
```
Start the server

```bash
  python manage.py runserver
```

## Running the frontend project on the server

From any directory, execute the commands sequentially

```bash
curl -fsSL https://deb.nodesource.com/setup_18.x | sudo -E bash - &&\
sudo apt-get install -y nodejs 
```
Go to the infra_sprint1/frontend/ directory and run the command

```bash
npm i  
```
The application is ready to launch. Run it

```bash
npm run start 
```

## Authors

- [@nurbek878](https://github.com/Nurbek878)# infra_sprint1

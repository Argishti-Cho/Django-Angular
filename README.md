

# DevOps Test Project

This project is a test project for DevOps classes at ACA. It utilizes Django Rest API and Angular 14.

## Getting Started

### Front-End Setup

1. Clone the repository:
   ```shell
git clone git@github.com:Argishti-Cho/Django-Angular.git

### Install Node.js:
Visit nodejs.org and choose your operating system version.
Run the following command to install Node.js and npm:
sudo apt install nodejs

### This will also install nVerify the installation by running node -v to check the Node.js version.
### Install Angular CLI (Version 14):
npm install -g @angular/cli@14

### Verify the installation by running ng --version to check the Angular CLI version.
### Run the Angular app on localhost:4200:
### In the Project root directory run the following commandng serve --open
If port :4200 is already in use or you need a custom port, you can run:
ng serve --host 0.0.0.0 --port 8080


## Back-End Setup
Open another terminal separate from the Angular terminal.

Install Python 3.11:sudo apt update && sudo apt upgradesudo apt install wget build-essential libncursesw5-dev libssl-dev libsqlite3-dev tk-dev libgdbm-dev libc6-dev libbz2-dev libffi-dev zlib1g-devsudo add-apt-repository ppa:deadsnakes/ppasudo apt install python3.11

### Set up a Python virtual environment:
Make sure you are in the project's root directory.
Create a virtual environment:python3 -m venv venv

### Activate the virtual environment:
source ./venv/bin/activate

### Install or ipgrade Pip
python -m pip install --upgrade pip

### Install project dependencies:
pip install -r DjangoApi/requirements.txt

### Run the Django server:
By default, the server runs on localhost:8000:
python manage.py runserver
### for a custom server, run:
python manage.py runserver localhost:9090
### Note: Do not use the same port as the Angular app.

### for deactivation just run commande 
deactivate
exit

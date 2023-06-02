# DevOps Test Project

This project is a test project for DevOps classes at ACA. It utilizes Django Rest API and Angular 14.

## Getting Started

### Front-End Setup

1. Clone the repository:
   ```shell
   git clone git@github.com:Argishti-Cho/Django-Angular.git
Install Node.js:

2. Visit nodejs.org and choose your operating system version.
Run the following command to install Node.js and npm:
    ```shell
    sudo apt install nodejs
This will also install npm. Verify the installation by running node -v to check the Node.js version.
Install Angular CLI (Version 14):

shell
npm install -g @angular/cli@14
Verify the installation by running ng --version to check the Angular CLI version.

Run the Angular app on localhost:4200:

shell
ng serve --open
If port :4200 is already in use or you need a custom port, you can run:

shell
ng serve --host 0.0.0.0 --port 8080
Back-End Setup
Open another terminal separate from the Angular terminal.

Install Python 3.11:

shell
sudo apt update && sudo apt upgrade
sudo apt install wget build-essential libncursesw5-dev libssl-dev libsqlite3-dev tk-dev libgdbm-dev libc6-dev libbz2-dev libffi-dev zlib1g-dev
sudo add-apt-repository ppa:deadsnakes/ppa
sudo apt install python3.11
Set up a Python virtual environment:

Make sure you are in the project's root directory.
Create a virtual environment:
shell
python3 -m venv venv
Activate the virtual environment:
shell
source ./venv/bin/activate
Install or upgrade Pip:

shell
python -m pip install --upgrade pip
Install project dependencies:

shell
pip install -r DjangoApi/requirements.txt
Run the Django server:

By default, the server runs on localhost:8000:
shell
python manage.py runserver
For a custom server, run:
shell
python manage.py runserver localhost:9090
Note: Do not use the same port as the Angular app.
To deactivate the virtual environment, run the following command:

shell
deactivate
exit
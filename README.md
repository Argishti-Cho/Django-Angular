# DevOps Test Project

This project is a test project for DevOps classes at ACA. It utilizes Django Rest API and Angular 14.

## Getting Started

### Front-End Setup

1. Clone the repository:
   ```shell
   git clone git@github.com:Argishti-Cho/Django-Angular.git
2. Install Node.js:
Visit nodejs.org and choose your operating system version.
Run the following command to install Node.js and npm:
    ```shell
    sudo apt install nodejs
This will also install npm. Verify the installation by running `node -v` to check the Node.js version.

3. Install Angular CLI (Version 14):
    ```shell
    npm install -g @angular/cli@14
Verify the installation by running `ng --version` to check the Angular CLI version.

4. Run the Angular app on localhost:4200:
    ```shell
    ng serve --open
If port :4200 is already in use or you need a custom port, you can run:
    ```shell
    ng serve --host 0.0.0.0 --port 8080

## Back-End Setup

Open another terminal separate from the Angular terminal.
5. Install Python 3.11:

    ```shell
    sudo apt update && sudo apt upgrade
    sudo apt install wget build-essential libncursesw5-dev libssl-dev libsqlite3-dev tk-dev libgdbm-dev libc6-dev libbz2-dev libffi-dev zlib1g-dev
    sudo add-apt-repository ppa:deadsnakes/ppa
    sudo apt install python3.11


6. Create a virtual environment:
Make sure you are in the project's root directory.
    ```shell
    python3 -m venv venv
7. Activate the virtual environment:
    ```shell
    source ./venv/bin/activate
8. Install and upgrade Pip:
    ```shell
    python -m pip install --upgrade pip
9. Install project dependencies:
    ```shell
    pip install -r DjangoApi/requirements.txt
Run the Django server: By default, the server runs on localhost:8000
    ```shell
    python manage.py runserver
For a custom server, run:
    ```shell
    python manage.py runserver localhost:9090
Note: Do not use the same port as the Angular app.
To deactivate the virtual environment, run the following command:
    ```shell
    deactivate
    exit
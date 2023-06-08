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

4. Build the Angular app:
    ```shell
    ng build 
It will create a dist/angular14, upload all files inside the dist/angular14 folder into your s3bucket
    so the index.html will be in the rootdirectory

## Back-End Setup

5. Open another terminal separate from the Angular terminal.
Install Python 3.11
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
10. Run the Django server: By default, the server runs on localhost:8000 .
    Do not use the same port as the Angular app.
    ```shell
    python manage.py runserver
For a custom server, run `python manage.py runserver localhost:9090`

To deactivate the virtual environment, simply run `deactivate` and then `exit`

### Note. 
open user_interface/angular14/src/app/share.service.ts in any text editor and see the lines 9 and 10
It is the API of your backend, update if backend's API changes  
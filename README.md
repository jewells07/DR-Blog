# DR-Blog
DR-Blog is a blog application implemented using DR(Django + React). The styling for the application is done using Bootstrap 4.5

# Setup
Clone this project.

## Backend

1. Move to the base directory: ```cd backend```

2. Create a new python enveronment with: ```python -m venv env```.

3. Activate enveronment with: ```env\Scripts\activate``` on windows, or ```source env/bin/activate``` on Mac and Linux.

4. Install required dependences with: ```pip install -r requirements.txt```.

5. Make migrations with: ```python manage.py makemigrations``` and then ```python manage.py migrate```.

6. Run app localy with: ```python manage.py runserver```.

## Frontend 

1. Move to the base directory: ```cd frontend```

2. Install all dependencies: ```npm install```.

3. Runs the app in the development mode: ```npm install```.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

4. Builds the app for production to the `build` folder. ```npm run build```.

### Final setup
From frontend move build directory into backend directory
Run app localy with: ```python manage.py runserver```.

#### Note
To see React working perfectly, Logout from admin panel

## Certificate
This project is officialy certified by Jewells Joshi.
All rights reserved 2020.
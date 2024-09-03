# movie-rating

## Setup

Clone this repository and move to movie-rating folder

`git clone https://github.com/Cyri0/movie-rating.git`

Create virtual environment and activate

`python -m venv movievenv`

`.\movievenv\Scripts\activate`

If works (movievenv) appears on terminal
Then install the backend requirements

`pip install -r requirements.txt`

Frontend setup

`cd backend\frontend\`

`npm i`

`npm run build`

Migrate DB and run server

`python manage.py migrate`

`python manage.py runserver`


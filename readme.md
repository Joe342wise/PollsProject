# Polls App (Django Tutorial Project)

> This is a simple Polls application built by following the official Django documentation tutorial.
It allows users to view polls, vote for choices, and see results.

## Features

- View a list of available polls
- Vote on a selected poll
- See the results of a poll after voting
- Basic styling added using custom CSS

## Technologies Used

- Python 3
- Django (latest stable version)
- HTML5
- CSS3 (custom styles)
- SQLite3 (default Django database for development)

## Project Structure

``` bash
pollsProject/ 
├── polls/ 
│ ├── migrations/ 
│ ├── static/ 
│ │ └── polls/ 
│ │ └── style.css 
│ ├── templates/ 
│ │ └── polls/ 
│ │ ├── index.html 
│ │ ├── detail.html 
│ │ └── results.html 
│ ├── admin.py 
│ ├── apps.py 
│ ├── models.py 
│ ├── tests.py 
│ ├── urls.py 
│ └── views.py 
├── manage.py 
└── polls_project/ 
├── init.py 
├── settings.py 
├── urls.py 
└── wsgi.py
```

## How to Run Locally

### Clone the repository

```bash
git clone <repository-url>
cd polls_project
```

### Create a virtual environment

```bash
python -m venv env
source env/bin/activate   # For Linux/Mac
env\Scripts\activate      # For Windows
```

### Install Django

```bash
pip install django
```

### Apply migrations

```bash
python manage.py migrate
```

### Run the development server

```bush
python mange.py runserver
```

### Acess the app

>Vist <http://127.0.0.1:8000/polls/> in your web browser

## Progress So Far

- Completed building the basic Polls app according to the Django tutorial
- Created models for Question and Choice
- Set up views for:
  - Index (list of questions)
  - Detail (poll voting page)
  - Results (display votes)

- Added and linked static CSS styling to improve the appearance of templates

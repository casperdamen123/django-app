# Django Poll App

This is a simple poll app built with Django. It allows users to create polls with multiple choices and vote on them.

## Installation

1. Clone the repository: `git clone https://github.com/your-username/django-poll-app.git`
2. Navigate to the project directory: `cd django-poll-app`
3. Install Poetry: Follow the instructions on the [Poetry website](https://python-poetry.org/docs/#installation) to install Poetry.
4. Create a virtual environment: `poetry shell`
5. Install the dependencies: `poetry install`
6. Run the migrations: `python manage.py migrate`
7. Start the development server: `python manage.py runserver`

## Usage

1. Create a poll by navigating to the admin panel (`/admin`) and adding a new poll with choices.
2. View the poll by navigating to the poll detail page (`/polls/<poll_id>/`).
3. Vote on the poll by selecting a choice and submitting the form.
4. View the results of the poll on the poll detail page.

## Testing

1. Run the unit tests: `python manage.py test`

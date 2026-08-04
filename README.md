# Ballot-box

Ballot-box is a Django-based electronic voting platform for organizing elections, managing candidates, casting ballots securely, and viewing live results.

## Features
- Create and manage elections
- Add and organize candidates
- Allow voters to cast ballots securely
- View election results in real time

## Setup
1. Create and activate a virtual environment.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Apply database migrations:
   ```bash
   python manage.py migrate
   ```
4. Create a superuser if needed:
   ```bash
   python manage.py createsuperuser
   ```

## Run the project
```bash
python manage.py runserver
```

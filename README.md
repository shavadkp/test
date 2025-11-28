# test
book rentel
# Rewardz - Student Book Rentals

## Objective
Simple Django + DRF app allowing students to rent books. First month is free. Each subsequent month is charged at (number_of_pages / 100) USD per month.

When creating a rental you can provide a book title — the app will fetch book details (including page count) from OpenLibrary.

## Tech stack
- Django
- Django REST Framework
- requests (for OpenLibrary)
- SQLite (development default)

## Setup (local)
1. Clone the repo (private repo to be created for submission).
2. Create and activate a virtualenv:
   ```bash
   python -m venv venv
   source venv/bin/activate

   python manage.py runserver
http://127.0.0.1:8000/api/
http://127.0.0.1:8000/admin/

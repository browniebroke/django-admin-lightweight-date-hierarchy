## Example Project for django_admin_lightweight_date_hierarchy

This example is provided as a convenience to allow potential users to try
the app straight from the app repo without having to create a Django
project.

To run this example, follow these instructions:

1. Navigate to the `example` directory.

2. Make and apply migrations

    python manage.py makemigrations
    python manage.py migrate

3. Create a super-user to access admin

    python manage.py createsuperuser

4. Load test data

    python manage.py loaddata sales/fixtures/dev/sales.json

5. Run the server

    python manage.py runserver

6. Access from the browser at `http://127.0.0.1:8000/admin`.

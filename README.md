## django-rest-framework-app

Sample app using the Django Rest Framework for study purposes.

To run the application:

```bash
docker compose up --build -d
```

Then check http://localhost:8000.

To run tests:

```bash
docker compose run --rm  app sh -c "python manage.py test"
```

To lint with `flake8`:

```bash
docker compose run --rm  app sh -c "flake8"
```

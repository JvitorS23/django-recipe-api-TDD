# recipe-app-api-TDD

Recipe app API source code. Implemented with test driven development.

## Requirements

* [Django](https://www.djangoproject.com/)
* [Django Rest Framework](https://www.django-rest-framework.org/)
* [psycopg2](https://pypi.org/project/psycopg2/)
* [flake8](https://pypi.org/project/flake8/) (optional)
* [Pillow](https://pillow.readthedocs.io/en/stable/)

## Run the API:

Run using Docker: `docker-compose up`

## Features

* Create user `/api/user/create/`
* Generate authentication token `/api/user/token/`
* Manage recipe tags `/api/recipe/tags/`
* Manage recipe ingredients `/api/recipe/ingredients/`
* Manage recipes `/api/recipe/recipes/`
* Upload recipe image `/api/recipe/recipes/{recipe_id}/upload-image/`
* Filter recipes by tags and ingredients
* Database: PostgreSQL

## Implemented tests:

* Tests for all models
* Tests for all endpoints
* Authentication tests
* Test image upload
* Test filtering




# blog-api

A blog API with CRUD functionality, built using Django REST Framework.

### Local Setup

1. Ensure Python 3.7x and Pipenv are already installed. [How To Setup.](https://djangoforbeginners.com/initial-setup/)
2. Clone the repo and configure the virtual environment

```
 $ git clone https://github.com/nickmwangemi/blog-api.git
 $ cd blog-api
 $ pipenv install
 $ pipenv shell
```

3. Run migrations and setup setup superuser account.

```
 $ python3 manage.py migrate
 $ python3 manage.py createsuperuser
```

4. Run local development server instance.

```
 $ python3 manage.py runserver
```

Crack open the Browsable API available at [http://127.0.0.1:8000/api/v1/](http://127.0.0.1:8000/api/v1/)

Also, Swagger UI documentation is available at [http://127.0.0.1:8000/swagger/](http://127.0.0.1:8000/swagger/)

## Endpoints

| Endpoint                          | HTTP Verb |
| --------------------------------- | --------- |
| /                                 | GET       |
| /:pk/                             | GET       |
| users/                            | GET       |
| users/:pk/                        | GET       |
| /rest-auth/registration           | POST      |
| /rest-auth/login                  | POST      |
| /rest-auth/logout                 | GET       |
| /rest-auth/password/reset         | POST      |
| /rest-auth/password/reset/confirm | POST      |

#

A live version of this project is available at [https://blog-api-docs.herokuapp.com/swagger/](https://blog-api-docs.herokuapp.com/swagger/). 🚀

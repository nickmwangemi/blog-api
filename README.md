# blog-api

A blog API with CRUD functionality, built using Django REST Framework.

### Local Setup

- Clone Repo or [download](https://github.com/nickmwangemi/blog-api/archive/master.zip) the project then unzip in a directory of choice.

```
git clone https://github.com/nickmwangemi/blog-api.git
```

- Change directory into root project folder.

```
cd blog-api
```

- Activate virtual environment.

```
pipenv shell
```

- Install project dependencies.

```
pipenv install
```

- Run migrations.

```
python3 manage.py migrate
```

- Create superuser.

```
python3 manage.py createsuperuser
```

- Run local development server instance.

```
python3 manage.py runserver
```

Crack open the Browsable API available at [http://127.0.0.1:8000/api/v1/](http://127.0.0.1:8000/api/v1/) 🚀

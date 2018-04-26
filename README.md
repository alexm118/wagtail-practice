# wagtail-practice
Practice Repo for a Wagtail CMS utilizing Bootstrap

## Running the Application
```sh
docker-compose up -d
```

## Create a Superuser
In order to enter the admin console, you need to create a superuser using the following command.
```sh
docker-compose exec web python manage.py createsuperuser
```


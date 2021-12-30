# recipe-app-api
Recipe app api source code.

## Commands
### Run application
```shell
docker-compose up
```

### Test
```
docker-compose run --rm app sh -c "python manage.py test && flake8"
```

### Migrations
```
docker-compose run --rm app sh -c "python manage.py makemigrations core"
```
# Base Symfony Docker boilerplate

For now just CLI.

1. `docker-compose build`
2. `docker-compose up`
3. `docker-compose run --rm php_cli bin/console cache:clear`

### If you want to have new Symfony project instead of using current
Remove everything, leave only:
* `.docker`
* `docker-compose.yml`
* `.gitignore`
* `docker-compose run --rm composer create-project symfony/website-skeleton your-project`
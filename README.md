# Base PHP + Composer Docker boilerplate

For now just CLI and PHP 7.1.

This boilerplate is created to minimize amount of software that's needed to be installed on your machine until you can run any PHP project.

Everything is based on Docker, so the only things you need are:
* Docker
* docker-compose

Everything else is based on your personal preferences (you can find few references to PHPStorm here, don't bother).


1. Copy `auth.json.dist` to `auth.json` and paste your GitHub token.
1. `docker-compose build`
2. `docker-compose up`
4. `docker-compose run --rm composer create-project symfony/website-skeleton your-project`

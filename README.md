# Dev Environment for Docker

<img src="https://preview.dragon-code.pro/andrey-helldar/dev-environment.svg?brand=docker" alt="Docker Environment"/>

> [!WARNING]
>
> THis repository is deprecated. Use [Docker Environment](https://github.com/andrey-helldar/docker-environment) instead.

## List of services

* MySQL
* PostgreSQL - pgAdmin
* Redis + Admin
* RabbitMQ
* Elasticsearch
* Mailhog

## Installation & Settings

![how to use](.github/images/how-to-use.gif)

## Credentials

By default, the following credentials are used:

```ini
DB_DATABASE = default
DB_USERNAME = dev
DB_PASSWORD = dev

REDIS_WEBUI_CONNECT_HOST = redis
REDIS_WEBUI_CONNECT_PORT = 6379
REDIS_WEBUI_PORT = 9987
```

If you do not specify the path to the folder at the time of creation, then the repository is cloned to the default path:

- `~/.docker/devenvironmentswork` for Unix
- `%USERPROFILE%\.docker\devenvironmentswork\` for Windows

By default, `Docker Dev Environments` loads and starts all services.

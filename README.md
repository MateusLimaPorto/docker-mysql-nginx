## Installation

1 - Clone this repository. [docker-mysql-nginx](https://github.com/MateusLimaPorto/docker-mysql-nginx.git)\
2 - Make sure you have [Docker](https://www.docker.com/) installed \
3 - To make containers up run "docker-compose up -d" \

```bash
git clone https://github.com/MateusLimaPorto/docker-mysql-nginx.git
```

```bash
cd docker-mysql-nginx
docker-compose up -d
```

## How do I connect to the database?

In your Workbench or other DBMS, put the following configuration: \
Host: localhost \
Port: 3306 \
Database: mysql \
User: dev \
Password: dev
# Aznable SQL

An implementation of centralized SQL servers under [Aznable Infra](https://github.com/aznable/infra).

## Installation

Install `Aznable SQL` by cloning its Github repository:

```
git clone https://github.com/aznable/sql.git
cd sql
cp .env.example .env
```

## Initial Configuration

Set up the MySQL root password using the `MYSQL_PASSWORD` variable in the `.env` file:

```
MYSQL_PASSWORD=helloworld
```

## Basic Usage

To run the containers, kindly execute the command below:

```
$ docker-compose up -d
```

## Accessing the `mysql` service

Execute the command below to access the `mysql` service:

```
$ docker exec -it mysql mysql -u root -p
```

**NOTE**: Use the value from `MYSQL_PASSWORD` for its `root` password.
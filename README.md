# Kafka-connect sample docker images

Kafka-connect environment with mySQL e mongodb connectors using docker-compose tool

## Necessary Tools
* docker
* docker-compose

## Execute

In root execute the command

```shell
docker compose up
```

## Run

In console - enter in kafka connect
- login mysql database (user, password and database name in docker-compose file)
- Create any tables and insert values
- Access Control-center confluent in localhost:9021 and add two connector by config file from folder "connector" in this repository.
- Access mongo express localhost:8085 to see data from mysql in mongodb database
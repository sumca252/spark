# spark platform

All Spark services started from a single repository

## Requirements

- [Docker](https://docs.docker.com/install/)
- [Docker Compose](https://docs.docker.com/compose/install/)

## Usage

### Start All Services
```bash
docker-compose up -d 
```

### Start Specific Service
```bash
docker-compose up -d <service_name> <service_name> ...
```
### Stop Specific Service
```bash
docker-compose up -d <service_name> ...
```
### Stop All Services
```bash 
docker-compose down
```

### Restart All Services

```bash
docker-compose restart
``` 

### Logs

```bash 
docker-compose logs -f <service_name> ...
```


### Status

```bash
docker-compose ps
```

# How to run it?

## Start all services

```bash
make run
```

## Stop all services

```bash
make stop
```

## Restart all services

```bash
make restart
```

## Run only backend services
    
```bash
make run-backend
```

## Run only frontend services

```bash
make run-frontend
```





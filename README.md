# spark platform

All Spark services started from a single repository

## Requirements
- [Taskfile](https://taskfile.dev/#/installation)
- [Docker](https://docs.docker.com/install/)
- [Docker Compose](https://docs.docker.com/compose/install/)


# How to run it with task command?
### Check if environment variables are set
```bash
task config
```

### Start All Services
```bash
task run
```
### Stop All Services
```bash 
task stop
```
### Restart All Services

```bash
task restart
``` 

### Logs

```bash 
task logs
```
### Status

```bash
task status
```

# How to run it with docker compose commands?

## dev
```
docker-compose -f docker-compose.dev.yml up -d
```



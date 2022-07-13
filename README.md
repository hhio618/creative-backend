# creative-backend
## Build using docker
### Setup Textile hub
1. Install the Textile hub cli using instructions in this (url)[https://docs.textile.io/hub/accounts/].
2. Generate API keys using instructions in this (url)[https://docs.textile.io/hub/apis/].
### Setup the env file
Copy env.example to `.env` and set the required env files obtained from the above step.
```
$ cp env.example .env
```
### Build using docker
```
$ docker build -t creative-backend:latest .
```
### Run it locally using docker-compose
```
$ docker-compose --env-file .env up -d
```

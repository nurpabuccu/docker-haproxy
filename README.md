# docker-haproxy
This project contains Flask python application and scale it using docker-compose and HAProxy.

The Flask application only returns a simple *Hello World!* response.

HAProxy acts as a load balancer

## How To Run
```bash
$git clone https://github.com/nurpabuccu/docker-haproxy
$cd docker-haproxy
$docker-compose up
```
Navigate to http://localhost:8000. HAProxy routes the requests balanced between services using round robin.

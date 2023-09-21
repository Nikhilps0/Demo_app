# Demo_app
Following application is devoloped for my friend.

In this application you can see 2 folder called

ipgeolocation-api-service
ipgeolocation-frontend

## The folder ipgeolocation-api-service contain the api service for the front end application.

Details need to setup api serivce container.


application is exposed to the port 8080
enviormental veriable for  the api service is-
APP_PORT="8080"
API_KEY="___"
Key you will able to get it free from the following.
https://ipgeolocation.io/
Redis is used for cache service.
Enviorment veriable for redis use in the API service are the following.
REDIS_PORT
REDIS_HOST


Once the API container is UP you will able to confirm it using the URL:- http://IP:8080/api/v1/8.8.8.8

## The Folder ipgeolocation-frontend contain the frond end application.

Detailes need to setup this app


Application running on the port 8080.
We need to map the API to this frond end app using the enviorment veriable.
Veriables are -
API_SERVER="IP/NAME of the API service"
API_SERVER_PORT="THE PORT YOU mapped above API service"
API_PATH="/api/v1" #use this once
APP_PORT="8080"

Once you setup the above container you will able to complete the project and can call the applicatio using the URL: http://IP:PORT/ip/8.8.8.8

:)



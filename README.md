# airport-application

- To run this application locally, clone this repo to your machine and do the command below:
```
cd airport-application
docker-compose up
```
## Testing endpoints

- Endpoint localhost/countries gets a full list of countries
- Endpoint localhost/airport get a full list of airports and their runways
- Nginx (endpoint - localhost) is used for reverse-proxy and/or load-balancer that exposes the services on port 80

## Running a new version of the application

- Update the jar file in the airports/ directory with the correct jar version i.e. airports-assembly-1.1.0.jar
- Then run:
```
docker-compose up
```

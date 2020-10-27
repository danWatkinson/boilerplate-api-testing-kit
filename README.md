project root

docker-compose file here to build everything. means we can separate out 'endpoints we need for our API' vs 'endpoints we need to test our API properly'; also means we're micro-service ready... dev-wise it's trivial to add another service.

scripts here to:
npm start: build + launch everything via docker-compose
npm test: build + launch everything via docker-compose, then run the API-tests against it

gives us easy e2e tests locally
can use github actions to wire up the CI to do all this on pull-request
hopefully the Dockerfiles are of use for deployment; ideally because we deploy a docker image but if not: at least it contains the build instructions...

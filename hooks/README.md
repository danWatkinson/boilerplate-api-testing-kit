endpoints that we wish we had for testing but don't want to actually release into the wild live here.

means we can write proper end-to-end tests, but we don't have to release every last dirty trick we do in order to do that into the public domain...


Dockerfile to build these hooks for us
 - means our CI process is literally "docker-compose up && [run API-tests]"

 

This simple DockerFile adds curl and bash to the base postgres:9.5-alpine image.
The purpose of this is to add the ability to use curl in a docker-compose environment so I can run scripts to check that other services are
up and running before a postgres database can start.

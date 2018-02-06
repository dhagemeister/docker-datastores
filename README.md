# Docker Datastores

This repo contains a `docker-compose.yaml` file that 
will start-up MongoDB and PostgreSQL in docker containers.
I expect this will be useful for development on the 
social todo assignments.

You run it like `docker-compose up` in the same directory
as the yaml file. This will automatically source any 
`.env` file you have in the directory. You'll want to 
specify some environment variables for PostgresSQL, otherwise
it will not function (or launch).

License: The Unlicense

# medsis
this project is a complete overhaul and rewrite of the original
medsistra project

## reason for rewrite
medsistra was originally a python flask app. however, in anticipation of
growth and in order to learn more modern technologies, the entire
project was rewritten in Golang and Typescript, implemented in Docker
with NGINX and Node + Next with Postgres as the database

### todo:
-write the initial golang http server
-write the initial react and next typescript pieces
-setup the nginx configuration
-ensure that the docker compose is using all the appropriate containers
-setup auth in golang
-create the templates for the different webpages so that they are
properly rendered and setup for Next
-setup the postgres db and ensure that an admin user is properly
configured
-deploy the entire project locally for dev testing

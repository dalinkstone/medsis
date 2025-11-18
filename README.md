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
--for the sake of testing the actual website, this should be the first
step so that i have some kind of html to render and then after having
the page and the layout, then i can start building out the backend
functionality to support this
-setup the nginx configuration
--the nginx configuration needs to be fleshed out some more, i think
that i am not using it to the best right now
-ensure that the docker compose is using all the appropriate containers
-setup auth in golang
-create the templates for the different webpages so that they are
properly rendered and setup for Next
-setup the postgres db and ensure that an admin user is properly
configured
-deploy the entire project locally for dev testing

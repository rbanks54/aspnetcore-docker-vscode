# Intentions

So my ultimate intentions for this are to be able to have the application running on port 5001 (example) - mapped to this directory, so re-building the solution automatically reflects when visiting http://localhost:5001 (like when pressing F5 in VS Code currently)

Also, other required containers (mysql, redis etc... for example) could also be running.  

Not sure how to be able to debug this running container.

Currently, if I run `docker-compose up -d` and visit http://localhost:5001 in the browser, I get `ERR_EMPTY_RESPONSE`
So I'm certainly doing something wrong!
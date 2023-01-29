To build, open a terminal in this directory and execute...
`docker build -f Dockerfile .. -t ctnelson1997/cs571-s23-hw2-api`

To run, open a terminal in any directory and execute...
`docker run --restart=always -d -p 25402:25402 --name cs571-s23-hw3-api ctnelson1997/cs571-s23-hw2-api:latest`
Note that you can change the beginning port number to any open port.

To view logs, open a terminal in any directory and execute...
`docker ps` (if the container is down, execute `docker ps -a`)
Find the container id (in this case, for `cs571-s23-hw2-api`) and execute...
`docker logs {CONTAINER_ID_HERE}`
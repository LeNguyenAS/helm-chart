# Docker compose sample

**How to run:**
* cd example/chapter8
* Build service:
    * `docker-compose build`
* Pull image:
    * `docker-compose pull`
* Up Service
    * `docker-compose up`
* After building successfuly, to list the containers associated with the example docker-compose project
  * `docker-compose ps`
* Explore the functionality of our own request/response web application on a different Terminal of the Docker host, as illustrated here:
  * `curl http://localhost:8080`
* To stop containers:
  * `docker-compose stop`

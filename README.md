
# drone-server
This section provides basic instructions for installing Drone using docker-compose. The below configuration can be used to start the Drone server with multi-agent.

### Dependencies
- [x] [Drne CI](https://github.com/drone/drone)
- [x] [Docker](https://www.docker.com/)
- [x] [Docker Compose
](https://docs.docker.com/compose/)

# Environment Variables Setting
* `copy .env.example .env `

# Start containers 
Start the containers in the background and leaves them running.
* `docker-compose up -d`

## Stops containers
Stops running containers without removing them
* `docker-compose stop `

## Stop and remove containers
Stops containers and removes containers, networks, volumes, and images created by up
* `docker-compose down `

## Log watching containers
Displays log output from services.
* `docker-compose logs -f`

# Command login drone server
```
$ export DRONE_SERVER=http://localhost/
$ export DRONE_TOKEN={YOUR_TOKEN}
$ drone info
User: cutedogspark
Email: cutedogspark@gmail.com
```

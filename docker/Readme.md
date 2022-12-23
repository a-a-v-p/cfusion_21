Switch into the docker directory and execute 

-Deploy with docker-compose:
docker-compose up -d

-Build command:
docker-compose -f docker-compose.yml up -d --build

-Run command:
docker-compose -f docker-compose.yml up -d
docker-compose -f docker-compose.yml logs -f

-List of containers:
docker ps

-List of images:
docker image ls

-Stop and remove the containers (note: not image):
$ docker-compose down
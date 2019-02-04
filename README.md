Warning ! it is imperative that ports 3000 and 4200 be available otherwise you have problems.

to launch the project :
docker stack deploy -c docker-compose.yml project-connection-test

to stop the project :
docker stack rm project-connection-test

url front-end (angular) :
http://localhost:4200/

url back-end (nodeJS) :
http://localhost:3000/

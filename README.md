# Dockerize-Apache-Webserver
Deploying Webserver using Dockerfile 

![Docker Architecture](https://github.com/VardhanLearn/Dockerize-Apache-webserver/assets/87961252/b1319a2f-9584-4fcd-95fb-5ab2699c7217)

PreRequisite:

1. EC2 server with UbuntuOS
2. Access terminal with pemfile & change to root user
3. Install docker with docker.io
4. Make docker directory (mkdir docker) -> cd docker -> create dockerfile
5. Run the docker file with command docker build -t "imagename"
6. check the docker container ls to see docker file exuted or error thrown
7. ![command 1](https://github.com/VardhanLearn/Dockerize-Apache-webserver/assets/87961252/12bd65fa-0cf8-47a7-8a1d-02d7bc518f45)

8. Create docker container & run this command docker run -p 80:80 "imagename"
9. Run local host on web browser
10. ![Webserver deployed](https://github.com/VardhanLearn/Dockerize-Apache-webserver/assets/87961252/c1b97fe9-3858-48ce-88cf-8d45de1b6641)

  

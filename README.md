# SoftwareAcademy-P9-SpringAdmin-Server

# Installation
todo
## Docker installation
###Docker image construction in project directory :

docker build --build-arg JAR_FILE=target/*.jar -t p9-spring-admin .

### Docker execution :

docker run -p 9105:9105 --name SpringAdmin p9-spring-admin

### Check Eureka server
* http://localhost:9102/

# Camunda8Compose
#To be able to use this with ARM64 support, run the following command to build your own container of Keycloak/Bitnamni:  

$ DOCKER_BUILDKIT=0 docker build -t bitnami/keycloak:19.0.3 "https://github.com/camunda/camunda-platform.git#main:.keycloak/"

Then:  
docker-compose up -d

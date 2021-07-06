# spring-docker

Exemplo de uma aplicação simples feita em spring para subir ao docker hub

Para fazer o build da imagem:
docker build --build-arg JAR_FILE=build/libs/*.jar -t kalilventura/spring-boot-docker:v1 .

Para executar a imagem:
docker run --name spring-boot-docker -d -p 8081:8081 kalilventura/spring-boot-docker:latest

Link do docker hub da imagem:
https://hub.docker.com/repository/docker/kalilventura/spring-boot-docker
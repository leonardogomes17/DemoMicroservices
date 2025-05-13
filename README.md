DEFAULT WEBAPI PROJECT + DOCKER

Docker --version
Em caso de erro WSL : wsl --update
echo . > Dockerfile (Criar arquivo Docker)
Docker build -t PROJECTNAME .
Docker images (Nome da imagem)
Docker container run -it --rm -p 3000:80 --name NOMECONTEINER NOMEIMAGEM

Docker container run -it --rm -p 3000:80 --name democonteiner demomicroservice
OR POR 3000:8080


REMOVE
Docker image rm AAAAA (5 PRIMEIRAS LETRAS DO NOME)

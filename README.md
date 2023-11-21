# DockerFileExample
Este projeto é um simples arquivo com Dockerfile subindo uma maquina debian e uma imagem nginx. 


Para buildar a imagem, rode = docker build -t nome-imagem/nginx:1.0

Para rodar a imagem em segundo plano = docker run --name teste -p 80:80 -d nome-imagem/nginx:1.0

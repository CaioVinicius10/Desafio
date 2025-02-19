# Desafio DevOps

1. Criar o Dockerfile para o projeto e tentar iniciar ele localmente.

    ## Comanandos auxiliares ##
        docker build -t nome_da_imagem .
        docker push nome_do_repositorio
        docker pull nome_do_repositorio
        docker container ls
        docker images


2. Criar conta no DockerHub e enviar a imagem apos ser validada o funcionamento, o dockerhub vai funcionar como repositorio remoto para armezenar as imagens apos ocorrer o Build.
    Link para criar conta no DockerHub: https://hub.docker.com/ 


OBS: Esse projeto é em python e estamos usando o Flask para auxiliar na construção do Dockerfile.
# NGINX com docker-compose.yml

A pasta nginx_config contém o arquivo de configuração do NGINX, sinta-se a vontade para alterá-lo.

# Fazendo funcionar
(para funcionar precisa ter o docker e o docker compose instalados)

1. Clone a branch com o comando:
```
git clone -b nginx --single-branch git@github.com:leonardocroda/initial-docker-compose-files.git
```
2. No arquivo docker-compose.yml, altere o valor de volumes, substituindo ./dist pela pasta do seu projeto
3. Execute o comando:
```
docker-compose up -d 
```
4. Abra o browser e navegue para http://localhost:8080, o seu site deve carregar.

# Escreva sua Documentação AQUI!!!

Criei o arquivo Dockerfile, criei o diretório, copiei as dependencias, instalei elas, e por fim copiei o restante da api

# Obs: Encontrei um erro ao executar as primeiras vezes, troquei o psycopg2 para psycopg2-binary e atualizei para a última versão, assim, parou os erros e rodou certinho.

No docker-compose.yml defini o .env com as variáveis e rodei a api na porta 5000, rodei também o container com o postgres logo em seguida, definindo a imagem e as variáveis.

Para rodar tudo é só digitar no terminal docker-compose up

Para testar a api, vamos no navegador e entramos inserimos o endereço localhost:5000
Para testar o banco, podemos usar o pgAdmin e logar no db com as credenciais disponíveis no arquibo .env

A imagem para teste está disponível no DockerHub:
https://hub.docker.com/repository/docker/otaviomartins/desafio-devops
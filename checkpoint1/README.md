##Adicionando instruções:

Comando "docker" para executar a aplicação a partir do docker hub do respectivo membro com profile "dev"
docker run -d -p 8080:8080 -e PROFILE=<dev> ping

Comando "docker" para executar a aplicação a partir do docker hub do respectivo membro com profile "stg"
docker run -d -p 8080:8080 -e PROFILE=<stg> ping

Comando "docker" para executar a aplicação a partir do docker hub do respectivo membro com profile "prd"
docker run -d -p 8080:8080 -e PROFILE=<prd> ping

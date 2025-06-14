# ds-mongodb

## Passos
- 1 - rodar o docker compose `docker compose up --build`
- 2 - instalar IDE de sua preferencia (mongo db compass)
- 3 - conectar via uri de conexao `mongodb://root:example@localhost:27017/?authSource=admin`

## IDEs recomendadas
- MongoDB Compass (GUI oficial, fácil de usar)
- NoSQLBooster (avançado, mas tem versão gratuita)
- Robo 3T (leve e popular)

## Dados de conexao 
- Host: localhost
- Porta: 27017
- Usuário: root
- Senha: example
- Database: contratacao

## Visualizando logs nos container 

`docker logs mongo_db`

## Executando via docker 
`docker exec -it mongo_db mongosh -u root -p example --authenticationDatabase admin` 

## Acessando via nuvel 
1 - acesse o atlas 
2 - logue com a conta do email
3 - use o cluster ou cre o cluester M0 free
4 - conecte com ele na sua ide compass
5 - pronto

## Referencias 

- https://www.mongodb.com/docs/manual/reference/method/db.collection.insertOne/ 
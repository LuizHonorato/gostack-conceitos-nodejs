# Desafio 02 Rocketseat
Segundo desafio do bootcamp GoStack 12 da Rocketseat: Utilizar conceitos fundamentais do NodeJS na criação de uma API para cadastro de repositórios fake.

## Conceitos
### API REST
Interface de comunicação padronizada entre um sistema e diversos clientes que podem consumir este sistema. Retorna estruturas de dados bem definidas como arrays e json's.

### Métodos HTTP
Cada requisição feita para uma API possui um método e indica uma ação destinada a um recurso. São eles:

GET - Lista recursos.

POST - Cria novos recursos.

PUT - Atualiza recursos.

DELETE - Deleta recursos.

### Parâmetros da Requisição
São informações enviadas na requisição e o back-end lida com elas:

Route params: Parâmetros enviados nas rotas.

Query Params - Parâmetros normalmente utilizados para filtros/paginação.

Body: Conteúdo/Corpo da requisição.

### Middlewares
Interceptam as requisições e podem pará-la ou manipular os dados enviados nela. Podem ser atríbutas a uma rota específica ou a várias. Todo o NodeJS é baseado em middlewares e trabalha com os conceitos de request, response e next (no caso dos middlewares).

# Integração com APIs

Resumo dos meus estudos iniciais sobre integração com APIs e comunicação entre sistemas.

## Conceitos principais

API é uma forma de comunicação entre sistemas. Ela permite buscar, enviar, atualizar ou remover informações usando requisições.

## Pontos estudados

* URL base e endpoint
* Métodos HTTP: GET, POST, PUT/PATCH e DELETE
* Request e response
* Dados em formato JSON
* Headers e body
* Query parameters
* Autenticação com API Key e Bearer Token
* Status codes como 200, 201, 400, 401, 403, 404 e 500

## Exemplo de lógica

Uma integração pode enviar dados de um sistema para outro usando uma requisição HTTP.

Exemplo:

```text
Método: POST
Endpoint: /clientes
Headers: Content-Type: application/json
Body: dados do cliente em JSON
```

## Objetivo do estudo

Entender a lógica básica de consumo e integração com APIs prontas, principalmente para uso em automações e troca de dados entre sistemas.

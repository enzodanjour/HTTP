# HyperText Transfer Protocol

- Protocolor de transferência de Hypertextos

## Visão geral

- Permite a troca de dados na internet
- Uma troca de mensagens
- HTML,CSS,JS,IMGS, VIDEO
- Uma chamada para cada recurso

## Request(Browser) <-> Response(Server)

### Request

Pedir ao servidor algo

#### Methods

Definição do tipo do pedido, qual é a finalidade da requisição.
Get:Pegar algo
Post: criar um recurso.

### Response
o servidor retorna algo 

#### Status code

resposta do servidor sobre o estado do pedido/resposta.

200: chegou o pedido.
301: redirecionamento do pedido.
404: não encontrado.
500: erro de servidor.

### Request/Response

#### Headers

Campos informativos, com valores(propriedade:valor)
exemplo:
``Content-Type:application/json``
``User-Agent:Chrome``
``Request-Url:www.google.com``

#### Body

Html, conteúdo, JSON

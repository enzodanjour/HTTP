# methods

 Define um conjunto de métodos http, pode ser chamados de verbos, cada um possui sua semântica.

## Características

### Seguro

- não altera o estado do servidor
- somente leitura
- client não solicita alterações
- não há carga extra para o servidor
- o servidor é responsável por manter o método seguro

métodos.
get, head, options.

### Idempotente

- Ao executar o método, a resposta será sempre a mesma.
quais são:
todos os seguros, put, delete

- status code poderá ser diferente
- o servidor tem a responsabilidade de retornar dados da mesma maneira
- Essa especifição não é garantia que os servidores irão aplicar o conceito corretamente

## Options

- informa sobre a disponibilidade da requisição.
seguro:
idempotente:sim
body
- request:não
- response: não
uso em formulários html:não
cacheável:não


``curl -X OPTIONS http://localhost:3000/posts/ -i``

``HTTP/1.1 204 No Content`
`X-Powered-By: Express`
Vary: Origin, Access-Control-Request-Headers
Access-Control-Allow-Credentials: true
Access-Control-Allow-Methods: GET,HEAD,PUT,PATCH,POST,DELETE
Content-Length: 0
Date: Tue, 27 Apr 2021 13:15:39 GMT
Connection: keep-alive``

## GET

pegar um recurso, e recebe.

seguro:sim

idempotente:sim

body
- request:não
- response: sim

uso em formulários html:sim, dependendo do formulário

cacheável:sim, pois podem existir várias perguntas.

``curl -v http://localhost:3000/posts``

```bash=
 GET /posts HTTP/1.1
 Host: localhost:3000
 User-Agent: curl/7.68.0
 Accept: */*
 ```
 
``` Mark bundle as not supporting multiuse
< HTTP/1.1 200 OK
< X-Powered-By: Express
< Vary: Origin, Accept-Encoding
< Access-Control-Allow-Credentials: true
< Cache-Control: no-cache
< Pragma: no-cache
< Expires: -1
< X-Content-Type-Options: nosniff
< Content-Type: application/json; charset=utf-8
< Content-Length: 77
< ETag: W/"4d-49G7XbVRP2NKipc5uj9Z4hcUq3Y"
< Date: Tue, 27 Apr 2021 13:33:35 GMT
< Connection: keep-alive
< 
[
  {
    "id": 1,
    "title": "json-server",
    "author": "typicode"
  }
```

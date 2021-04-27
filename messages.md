# messages

Request e response temos mensagens,
Http/1.1 legível e texto
Http/2 estrutura binária, otimizações, mesma maneira que a versão 1.1
``https://github.com/typicode/json-server``
excelente repo

## Request

### Request Line

é o pedido que fazemos ao servidor

- method, um verbo que diz a intenção do pedido
- protocol version
- uri

comando verificando requisições
``curl -v https://google.com``

``> GET /HTTP/2``
``> Host: www.google.com``
```> user-agent: curl/7.68.0```
```> accept: */*```

### Body

### Headers

## Response

``HTTP/2 200``
``content-type: text/html; charset=ISO-8859-1``
``p3p: CP="This is not a P3P policy! See g.co/p3phelp for more info."``
``date: Tue, 27 Apr 2021 12:21:44 GMT``
``server: gws``
``x-xss-protection: 0``
``x-frame-options: SAMEORIGIN``
``expires: Tue, 27 Apr 2021 12:21:44 GMT``
``cache-control: private``
``set-cookie: 1P_JAR=2021-04-27-12; expires=Thu, 27-May-2021 12:21:44 GMT; path=/; domain=.google.com; Secure``
``set-cookie: NID=214=J3pswikYac4iorNHcvzITX4WHMBy_hvofXHTb6thMNk5rl1hBp0d4IsMXq_OcVSBu5w9dnwx22CVtI8YDaV3RZhHkVtjrce8xmXKAfhRNP1grTGFvYYoqUj4gwIPXUJyrgfVVoLPSSZ3EEVTFvIZFWcySvOKQflAhHJsRTZ19p4; expires=Wed, 27-Oct-2021 12:21:44 GMT; path=/; domain=.google.com; HttpOnly``
``alt-svc: h3-29=":443"; ma=2592000,h3-T051=":443"; ma=2592000,h3-Q050=":443"; ma=2592000,h3-Q046=":443"; ma=2592000,h3-Q043=":443"; ma=2592000,quic=":443"; ma=2592000; v="46,43"``

### Protocol version

``HTTP/2``

### Headers

parâmetros iniciais

``content-type: text/html; charset=ISO-8859-1``
``p3p: CP="This is not a P3P policy! See g.co/p3phelp for more info."``
``date: Tue, 27 Apr 2021 12:21:44 GMT``
``server: gws``
``x-xss-protection: 0``
``x-frame-options: SAMEORIGIN``
``expires: Tue, 27 Apr 2021 12:21:44 GMT``
``cache-control: private``
``set-cookie: 1P_JAR=2021-04-27-12; expires=Thu, 27-May-2021 12:21:44 GMT; path=/; domain=.google.com; Secure``
``set-cookie: NID=214=J3pswikYac4iorNHcvzITX4WHMBy_hvofXHTb6thMNk5rl1hBp0d4IsMXq_OcVSBu5w9dnwx22CVtI8YDaV3RZhHkVtjrce8xmXKAfhRNP1grTGFvYYoqUj4gwIPXUJyrgfVVoLPSSZ3EEVTFvIZFWcySvOKQflAhHJsRTZ19p4; expires=Wed, 27-Oct-2021 12:21:44 GMT; path=/; domain=.google.com; HttpOnly``
``alt-svc: h3-29=":443"; ma=2592000,h3-T051=":443"; ma=2592000,h3-Q050=":443"; ma=2592000,h3-Q046=":443"; ma=2592000,h3-Q043=":443"; ma=2592000,quic=":443"; ma=2592000; v="46,43"``

### Status code

deu tudo certo com a request?
``200``

### Status message
 verá em breve
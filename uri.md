# Uri

Uniform Resource Identifier(identificador de maneira uniforme): identificar um recurso pelo nome ou localização.
Exemplo, domínio/ip

## Recurso

Pedido do alvo, para onde está indo.
qualquer coisa identificável/entidade:
-Digital: email
-Abstrata: sessão/ autenticação
-Fisicos: Produtos/ usuários

Se podemos identificar, nomear, manipular ou endereçar, estamos falando de um recurso.

## Locator

Url, uniform resource Locator(``https://youtu.be/qnYSx-SQXiI?t=1658``)
Componentes:

### Obrigatórios

- protocolo.
- Domínio.

```https://google.com```

### Opcionais

- Subdominio: vem antes do domínio
``www``
- Path:caminho
``/blog``
- Parâmetros: recursos adicionais.
``?t=1658``
- Porta: caminho de algum recurso específico, alguns momentos a porta está fechada, no http quando não declaro, a porta implícita é a 8080, no https, a porta implicita é a 443, manualmente abrir umas portas.
``http://*127.0.0.1:3333*/index.html#algumlugar``
- âncora: algo em específico dentro do documento
``http://127.0.0.1:3333/index.html*#algumlugar*``

## Nome(urn)

Uniforme Resource Name

### Exemplo

``urn:isbn:0451450523``/ localização de um livro
``urn:oasis:names:specification:docbook:dtb:xml:4.1.2``

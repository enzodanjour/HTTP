# How works internet

## Você digita a URL ``https://endereco.com``

- URL:
-HTTP(Hypertext Transfer Protocol): trocar mensagens entre os computadores, mensagem é quebrada em diversos pedaços(chunks)

## É iniciada uma linha de comunicação, através do protocolo TCP, entre seu computador(client) até o computador que tem a página(servidor)

- Client(browser):Computador que fez o pedido
- servidor: computador configurado para receber os pedidos e enviar respostas aos pedidos.
- tcp(transmission control protocol): garantir que os pacotes cheguem corretamente ao destino.

## O endereço é convertido em um ip(76.76.21.21) através do dns

-ip(internet protocol): endereçamento dos computadores
-dns(domain name server): converter um domínio em um endereço IP

## seu pedido está percorrendo diversos proxies

- Proxy(qualquer dispositivo no meio do caminho): roteador, modem, outros computadores, função encaminhamento dos pacotes.

## meu pedido chega até o servidor

## servidor analisa o pedido e te dá uma resposta,caso positivo

## O caminho de volta é semelhante ao de ida, passando pela linha de comunicação que foi criada

## O browser recebe os pedaços e monta a tela do site para você

## esse percurso acontece muitas vezes, pois para cada recurso(html,css,js,img) é feita uma nova requisição

## Curl

funciona como analise da requisição mais aprofundada.
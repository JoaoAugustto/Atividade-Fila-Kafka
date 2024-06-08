### Kafka ### 

### Pré-requisitos ###

Docker instalado

Como instalar?

Baixe o código do repositório.
Abra o terminal no diretório onde o código foi baixado.

## Execute o comando: ##

Copiar código
 ``` "docker-compose up" ```
 
### Como usar? ###

O produtor (producer) estará disponível na porta 8080 do seu computador, acessível pela rota /produce em http://localhost:8080/produce.

Para enviar uma mensagem, faça uma requisição POST para essa rota com o seguinte formato:

json
Copiar código
```
{
  "message": "Sua mensagem"
}
```
Visualização do Log
Os logs do consumidor (consumer) estarão disponíveis diretamente no terminal onde o comando docker-compose up foi executado.

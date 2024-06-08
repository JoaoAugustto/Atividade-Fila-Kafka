# Exemplo de fila KAFKA

### Dependências: Docker

### Como instalar?

Baixe o código deste repositório, abra o terminal e rode o comando "docker-compose up"

### Funcionamento:

O producer ficará disponível na porta 8080 do seu computador com a rota "produce" "http://localhost:8080/produce"

Envie a seguinte requisição
``` 
{
  "message": "Sua mensagem" 
}
```

O log do consumer estará disponível no seu terminal

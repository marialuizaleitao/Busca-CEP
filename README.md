# Busca-CEP

Um simples programa em Go que consome a API ViaCEP do IBGE para retornar informações sobre um CEP fornecido. O programa faz uma requisição HTTP para a API, analisa a resposta JSON e exibe os detalhes do CEP.

## Funcionalidades
- Consumo da API ViaCEP para buscar informações de um CEP.
- Exibição de detalhes como logradouro, bairro, localidade, UF, entre outros.

## Como usar
Para executar o programa, forneça a URL da API com o CEP desejado como argumento. Exemplo:

```sh
go run main.go https://viacep.com.br/ws/{cep}/json/
```

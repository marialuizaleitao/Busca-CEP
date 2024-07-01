# Busca-CEP

Um simples programa em Go que consome a API ViaCEP do IBGE para retornar informações sobre um CEP fornecido. O programa faz uma requisição HTTP para a API, analisa a resposta JSON e exibe os detalhes do CEP. Além disso, os logs das buscas são armazenados em um arquivo de texto.

## Funcionalidades
- Consumo da API ViaCEP para buscar informações de um CEP.
- Exibição de detalhes como logradouro, bairro, localidade, UF, entre outros.
- Armazenamento dos logs de busca em um arquivo de texto.

## Como usar
Para executar o programa, forneça o CEP desejado como argumento. Exemplo:

```sh
go run main.go 30260-070
```
Isso buscará as informações do CEP 30260-070 na API ViaCEP e armazenará os detalhes no arquivo cidade.txt.

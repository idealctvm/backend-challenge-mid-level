# Backend | Desafio Técnico

## Introdução

Este projeto tem como objetivo descrever o desafio de código para candidatos que queiram se aplicar para vaga de desenvolvedor backend na Ideal CTVM.

## Objetivo

O objetivo do desafio será escrever uma API Web que possibilita aos usuários criarem sua lista de acompanhamento de ativos para posterior consulta de suas cotações (preço do ativo). Esta API será utilizada pelo time de front-end na criação de uma tela bem bacana para disponibilizarmos a funcionalidade em nosso site.

## Estórias

### 1. Usuário adiciona um ativo em sua lista de acompanhamento.

O usuário poderá adicionar qualquer ativo válido em sua lista de acompanhamento para posterior consulta.

Exemplos de ativos:

```
PBR, APPL, GOGL
```

### 2. Usuário ordena sua lista de acompanhamento.

O usuário poderá ordenar sua lista de acompanhamento de três formas:
1. Ordem alfabética (Ativo)
2. Preço do ativo
3. Colocar o ativo na posição em que preferir

### 3. Usuário consulta sua lista de acompanhamento.

O usuário poderá consultar a sua lista de acompanhamento, a qual deverá retornar os ativos adicionados juntamente com a sua respectiva cotação, ordenados de acordo com suas preferências.

### 4. Usuário consulta a cotação de um ou mais ativos.

O usuário poderá consultar a cotação de um ou mais ativos, mesmo ele(s) não fazendo parte da sua lista de acompanhamento.


## Provedor de Cotações

Para a conclusão do desafio, você poderá utilizar a API de cotações do [Yahoo! Finance](http://yahoofinanceapi.com) ou qualquer outra de sua preferência (inclusive de criptomoedas, se assim preferir). 

Exemplo de chamada da API do Yahoo! Finance:

``` 
curl -X 'GET' \
  'https://yfapi.net/v6/finance/quote?region=US&lang=en&symbols=AAPL' \
  -H 'accept: application/json' \
  -H 'X-API-KEY: [xxxxx SUA API KEY xxxxxx]'
```

Essa requisição retorna o preço da APPL (Apple).

## Regras

* API deve ser implementada usando REST, GraphQL ou gRPC
* Use a linguagem de programação na qual tenha mais experiência/se sinta confortável
* Nomes de variaveis, métodos, classes/estruturas e comentários devem ser feitos em inglês
* Não há restrições com relação a soluções de armazenamento de dados
* Adicione o README.md no seu repositório

## O que iremos focar ao analisar o seu código?

* Qualidade do código
  * Organização de código e legibilidade
  * Principios SOLID
  * Design patterns (se aplicável)
* Proatividade em fazer perguntas, pesquisas e tomada de decisões
* Histórico de commits no repositório

## Bônus

* Unit tests
* Utilização de container docker
* Mecanismo de autenticação e autorização
* Desenvolvimento da API utilizando a linguagem Golang

## Entrega

O código do desafio deverá estar publicado em um repositório **privado** no GitHub. O usuário ```fandradesantos```  deve ser adicionado ao repo para visualização do código.

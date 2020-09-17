## :rocket: Bootcamp Rocketseat - Desafio 02: 

### Para execução do projeto:

Na raiz do projeto,instale os módulos de dependencia:
#### `yarn`

Execute o projeto:
#### `yarn start`


### Desafio: Conceitos do ReactJS
Nesse desafio, você deve criar uma aplicação para treinar o que você aprendeu até agora no Node.js! 

![image](https://user-images.githubusercontent.com/43305891/93405179-b081c700-f862-11ea-8d98-aea17e896799.png)

A porposta deste desafio era utilizar o framework express, a biblioteca uuid para geração de chave única e salvar em uma variável repositórios


#### `get('/repositories')`
Lista todos os repositórios cadastrados na variável.

#### `post('/repositories')`
Adiciona um novo repositório na lista de repositórios.

#### `put('/repositories/:id')`
Atualização dos dados de um repositório passando o id como chave de identificação

#### `delete('/repositories/:id')`
Deletar um repositório da listagem passando como chave o id do repositório.

#### `post('/repositories/:id/like')`
Possibilita que seja adicionado um like no repositório ao qual foi passado o id.

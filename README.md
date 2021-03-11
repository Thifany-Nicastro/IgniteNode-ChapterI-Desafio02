# Desafio 02 - Trabalhando com middlewares :rocket: :purple_heart:

## :dart: Objetivo

Adicionar o tipo de plano do usuário no desafio anterior por meio de middlewares.

## :white_check_mark: Requisitos

### Middlewares
- [x] checksExistsUserAccount
- [x] checksCreateTodosUserAvailability
- [x] checksTodoExists
- [x] checksTodoExists

### Específicação dos testes
- [ ] Should be able to find user by username in header and pass it to request.user
- [ ] Should not be able to find a non existing user by username in header
- [ ] Should be able to let user create a new todo when is in free plan and have less than ten todos
- [ ] Should not be able to let user create a new todo when is not Pro and already have ten todos
- [ ] Should be able to let user create infinite new todos when is in Pro plan
- [ ] Should be able to put user and todo in request when both exits
- [ ] Should not be able to put user and todo in request when user does not exists
- [ ] Should not be able to put user and todo in request when todo id is not uuid
- [ ] Should not be able to put user and todo in request when todo does not exists
- [ ] Should be able to find user by id route param and pass it to request.user
- [ ] Should not be able to pass user to request.user when it does not exists

## :computer: Instalação ##

```bash
# Clone este repositório
$ git clone https://github.com/Thifany-Nicastro/IgniteNode-Desafio02.git

# Entre na pasta
$ cd IgniteNode-Desafio02

# Instale as dependências
$ yarn ou yarn install

# Execute a aplicação em modo de desenvolvimento
$ yarn dev

# O servidor inciará na porta:3333
acesse <http://localhost:3333>
```
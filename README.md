## Escola de Software - Usuários - API Gateway

Esse repositório contém a API gateway do microserviço de usuários da escola de software.

# Rotas disponíveis

- POST /usuarios

Cria um novo usuário na escola de software, caso já exista, nada será feito. Essa rota deve ser utilizada para a criação de um *novo* usuário.

Body:
- email: string, required
- nome: string, required
- sobrenome: string, required
- cpf: string, required
- senha: string, required

- PUT /usuarios

Atualiza um usuário na escola de software, apenas se existir. Não é possível atualizar o e-mail ou a senha por essa rota. Pois se destina apenas aos dados do cliente.

Body:
- email: string, required
- nome: string, required
- sobrenome: string, required
- cpf: string, required

# Infraestrutura criada

O repositório cria toda a infraestrutura do API Gtw e também as permissões de Invoke para cada lambda que será utilizada.

Obrigado

<hr/>

## Escola de Software - Users - API Gateway

This repository contains the API Gateway of users microservice of escola de software.

# Available routes

- POST /usuarios

Create a new user on escola de software, if user already exists, nothing will be done. Use this route to create a *new* user.

Body:
- email: string, required
- nome: string, required
- sobrenome: string, required
- cpf: string, required
- senha: string, required

- PUT /usuarios

Update a user on escola de software, only if user exists. This route do not update email or password.

Body:
- email: string, required
- nome: string, required
- sobrenome: string, required
- cpf: string, required

# Infraestrutura criada

The repository create all the infrastructure of the API Gateway plus the policies for invoke lambdas.

Thanks a lot
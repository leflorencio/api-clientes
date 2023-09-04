# API Clientes

<p align="center">Projeto responsável pelo registro de clientes em um banco de dados, respeitando os fundamentos do REST FULL.</p>

### Features

### Cadastro de clientes 
Recebe uma solicitação de criação de um novo cliente (Solicitação via HTTP POST).
Valida os dados do cliente.
Se os dados forem válidos:
Crie um novo registro de cliente no banco de dados.
Retorne uma resposta de sucesso.
Se for invalido: 
Retorna uma reposta informando que os dados precisam ser válidos. 

### Listar clientes
Recebe uma solicitação para ler informações de uma página de clientes (Solicitação HTTP GET com um Pageable).
Consulta o banco de dados para obter os detalhes do cliente.
Se existir registro de clientes:
Retorne a quantidade de registro informado na paginação com os dados dos clientes.
Se não existir registro:
Retorne uma resposta indicando que não foi encontrado.

### Listar cliente por ID
Receba uma solicitação para ler informações de um cliente (Solicitação HTTP GET com um ID de cliente).
Consulte o banco de dados para obter os detalhes do cliente.
Se o cliente existir:
Retorne as informações do cliente na resposta.
Se o cliente não existir:
Retorne uma resposta indicando que o cliente não foi encontrado.

### Deletar
Receba uma solicitação para excluir um cliente (Solicitação HTTP DELETE com um ID de cliente).
Verifique se o cliente existe no banco de dados.
Se o cliente existir:
Altera o status do cliente para Inativo no banco de dados.
Retorne uma resposta de sucesso.
Se o cliente não existir:
Retorne uma resposta indicando que o cliente não foi encontrado.

### Atualizar 
Recebe uma solicitação de atualização das informações de um cliente (Solicitação HTTP PUT com um ID de cliente).
Valide os dados atualizados do cliente.
Se os dados forem válidos:
Atualize o registro do cliente no banco de dados.
Retorne uma resposta de sucesso.
Se for invalido: 
Retorna uma reposta informando que os dados precisam ser válidos. 


### 🛠 Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

Java 17 - Spring Boot - API Docs - H2 Database - 





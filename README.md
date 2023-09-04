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


# ProjetoESOF2
## Sistema de Controle de Despesas

### Domínio do Projeto

O sistema simples de finanças pessoais e tem como objetivo permitir que um usuário:

* Cadastre receitas e despesas
* Visualize seu saldo 
* Consulte suas transações
* Tenha uma aplicação organizada em microserviços independentes

### Escopo do Projeto
* Funcionalidades Implementadas (MVP)
* Cadastro de usuários
* Cadastro de transações (receita/despesa)
* Listagem de transações
* Cálculo do saldo
* Interface web consumindo as APIs

### Metodologia — Scrum
 #### Product Backlog
- Cadastro de usuários
- Cadastro de transações
- Cálculo de saldo
- Criação do front-end
- Dockerização dos serviços

### Requisitos Funcionais

- RF01	O sistema deve permitir cadastrar usuários
- RF02	O sistema deve permitir cadastrar receitas
- RF03	O sistema deve permitir cadastrar despesas
- RF04	O sistema deve listar todas as transações
- RF05	O sistema deve calcular o saldo 
- RF06	O front-end deve consumir os dados das APIs

### Requisitos Não Funcionais

- RNF01	O sistema deve ser dividido em microserviços
- RNF02	Cada serviço deve rodar em um container Docker
- RNF03	A comunicação deve ocorrer via HTTP/JSON
- RNF04	O sistema deve ser simples e didático 
- RNF05	O sistema deve rodar localmente com um único comando

### Tecnologias Utilizadas
* Node.js — Back-end
* Express — API REST
* Docker — Containerização
* HTML, CSS e JavaScript — Front-end


<img width="876" height="750" alt="Diagrama caso de uso" src="https://github.com/user-attachments/assets/427121d7-5a91-4e4b-b700-620523db4d82" />


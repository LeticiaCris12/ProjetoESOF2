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

<img width="752" height="600" alt="Diagrama de classes" src="https://github.com/user-attachments/assets/ef4963ae-3187-4750-8d35-ccaa4c9b34fd" />

### Diagrama de Sequencia
<img width="1408" height="862" alt="mermaid-diagram" src="https://github.com/user-attachments/assets/dde712f1-123c-4c02-b062-95f0744e91ca" />

### Diagrama de Componentes
<img width="1229" height="396" alt="mermaid-diagram (1)" src="https://github.com/user-attachments/assets/37bfb9ec-49e5-4ef6-804e-870c181b549a" />

### Diagrama de Deployment
<img width="1305" height="538" alt="mermaid-diagram (2)" src="https://github.com/user-attachments/assets/a2a59194-22fa-4024-8bdc-3f20dd59b4dc" />

### Diagrama de Atividades
<img width="832" height="1241" alt="mermaid-diagram (3)" src="https://github.com/user-attachments/assets/ebbb2c26-bdd8-4665-ba77-71a0a21537f5" />

### Diagrama de Containers
<img width="1723" height="536" alt="mermaid-diagram (4)" src="https://github.com/user-attachments/assets/80ac770f-d13f-4567-8955-fb7c8fef9448" />


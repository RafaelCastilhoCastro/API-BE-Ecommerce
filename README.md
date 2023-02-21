# Lab-Ecommerce-Backend

### API para a manipulação de dados armazenados em banco de dados MySQL.

:green_book: [Link para a Documentação da API](https://documenter.getpostman.com/view/22376211/2s8Yt1tpoR)

:satellite: [Link do Deploy no Render](https://lab-ecommerce-backend.onrender.com)

### Como usar
- Clone o repositório
- Rode npm i (ou equivalente) para instalar as dependências
- Crie um arquivo .env na raiz do projeto e preencha os parâmetros:
    - Dados do seu bando de dados
        - DB_HOST=""
        - DB_USER=""
        - DB_PASSWORD=""
        - DB_DATABASE=""
- Rode npm run migrations para criar as tabelas no banco de dados (MySQL).
- Teste os endpoints através do arquivo request.rest, Postman ou equivalente.

### Dependências utilizadas:
* Knex
* Express
* ts-node-dev
* Cors
* Typescript
* dotenv
* MySQL

### Endpoints disponiveis:
- Buscar todos os usuários cadastrados (com seus históricos de compras)
- Buscar todas as compras de um determinado usuário
- Buscar todos os produtos cadastrados
- Adicionar usuário
- Adiciona produto
- Registrar compra

---

💻 Desenvolvedor: **Rafael Castro**.

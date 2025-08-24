# Projeto Vendas Mensais

Este projeto é uma API RESTful desenvolvida em Node.js com Express e MongoDB para gerenciar vendas mensais. Ele permite criar, listar, atualizar e remover registros de vendas mensais de forma simples e eficiente.

## Funcionalidades

- **Criar venda mensal:**  
  `POST /vendas`  
  Adiciona um novo registro de venda mensal.

- **Listar vendas mensais:**  
  `GET /vendas`  
  Retorna todos os registros de vendas mensais.

- **Atualizar venda mensal:**  
  `PUT /vendas/:id`  
  Atualiza um registro de venda mensal pelo ID.

- **Remover venda mensal:**  
  `DELETE /vendas/:id`  
  Remove um registro de venda mensal pelo ID.

## Tecnologias Utilizadas

- Node.js
- Express
- MongoDB (via Mongoose)
- Dotenv

## Como executar

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   cd seu-repositorio
   ```

2. **Instale as dependências:**
   ```bash
   npm install
   ```

3. **Configure o arquivo `.env`:**
   ```
   MONGO_URI=seu_link_de_conexao_mongodb
   ```

4. **Inicie o servidor:**
   ```bash
   node server.js
   ```

O servidor estará disponível em `http://localhost:3000`.

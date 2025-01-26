O backend é construído com Node.js, Express e Prisma.

### Instalação

1. Navegue até o diretório `backend`:
    ```sh
    cd backend
    ```

2. Instale as dependências:
    ```sh
    npm install
    ```

3. Configure o banco de dados no arquivo `.env`:
    ```
    DATABASE_URL="sua_url_do_banco_de_dados"
    ```

4. Execute as migrações do Prisma:
    ```sh
    npx prisma migrate dev
    ```

5. Inicie o servidor:
    ```sh
    node server.js
    ```

### Endpoints

- `POST /users`: Cria um novo usuário.
- `GET /users`: Retorna todos os usuários ou filtra por nome, email ou idade.
- `PUT /users/:id`: Atualiza um usuário existente.
- `DELETE /users/:id`: Deleta um usuário.

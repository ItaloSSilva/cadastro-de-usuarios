# Cadastro de Usuários

Aplicação web para cadastro de usuários.

## Estrutura do Projeto

## Backend

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

## Frontend

O frontend é construído com React e Vite.

### Instalação

1. Navegue até o diretório [frontend](http://_vscodecontentref_/14):
    ```sh
    cd frontend
    ```

2. Instale as dependências:
    ```sh
    npm install
    ```

3. Inicie o servidor de desenvolvimento:
    ```sh
    npm run dev
    ```

### Estrutura

- [main.jsx](http://_vscodecontentref_/15): Ponto de entrada da aplicação React.
- [index.jsx](http://_vscodecontentref_/16): Componente principal da página de cadastro de usuários.
- [api.js](http://_vscodecontentref_/17): Configuração do Axios para chamadas à API.

## Licença

Este projeto está licenciado sob a licença ISC.

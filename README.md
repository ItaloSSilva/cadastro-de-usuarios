# Cadastro de Usuários

Aplicação web para cadastro de usuários, composta por um backend em Node.js com Express e Prisma, e um frontend em React com Vite.

## Estrutura do Projeto

## Backend

O backend é responsável por gerenciar o banco de dados e fornecer uma API RESTful para o frontend.

### Tecnologias Utilizadas

- Node.js
- Express
- Prisma

### Instalação e Configuração

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
    npm start
    ```

### Endpoints

- `POST /users`: Cria um novo usuário.
- `GET /users`: Retorna todos os usuários ou filtra por nome, email ou idade.
- `PUT /users/:id`: Atualiza um usuário existente.
- `DELETE /users/:id`: Deleta um usuário.

## Frontend

O frontend é responsável pela interface do usuário e comunicação com o backend.

### Tecnologias Utilizadas

- React
- Vite
- Axios

### Instalação e Configuração

1. Navegue até o diretório [frontend](http://_vscodecontentref_/1):
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

### Estrutura de Diretórios

- `src/main.jsx`: Ponto de entrada da aplicação React.
- `src/pages/home/index.jsx`: Componente principal da página de cadastro de usuários.
- `src/services/api.js`: Configuração do Axios para chamadas à API.

## Licença

Este projeto está licenciado sob a licença ISC.

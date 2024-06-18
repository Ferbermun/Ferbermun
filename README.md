## Funcionalidades

- Criação de tickets de atendimento
- Listagem de tickets
- Atualização de status dos tickets

## Tecnologias Utilizadas

### Backend
- Node.js
- Express
- Mongoose
- MongoDB

### Frontend
- React
- Axios
- React Router DOM

## Instalação

### Pré-requisitos

- Node.js instalado
- MongoDB em execução

### Passos para configurar o ambiente de desenvolvimento

1. Clone o repositório:
    ```bash
    git clone https://github.com/seu-usuario/color-graf-atendimento.git
    cd color-graf-atendimento
    ```

2. Configure o Backend:
    ```bash
    cd backend
    npm install
    ```

3. Crie um arquivo `.env` na pasta `backend` com o seguinte conteúdo:
    ```
    PORT=5000
    MONGO_URI=mongodb://localhost:27017/colorgraf
    ```

4. Inicie o servidor backend:
    ```bash
    npm run dev
    ```

5. Configure o Frontend:
    ```bash
    cd ../frontend
    npm install
    ```

6. Inicie o servidor frontend:
    ```bash
    npm start
    ```

## Uso

1. Acesse o frontend no seu navegador em `http://localhost:3000`.
2. Use a interface para criar e listar tickets de atendimento.

## Contribuição

Se você deseja contribuir com o projeto, siga os passos abaixo:

1. Faça um fork do repositório.
2. Crie uma branch para sua feature (`git checkout -b feature/nome-da-feature`).
3. Commit suas mudanças (`git commit -m 'Adiciona nova feature'`).
4. Envie para o branch principal (`git push origin feature/nome-da-feature`).
5. Abra um Pull Request.

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

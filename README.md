# SoulCode Pets - Back End

Bem-vindo ao back-end do projeto SoulCode Pets! Este é o servidor que fornece a API para gerenciar informações sobre pets, permitindo a criação, leitura, atualização e exclusão de dados.

## Tecnologias Utilizadas

- **Node.js**: Ambiente de execução para JavaScript no servidor.
- **Express**: Framework para criar APIs e gerenciar rotas.
- **MongoDB**: Banco de dados NoSQL para armazenar informações dos pets.
- **Mongoose**: Biblioteca para modelar dados e interagir com o MongoDB.

## Instalação

1. **Clone o Repositório**

   ```bash
   git clone https://github.com/SEU_USUARIO/SoulCode-Pets-Back-End.git
   ```
2. **Navegue para o Diretório do Projeto

   ```bash
   cd SoulCode-Pets-Back-End
   ```
3. **Instale as Dependências

   ```bash
   npm install
   ```

4. **Configuração do Ambiente
- Crie um arquivo .env na raiz do projeto e adicione as seguintes variáveis:

   ```bash
   MONGODB_URI=mongodb://localhost:27017/soulcode-pets
   PORT=3000
  ```

5. **Inicie o Servidor

  ```bash
  npm start
  ```
- O servidor estará disponível em http://localhost:3000.

## Estrutura do Projeto
- src/: Contém o código fonte do servidor.
  - controllers/: Lida com a lógica de negócio e interage com o banco de dados.
    - petController.js: Funções para gerenciar pets.
- models/: Definições dos modelos de dados.
  - petModel.js: Modelo para pets.
- routes/: Define as rotas da API.
  - petRoutes.js: Rotas para operações relacionadas a pets.
- config/: Configurações do projeto.
  - db.js: Configuração e conexão com o MongoDB.
- server.js: Arquivo principal que inicializa o servidor.

 
## Endpoints da API
- As seguintes rotas estão disponíveis para interagir com a API:

    - GET /pets: Recupera todos os pets.
    - GET /pets/:id: Recupera um pet específico pelo ID.
    - POST /pets: Adiciona um novo pet.
    - PUT /pets/:id: Atualiza um pet existente.
    - DELETE /pets/:id: Exclui um pet pelo ID.

## Testes
- Para rodar os testes, certifique-se de ter as dependências instaladas e execute:

   ```bash
  npm test
   ```
## Contribuindo
- Faça um Fork do Repositório

Crie uma Branch para sua Feature

   ```bash
  git checkout -b minha-feature
   ```
- Faça suas Alterações e Commit

   ```bash
  git add .
  git commit -m "Adiciona nova funcionalidade"
   ```
   
## Envie para o Repositório Remoto

  ```bash
  git push origin minha-feature
  ```
- Abra um Pull Request

- Vá para a página do repositório no GitHub e abra um novo pull request para sua branch.

## Licença
Este projeto está licenciado sob a MIT License.

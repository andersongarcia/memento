# Memento

Memento é um sistema para organização e acompanhamento de registros e ocorrências associadas a diferentes itens. 

## 🚀 Funcionalidades

- Cadastro e organização de itens por temas
- Registro e categorização de ocorrências associadas a itens
- Definição personalizada de tipos de ocorrências por tema
- Interface web responsiva para gerenciamento dos registros
- API REST para comunicação entre frontend e backend
- Testes automatizados para garantir qualidade e robustez

## 🛠️ Tecnologias

**Backend**
- C# / ASP.NET Core 
- Entity Framework Core
- PostgreSQL 
- xUnit/NUnit para testes
- JWT para autenticação (futuro)

**Frontend**
- React (com TypeScript, se necessário)
- React Query / Redux para gerenciamento de estado
- Jest + Testing Library para testes unitários
- Cypress para testes end-to-end

**Infraestrutura**
- Docker para conteinerização do ambiente de desenvolvimento e produção
- Docker Compose para orquestração dos containers

## 📦 Como Rodar o Projeto

### 1️⃣ Configurar o Backend
1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/memento.git
   cd memento/backend
   ```
2. Instale as dependências:
   ```bash
   dotnet restore
   ```
3. Configure o banco de dados (exemplo usando PostgreSQL):
   ```bash
   dotnet ef database update
   ```
4. Inicie a API:
   ```bash
   dotnet run
   ```

### 2️⃣ Configurar o Frontend
1. Acesse a pasta do frontend:
   ```bash
   cd ../frontend
   ```
2. Instale as dependências:
   ```bash
   npm install
   ```
3. Inicie o servidor de desenvolvimento:
   ```bash
   npm run dev
   ```

### 3️⃣ Rodar o Projeto com Docker
1. Certifique-se de que o Docker e o Docker Compose estão instalados.
2. Na raiz do projeto, execute:
   ```bash
   docker-compose up --build
   ```
3. O backend estará acessível em `http://localhost:5000` e o frontend em `http://localhost:3000`.

## 🔮 Próximos Passos
- Criar a estrutura inicial do banco de dados
- Implementar os primeiros endpoints da API
- Criar os primeiros componentes do frontend
- Configurar os testes automatizados
- Definir autenticação e controle de usuários (futuro)

## 📌 Contribuição
Este é um projeto pessoal com foco em aprendizado e boas práticas de desenvolvimento. Sugestões e melhorias são sempre bem-vindas!

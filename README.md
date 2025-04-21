# Cadastro de Usuários

## Sobre o projeto

Este é um projeto de **aplicação de cadastro de usuários**, criado com o objetivo de permitir a criação, listagem, edição e exclusão de usuários em uma API simples e funcional. Futuramente, o projeto será evoluído para se tornar uma **lista de contatos** completa, proporcionando funcionalidades mais avançadas para gerenciamento de contatos.

---

## Funcionalidades
Atualmente, o projeto conta com as seguintes funcionalidades:
- **Cadastrar Usuários:** Adicionar novos usuários com informações como nome, idade e e-mail.
- **Listar Usuários:** Obter uma lista com todos os usuários cadastrados.
- **Editar Usuários:** Atualizar informações de um usuário existente.
- **Deletar Usuários:** Remover usuários do sistema.

---

## Tecnologias Utilizadas
Este projeto foi desenvolvido com:
- **Node.js**: Ambiente de execução JavaScript.
- **Express**: Framework para criação de rotas e gerenciamento da API.
- **MongoDB**: Banco de dados NoSQL para armazenar os dados dos usuários.
- **Prisma**: Ferramenta para interação com o banco de dados e gerenciamento de modelos.

---

## Como executar o projeto

### Pré-requisitos
- **Node.js** instalado (v20 ou mais recente).
- Gerenciador de pacotes **npm** ou **yarn**.
- Uma instância do MongoDB ativa (local ou em MongoDB Atlas).
- Arquivo `.env` com a configuração da variável `DATABASE_URL`.

### Passos
1. Clone o repositório:
   ```bash
   git clone https://github.com/seuUsuario/cadastro-back.git
2. Instale as dependencias:
  npm install
3.Gere o Prisma Client:
  npx prisma generate
4.Execute o servidor:
  node server.js



Próximos passos
Os próximos passos para evolução do projeto incluem:
- Conversão para uma lista de contatos completa.
- Implementação de autenticação para os usuários.
- Criação de filtros avançados (ex.: por idade, nome ou e-mail).
- Integração com front-end para visualização e interação.




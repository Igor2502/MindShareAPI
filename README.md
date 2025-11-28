# MindShare - API GraphQL para Gestão de Ideias

![Status](https://img.shields.io/badge/status-em%20desenvolvimento-purple)
![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)
![Made with GraphQL](https://img.shields.io/badge/API-GraphQL-E10098?logo=graphql)


Seja bem-vindo ao **MindShare - API**, um projeto backend desenvolvido como parte do módulo de "Back-end GraphQL" da pós-graduação Tech Developer 360 da [Faculdade de Tecnologia da Rocketseat](https://www.rocketseat.com.br/faculdade). O objetivo principal deste projeto é consolidar os conhecimentos sobre GraphQL.


## 🚀 Sobre o Projeto

**MindShare** é uma plataforma que permitirá que equipes proponham ideias, dêem feedbacks e votem nas melhores sugestões.
Este projeto foi desenvolvido com foco na implementação de um esquema GraphQL robusto, utilizando Apollo Server para gerenciar as queries e mutations e Prisma como ORM, garantindo uma aplicação bem tipada com TypeScript.

## ✨ Funcionalidades
 - Criação de usuários.
 - Login e validação de tokens JWT.
 - Criação/atualização de ideias.
 - Exibir lista de ideias cadastradas.
 - Exclusão de ideias.
 - Criação de comentários para cada ideia.
 - Opção de votar em ideias.


## 🛠️ Tecnologias Utilizadas
 - GraphQl *(v16.12.0)*.
 - Apollo Server *(v.5.1.0)*.
 - Prisma *(v6.18.0)*.
 - Express *(v5.1.0)*.
 - Typescript *(v5.9.3)*.
 - JSON Web Tokens.
 - SQLite (Banco de dados local para desenvolvimento).


## 🖥️ Instalação e Execução
### Pré-requisitos
 - Node.js (versão 22.18 ou superior);
 - Gerenciador de pacotes npm;

### Etapas de configuração:

#### 1. Clone o repositório e acesse o diretório do projeto:
```bash
git clone https://github.com/Igor2502/MindShareAPI.git
```

#### 2. Instale as dependências:
```bash
npm install
```

#### 3. Crie um arquivo ``.env`` com as variáveis de ambiente necessárias (exemplo disponível em ``.env.example``).
 ```bash
cp .env.example .env
 ```

#### 4. Inicie o servidor:
```bash
npm run dev
```

#### 5. Caso tudo tenha dado certo você terá recebido o seguinte retorno:
```bash
> mindshare@1.0.0 dev
> tsx watch src/index.ts

Servidor iniciado na porta: 4000!
```

#### 6. Acesse o Playground GraphQL:
Após iniciar o servidor, a API estará acessível em ``http://localhost:4000/graphql``. Você pode interagir com as queries e mutations utilizando o Apollo Sandbox (Playground GraphQL) no seu navegador.


## 🤝 Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests com melhorias, correções ou novas funcionalidades.


## 📄 Licença
Este projeto está licenciado sob a [MIT License](./LICENSE).


## 👨‍💻 Autor
Desenvolvido com ❤️ por [👨‍🚀Igor](https://www.linkedin.com/in/igor-gomes-da-silva/) como parte da pós-graduação da [FTR 🚀](https://www.rocketseat.com.br/faculdade).

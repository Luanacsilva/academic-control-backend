# 🎓 Academic Control API — Backend de Gestão Educacional

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)


Este repositório contém o backend da **Academic Control**, uma API RESTful para gerenciamento de usuários em um ambiente educacional.  
O sistema é focado em prover diferentes níveis de acesso para **alunos**, **professores** e **gestores**, com autenticação segura e rotas protegidas.

> Desenvolvido com Node.js + TypeScript + MongoDB, este backend é o núcleo de um painel acadêmico completo.

---

## 🚀 Tecnologias Utilizadas

- Node.js
- TypeScript
- Express
- MongoDB + Mongoose
- JWT (Autenticação)
- UUID
- Bcrypt
- Dotenv
- Swagger (Documentação da API)

---

## 🧠 Funcionalidades

- Cadastro e login de usuários
- Controle de permissões por perfil (aluno, professor, gestor)
- Rotas protegidas com autenticação JWT
- Organização modular: controllers, services, middlewares
- Integração com banco de dados MongoDB
- Documentação com Swagger

---

## 📁 Estrutura do Projeto

```bash
## 📁 Estrutura do Projeto

```bash
academic-control-backend/
├── prisma/              # Configurações do Prisma e esquemas do banco de dados
├── src/                 # Código-fonte principal do backend
│   ├── controllers/     # Controladores das rotas e regras de negócio
│   ├── routes/          # Definições das rotas da API
│   ├── middlewares/     # Middlewares (ex: autenticação, validações)
│   ├── services/        # Lógica de serviços (conexões com banco, regras)
│   ├── utils/           # Utilitários e helpers reutilizáveis
│   └── index.ts         # Arquivo principal de inicialização da aplicação
├── .gitignore           # Arquivos e diretórios ignorados pelo Git
├── package.json         # Dependências e scripts do projeto
├── tsconfig.json        # Configurações do TypeScript
└── README.md            # Documentação do projeto
```

---

##
---

## 📄 Documentação da API

A documentação da API está disponível via Swagger:

GET /api-docs

Ou diretamente via o arquivo `swagger.json` no repositório.

---

## ▶️ Como Executar o Projeto

1. Clone o repositório:

```bash
git clone https://github.com/Luanacsilva/academic-control-backend.git
cd academic-control-backend
```

2. Instale as dependências:

```bash
npm install
```

3. Configure o arquivo .env:

```bash
PORT=3000
MONGO_URI=seu_mongo_uri
JWT_SECRET=sua_chave_super_secreta
```

4. Inicie o servidor:

```bash
npm run dev
 ```

---

## 👥 Contribuidores

<table> <tr> <td align="center"> <a href="https://github.com/Luanacsilva"> <img src="https://avatars.githubusercontent.com/u/00000000?v=4" width="100px;" alt="Luana"/><br /> <sub><b>Luana Cristina da Silva</b></sub> </a><br/> <code>@Luanacsilva</code> </td> <td align="center"> <a href="https://github.com/xLupus"> <img src="https://avatars.githubusercontent.com/u/82850927?v=4" width="100px;" alt="Vinícius"/><br /> <sub><b>Vinícius A Souza</b></sub> </a><br/> <code>@xLupus</code> </td> </tr> </table>


---

## ⚖️ Licença

Este projeto está licenciado sob a licença MIT.







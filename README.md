# Projeto: PostgreSQL + pgAdmin com Docker Compose

Este projeto sobe uma instância do PostgreSQL e do pgAdmin utilizando Docker Compose, com organização própria para ambientes de desenvolvimento e publicação no GitHub.

## 🚀 Como subir o projeto

1. Renomeie o arquivo `.env.example` para `.env` e edite com suas credenciais.
2. Execute o comando:

```bash
docker-compose up -d
```

3. Acesse o pgAdmin:
   - URL: [http://localhost:8080](http://localhost:8080)
   - Login: conforme definido no `.env`

## 📦 Serviços

- **PostgreSQL:** banco de dados relacional.
- **pgAdmin:** ferramenta gráfica de administração do PostgreSQL.

## 🔐 Segurança

- Variáveis sensíveis estão armazenadas no arquivo `.env` (não versionado).
- Certifique-se de usar senhas seguras e não subir arquivos sensíveis ao repositório.

## 📁 Estrutura do Projeto

```
.
├── .env
├── .gitignore
├── docker-compose.yml
└── README.md
```

## 🛠 Requisitos

- Docker e Docker Compose instalados.
- Git e Visual Studio (opcional) para gerenciar e editar o projeto.

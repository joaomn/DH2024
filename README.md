# Hefesto Deployment with Docker Compose

Este repositório contém o `docker-compose.yaml` necessário para realizar o deploy da aplicação Hefesto em uma VM no Azure.

## Imagens Docker Utilizadas

- **Backend**: `jhonyamn/mustang:1.2b`
- **Frontend**: `jhonyamn/nascar:1.0`

## Variáveis de Ambiente

Certifique-se de definir as seguintes variáveis de ambiente antes de iniciar o deploy:

- `DATABASE_URL`: URL de conexão com o banco de dados.
- `SPRING_DATASOURCE_USERNAME`: Usuário do banco de dados para o Spring.
- `SPRING_DATASOURCE_PASSWORD`: Senha do banco de dados para o Spring.
- `VITE_API_URL`: URL da API para o Vite.

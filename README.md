# n8n no Render

Esse repositório foi criado para subir o [n8n](https://n8n.io/) no [Render](https://render.com/) usando a imagem oficial `n8nio/n8n:latest`.

## Objetivo
Demonstrar fluxos automatizados no n8n para compor portfólio (focado em qualificação de leads).

## Deploy
1. Subir este repositório no GitHub
2. Criar um Web Service no Render conectado a este repo
3. Conectar com PostgreSQL externo (ex: [Supabase](https://supabase.com/)) via variáveis de ambiente
4. Configurar `N8N_ENCRYPTION_KEY` e dados do banco

## Tecnologias
- n8n (self-hosted)
- Docker
- PostgreSQL (Supabase Transaction Pooler porta 6543)


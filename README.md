# Backend (Directus) — Projeto Maquilhagem

## Local
1) Copie `.env.example` para `.env` e preencha DB da Supabase.
2) `docker compose up -d`
3) Aceda `http://localhost:8055/admin`.

## Render
- Crie Web Service (Docker) a partir deste repositório.
- Em **Environment Variables**, crie todas as keys do `.env.example`
  (NÃO faça upload do `.env`).
- Health check: `/server/health`.
- Após deploy: `https://SEU-SERVICO.onrender.com/admin`.

# Deploy Doctor

Validacao automatica de saude tecnica pos deploy.

## Problema
Deploys sobem sem checklist tecnico completo.

## Publico
DevOps, backend e equipes de platform engineering.

## MVP
- Teste de dominio, DNS e certificado SSL.
- Smoke de rotas e endpoints criticos.
- Verificacao de headers de seguranca.
- Relatorio consolidado por ambiente.

## Stack
- React + TypeScript + Vite
- Node + Express + TypeScript
- CI com lint/test/build/audit

## Setup
1. npm install --include=dev
2. npm run bootstrap
3. npm run dev

## Monetizacao
Plano por execucao com monitoramento continuo.

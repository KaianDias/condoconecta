# ADR 0001: Escolha da stack tecnológica

**Status:** Aceito
**Data:** 22/09/2026

## Contexto

O CondoConecta precisa de uma stack simples de manter por um único desenvolvedor, com bom suporte a testes automatizados e implantação contínua.

## Decisão

- Backend: Node.js com Express
- Frontend: React
- Banco de dados: PostgreSQL, via Prisma ORM
- Hospedagem: Render, usando Blueprint (render.yaml) como infraestrutura como código
- CI/CD: GitHub Actions

## Consequências

Essa stack tem ampla documentação, é gratuita para os planos usados no projeto e se integra bem com GitHub Actions, o que reduz o esforço de configuração dos pipelines descritos no PGCS.

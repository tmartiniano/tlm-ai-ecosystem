# TLM AI Ecosystem

> Infraestrutura de IA gerenciada para automação de negócios, desenvolvida e mantida pela [TLM Tecnologia](https://tlmtecnologia.com).

## O que é este projeto

Ecossistema completo de agentes de IA, automações e integrações construído sobre infraestrutura própria em VPS, projetado para ser oferecido como serviço recorrente em três planos distintos conforme a maturidade técnica do cliente.

## Stack principal

| Camada | Tecnologia |
|---|---|
| Orquestração | n8n self-hosted |
| WhatsApp | Evolution API |
| Banco de dados | Supabase (PostgreSQL + pgvector) |
| Agentes de IA | Claude + OpenAI |
| Memória e RAG | Embeddings + Supabase pgvector |
| Infraestrutura | Docker + Nginx + Contabo VPS |
| Contexto persistente | MCP (Model Context Protocol) |

## Planos disponíveis

**Base:** agente único pré-configurado para clientes em fase inicial de adoção de IA.

**Pro:** ambiente semi-dedicado com múltiplos agentes integrados, ideal para quem já opera com automações e quer escalar.

**Premium:** infraestrutura dedicada com multiagentes orquestrados, RAG, dashboards e parceria técnica contínua.

## Estrutura do repositório
tlm-ai-ecosystem/ ├── docs/ # Documentação técnica de cada módulo ├── infra/ # Docker Compose e configurações de infraestrutura ├── agents/ # Código dos agentes de IA ├── workflows/ # Exports dos fluxos do n8n └── prompts/ # Biblioteca de prompts organizados por caso de uso

## Autor

**Thiago Martiniano**
TLM Tecnologia · [app.tlmtecnologia.com](https://app.tlmtecnologia.com)
GitHub: [@tmartiniano](https://github.com/tmartiniano)

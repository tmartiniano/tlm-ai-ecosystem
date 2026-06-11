# TLM AI Ecosystem

> Infraestrutura de IA gerenciada para automações inteligentes, agentes autônomos e integrações com WhatsApp, CRM e APIs.

**Desenvolvido e mantido por [Thiago Martiniano](https://github.com/tmartiniano)**

---

## Sobre o Projeto

O TLM AI Ecosystem é uma infraestrutura completa de IA construída para entregar automações inteligentes como serviço recorrente. O ecossistema combina agentes de IA, orquestração de fluxos, RAG com embeddings e integrações com WhatsApp, CRM e APIs externas.

---

## Stack Principal

| Camada | Tecnologia |
|---|---|
| Agentes de IA | Claude Code + OpenAI |
| Banco de Dados + Vetores | Supabase + pgvector |
| Orquestração | n8n (self-hosted) |
| WhatsApp | Evolution API |
| Contexto Persistente | MCP |
| Infraestrutura | Docker + VPS Ubuntu |
| Proxy Reverso | Nginx + SSL |

---

## Planos Disponíveis

### Base
Para quem está começando. Agente único pré-configurado com caso de uso específico, infraestrutura compartilhada e suporte por ticket.

### Pro
Para quem já opera com automações. Ambiente semi-dedicado com múltiplos agentes integrados, RAG, CRM e SLA de suporte definido.

### Premium
Para quem quer o potencial máximo. Ambiente dedicado, multiagentes orquestrados, memória de longo prazo, dashboards e parceria técnica mensal.

---

## Estrutura do Repositório
tlm-ai-ecosystem/ ├── docs/ # Documentação de cada etapa ├── infra/ # Docker Compose e configurações ├── agents/ # Código dos agentes de IA ├── workflows/ # Exports dos fluxos n8n └── prompts/ # Biblioteca de prompts

---

## Documentação

Cada etapa da construção está documentada na pasta `/docs`, em ordem de execução.

---

* TLM AI Ecosystem · 2026*

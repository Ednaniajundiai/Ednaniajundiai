# Ednan Ferreira da Silva

### Engenheiro de Software Backend · Python · FastAPI
**Sistemas com LLMs e agentes conversacionais em produção**

Projeto e opero sistemas backend em produção de ponta a ponta — da arquitetura à
sustentação. **FastAPI, PostgreSQL, Redis e Docker**, integrações via API e webhooks,
e IA generativa aplicada com previsibilidade de arquitetura: LLM integrado a fluxo
de negócio, com saída controlada e auditável — não geração livre.

Trabalho orientado a especificação (**SDD — Spec Driven Development**): spec antes
do código, validação via pytest e code review.

Mais de 10 anos em Supply Chain em ambiente corporativo antes da engenharia de
software — leio a regra de negócio antes de escrever a primeira linha.

---

## 🛠️ Stack

**Backend** `Python` `FastAPI` `SQLAlchemy` `Pydantic` `Node.js`
**Dados & Cache** `PostgreSQL` `Redis` `pgvector` `Row Level Security`
**IA Generativa** `LangGraph` `LangChain` `RAG` `MCP` `Vertex AI`
**Integrações** `REST/JSON` `Webhooks` `WhatsApp API` `Meta Graph API` `OAuth2 / JWT`
**Infra** `Docker` `Docker Swarm` `Nginx` `CI/CD` `GitHub Actions` `Cloud Run`
**Qualidade** `Pytest` `Clean Architecture` `SDD`

---

## 📂 Projetos em Produção

> Os sistemas abaixo estão em operação com clientes reais, incluindo dados
> sensíveis sob LGPD. Por isso os repositórios são privados — o que publico aqui
> é a documentação de arquitetura. Código disponível para apresentação em call
> ou acesso de leitura mediante solicitação.

### 🧠 SomaVital — Plataforma NR-01 *(privado)*
SaaS multi-tenant para gestão de risco psicossocial (NR-01 / COPSOQ II).
Motor de scoring **determinístico** em Python, com regras externalizadas em YAML;
LLM restrito à borda auditável para geração de saídas. Isolamento multi-tenant via
**Row Level Security** no PostgreSQL, RBAC e JWT RS256.
Selecionado entre 700+ inscritos no AI for Social Impact Hackathon (Google DeepMind)
e apresentado no meetup do AI Tinkerers SP.
`FastAPI` `PostgreSQL` `RLS` `Clean Architecture` `LGPD`
📄 [Documento de arquitetura](LINK)

### 🤖 Atendimento automatizado via WhatsApp — setor de saúde *(privado)*
Bot em produção há mais de um ano, com dado sensível de paciente sob LGPD.
Máquina de estados própria em Python, estado externalizado em Redis com TTL,
ingestão de webhook com ACK imediato e processamento assíncrono, idempotência por
ID de mensagem, retry com backoff e handoff para humano. Roteamento distinto entre
paciente ativo e lead. Iniciado em Botpress/n8n e reescrito em Python.
`Python` `Redis` `Webhooks` `WhatsApp API` `Docker`
📄 [Documento de arquitetura](LINK)

### 💰 RotaVenda — CRM financeiro *(privado)*
CRM para rotas de venda a prazo, com lógica de parcelas e saldo calculado em runtime.
Inclui pipeline de digitalização de registro manuscrito com LLM e validação
determinística por schema — o que não passa vai para revisão humana.
`FastAPI` `PostgreSQL` `Redis`
📄 [Vitrine pública](https://github.com/Ednaniajundiai/RotaVenda-Portfolio)

---

## 🎓 Formação

- **MBA em Engenharia de Software** — USP/ESALQ *(em andamento, 2025–2027)*
- **MBA em Supply Chain** — USF *(2023–2024)*
- **Bacharelado em Engenharia Elétrica** — USF *(2015–2020)*

---

## 📫 Contato

📍 Jundiaí, SP — Híbrido · Remoto
📧 ednanferreira@gmail.com
💼 [LinkedIn](https://www.linkedin.com/in/ednan-ferreira)

<sub>Metodologia: SDD com specs versionadas, apoio de ferramentas de AI coding
e validação via pytest.</sub>
